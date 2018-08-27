{
  "info": {
    "name": "Microsoft Graph API List Directory Role Templates",
    "_postman_id": "45452cdd-fc75-4f40-aea6-a5265eae64d8",
    "description": "List directoryRoleTemplates Retrieve a list of directoryRoleTemplate objects.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "list",
      "item": [
        {
          "id": "ff648953-fc0e-42e8-855d-26c39ddde478",
          "name": "ListDirectoryRoleTemplates",
          "request": {
            "url": "http://graph.microsoft.com/directoryRoleTemplates",
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
            "description": "List directoryRoleTemplates Retrieve a list of directoryRoleTemplate objects"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "f9c45e95-4205-47e0-8561-3865d1d48b32"
            }
          ]
        }
      ]
    }
  ]
}