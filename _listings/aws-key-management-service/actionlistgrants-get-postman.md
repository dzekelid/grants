{
  "info": {
    "name": "AWS Key Management Service API List Grants",
    "_postman_id": "a54381b9-8bd1-4f51-9668-bf64d9f220fa",
    "description": "List the grants for a specified key.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Keys",
      "item": [
        {
          "id": "72936239-7ba7-4499-be4d-7b2770922d59",
          "name": "cancelKeyDeletion",
          "request": {
            "url": "http://example.com/api/?Action=CancelKeyDeletion?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels the deletion of a customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de951a5a-14b6-49f8-b579-ac1bedd924bc"
            }
          ]
        },
        {
          "id": "9dc60fb5-45a9-423d-a6e3-66322f1202a9",
          "name": "createKey",
          "request": {
            "url": "http://example.com/api/?Action=CreateKey?BypassPolicyLockoutSafetyCheck=BypassPolicyLockoutSafetyCheck&Description=Description&KeyUsage=KeyUsage&Origin=Origin&Policy=Policy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8d392f45-0fe2-4d97-b02e-26ae5dce935a"
            }
          ]
        },
        {
          "id": "c3e2896a-3cd8-4230-9a89-98c7b4273762",
          "name": "deleteImportedKeyMaterial",
          "request": {
            "url": "http://example.com/api/?Action=DeleteImportedKeyMaterial?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes key material that you previously imported and makes the specified customer\n      master key (CMK) unusable."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98c00ccd-0fe1-4591-8932-e8eaa5cc5645"
            }
          ]
        },
        {
          "id": "56dd533c-dabc-4fc2-a37f-87f5bb79e8ab",
          "name": "describeKey",
          "request": {
            "url": "http://example.com/api/?Action=DescribeKey?GrantTokens=GrantTokens&KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Provides detailed information about the specified customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fe439788-fed6-4395-afd9-8dd898f5b38e"
            }
          ]
        },
        {
          "id": "4aadad9e-7c8d-4479-b12a-fd9a3d4b84e3",
          "name": "disableKey",
          "request": {
            "url": "http://example.com/api/?Action=DisableKey?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Sets the state of a customer master key (CMK) to disabled, thereby preventing its use\n      for cryptographic operations."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "254e328c-23a1-400a-8aff-02f4d691ae8a"
            }
          ]
        },
        {
          "id": "be3ea0a2-9067-46ce-9ed8-d97b064b1a16",
          "name": "disableKeyRotation",
          "request": {
            "url": "http://example.com/api/?Action=DisableKeyRotation?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Disables rotation of the specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2af2c7f9-60a3-4477-ac0b-c3e98aad6030"
            }
          ]
        },
        {
          "id": "ff7d904f-feef-47b0-b4da-e5886b70531f",
          "name": "enableKey",
          "request": {
            "url": "http://example.com/api/?Action=EnableKey?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Marks a key as enabled, thereby permitting its use."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a773ebd-05ac-4732-90c1-5b40b86716b8"
            }
          ]
        },
        {
          "id": "c80d1105-2b4d-4464-8b6b-12135768fe61",
          "name": "enableKeyRotation",
          "request": {
            "url": "http://example.com/api/?Action=EnableKeyRotation?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Enables rotation of the specified customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c717edfc-f4f1-42c8-aefb-97a9568dd0ab"
            }
          ]
        },
        {
          "id": "3e6207af-9790-47f8-806f-964d0ce8ab0c",
          "name": "generateDataKey",
          "request": {
            "url": "http://example.com/api/?Action=GenerateDataKey?EncryptionContext=EncryptionContext&GrantTokens=GrantTokens&KeyId=KeyId&KeySpec=KeySpec&NumberOfBytes=NumberOfBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a data encryption key that you can use in your application to encrypt\n      data locally."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "08f311d2-c986-4429-930a-33f780a5237b"
            }
          ]
        },
        {
          "id": "5f42064d-c263-4b73-842f-21596c5b1de2",
          "name": "generateDataKeyWithoutPlaintext",
          "request": {
            "url": "http://example.com/api/?Action=GenerateDataKeyWithoutPlaintext?EncryptionContext=EncryptionContext&GrantTokens=GrantTokens&KeyId=KeyId&KeySpec=KeySpec&NumberOfBytes=NumberOfBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a data encryption key encrypted under a customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47cc77aa-521b-4e19-91e9-02448579763e"
            }
          ]
        },
        {
          "id": "5beddcbf-6a6b-4196-bdf1-bbb063eb957a",
          "name": "getKeyRotationStatus",
          "request": {
            "url": "http://example.com/api/?Action=GetKeyRotationStatus?KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a Boolean value that indicates whether key rotation is enabled for the\n      specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e86cf469-4e82-445b-9f0a-7c64399c2d51"
            }
          ]
        },
        {
          "id": "232a9cd1-7557-4a97-a38b-7724a6b51c4f",
          "name": "importKeyMaterial",
          "request": {
            "url": "http://example.com/api/?Action=ImportKeyMaterial?EncryptedKeyMaterial=EncryptedKeyMaterial&ExpirationModel=ExpirationModel&ImportToken=ImportToken&KeyId=KeyId&ValidTo=ValidTo",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Imports key material into an AWS KMS customer master key (CMK) from your existing key\n      management infrastructure."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "19887629-953c-41ff-a19a-d5d2bd48fd45"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "27df3e2f-eb07-4f48-bf25-ea0925e28c23",
          "name": "createAlias",
          "request": {
            "url": "http://example.com/api/?Action=CreateAlias?AliasName=AliasName&TargetKeyId=TargetKeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a display name for a customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d76d6087-e359-4a13-b1db-91cfd40b95ac"
            }
          ]
        },
        {
          "id": "995d0435-9523-4d0c-b294-061030f849e7",
          "name": "deleteAlias",
          "request": {
            "url": "http://example.com/api/?Action=DeleteAlias?AliasName=AliasName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified alias."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1196bcad-352b-4ea6-bbe7-766043a3eaa8"
            }
          ]
        },
        {
          "id": "fb2d91a6-961c-4a41-9acd-3f84864b1745",
          "name": "listAliases",
          "request": {
            "url": "http://example.com/api/?Action=ListAliases?Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists all of the key aliases in the account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6e887d0-db42-4fee-8ac3-2b652db64dbc"
            }
          ]
        }
      ]
    },
    {
      "name": "Grants",
      "item": [
        {
          "id": "8cbb08e4-ad81-43f0-9608-37dd783fa83a",
          "name": "createGrant",
          "request": {
            "url": "http://example.com/api/?Action=CreateGrant?Constraints=Constraints&GranteePrincipal=GranteePrincipal&GrantTokens=GrantTokens&KeyId=KeyId&Name=Name&Operations=Operations&RetiringPrincipal=RetiringPrincipal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Adds a grant to a key to specify who can use the key and under what conditions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "db32099d-9ced-4c8a-8573-a60ab8f5b38f"
            }
          ]
        },
        {
          "id": "c58dfa7d-fc43-4322-9270-60f15385d1e8",
          "name": "listGrants",
          "request": {
            "url": "http://example.com/api/?Action=ListGrants?KeyId=KeyId&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List the grants for a specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "877b3838-f1f4-4799-9d59-411fb22397a6"
            }
          ]
        }
      ]
    },
    {
      "name": "Decrypt",
      "item": [
        {
          "id": "5c932353-11c5-4ed4-8fcc-991720766046",
          "name": "decrypt",
          "request": {
            "url": "http://example.com/api/?Action=Decrypt?CiphertextBlob=CiphertextBlob&EncryptionContext=EncryptionContext&GrantTokens=GrantTokens",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Decrypts ciphertext."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "335c9bb6-276c-4164-b263-41abe592349d"
            }
          ]
        }
      ]
    },
    {
      "name": "Encrypt",
      "item": [
        {
          "id": "0fb33c4a-3160-47b1-9d13-608a1a1c946f",
          "name": "encrypt",
          "request": {
            "url": "http://example.com/api/?Action=Encrypt?EncryptionContext=EncryptionContext&GrantTokens=GrantTokens&KeyId=KeyId&Plaintext=Plaintext",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Encrypts plaintext into ciphertext by using a customer master key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ace942f8-a860-4759-831f-b5b250f4fe0b"
            }
          ]
        }
      ]
    },
    {
      "name": "Randoms",
      "item": [
        {
          "id": "117488cb-a008-4624-8dda-0980bb3c3c09",
          "name": "generateRandom",
          "request": {
            "url": "http://example.com/api/?Action=GenerateRandom?NumberOfBytes=NumberOfBytes",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Generates an unpredictable byte string."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3730759c-2a3d-4581-8817-dd257cf2e05b"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Policies",
      "item": [
        {
          "id": "c5577401-ffd9-449f-a8f5-3fc5577c02e5",
          "name": "getKeyPolicy",
          "request": {
            "url": "http://example.com/api/?Action=GetKeyPolicy?KeyId=KeyId&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a policy attached to the specified key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3f7273b5-643e-4aa3-ae96-4efbc7f038a7"
            }
          ]
        }
      ]
    },
    {
      "name": "Parameters",
      "item": [
        {
          "id": "bb2585b5-5cd7-4ddc-8f50-3d770c95e36f",
          "name": "getParametersForImport",
          "request": {
            "url": "http://example.com/api/?Action=GetParametersForImport?KeyId=KeyId&WrappingAlgorithm=WrappingAlgorithm&WrappingKeySpec=WrappingKeySpec",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the items you need in order to import key material into AWS KMS from your\n      existing key management infrastructure."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f948c6d2-7a56-4393-8c36-7ac4061a2f23"
            }
          ]
        }
      ]
    }
  ]
}