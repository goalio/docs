Spieler
=======

.. http:get:: /api/bap/v1/user

   Liste von allen BOOKANDPLAY Benutzern abrufen

   **Beispiel request**:

   .. sourcecode:: http

      GET /api/bap/v1/user HTTP/1.1
      Host: example.com
      Accept: application/json

   **Beispiel response**:

   .. sourcecode:: http

      HTTP/1.1 200 OK
      Content-Type: application/json

      {
        "success": true,
        "message": "Saved successfully"
        "total":2
        "data":
        [
            {
                "bapId":123,
                "firstName":"Hans",
                "lastName":"Meier",
                ...
            },
            {
                "bapId":124,
                "firstName":"Max",
                "lastName":"Mustermann",
                ...
            }
        ]
      }

   :query sort: one of ``hit``, ``created-at``
   :query offset: offset number. default is 0
   :query limit: limit number. default is 30
   :reqheader Accept: the response content type depends on :mailheader:`Accept` header
   :reqheader Authorization: optional OAuth token to authenticate
   :resheader Content-Type: this depends on :mailheader:`Accept` header of request
   :statuscode 200: no error
   :statuscode 404: there's no user