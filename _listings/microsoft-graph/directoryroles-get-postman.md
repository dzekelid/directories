{
  "info": {
    "name": "Microsoft Graph API List Directory Roles",
    "_postman_id": "87954f4c-5a2a-479a-82ee-19c729c55b58",
    "description": "List directoryRoles List the directory roles that are activated in the tenant.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "list",
      "item": [
        {
          "id": "ba2fbad7-c130-4267-b2b7-97bfafde7da6",
          "name": "ListDirectoryRoles",
          "request": {
            "url": "http://graph.microsoft.com/directoryRoles",
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "Authorization",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "List directoryRoles List the directory roles that are activated in the tenant"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "0a7db562-7ed9-4768-a09b-8f5058280f17"
            }
          ]
        }
      ]
    }
  ]
}