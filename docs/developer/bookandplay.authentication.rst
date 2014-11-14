Authentifizierung
=================

.. http:post:: /oauth/token

   Mit Hilfe des bei BOOKANDPLAY hinterlegten Client ID und Client Secrets einen Access Token bei der goalio Applikation beantragen.

   **Beispiel request**:

   .. sourcecode:: http

      GET /oauth/token HTTP/1.1
      Authorization: Basic Ym9va2FuZHBsYXk6MTIzNDU2
      grant_type=client_credentials&scope=bap_users+bap_booking

   **Beispiel response**:

   .. sourcecode:: http

      HTTP/1.1 200 OK
      Content-Type: application/json
      {
        "access_token":"f3b626f3fce4e24ce0ea5f706be2c08bf880a717",
        "expires_in":3600,
        "token_type":"Bearer",
        "scope":"bap_users bap_booking"
      }


   :query string grant_type: Ist immer ''client_credentials''
   :query string scope: Ist immer ''bap_users bap_booking''
   :reqheader Authorization: ``Basic authentication`` mit base64 kodiertem Client ID udn Client Secret
   :resheader Content-Type: this depends on :mailheader:`Accept` header of request
   :>json string access_token: Token das bei folgenden Reuqests genutzt werden muss
   :>json int expires_in: Gültigkeit des Tokens in Sekunden
   :>json string token_type: Typ des Tokens. In diesem Fall immer Bearer
   :>json string scope: Token ist gültig für diese Scopes
   :statuscode 200: Kein Error
   :statuscode 404: there's no user