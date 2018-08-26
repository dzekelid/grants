{
  "info": {
    "name": "AWS Key Management Service API Retire Grant",
    "_postman_id": "8519d2dc-20f9-4d39-8f8e-24e357d13a1b",
    "description": "Retires a grant.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Keys",
      "item": [
        {
          "id": "3354e4c2-ea35-4768-8ad6-11e98d2b1005",
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
              "id": "28c232a1-a70a-47d1-b332-24a589347729"
            }
          ]
        },
        {
          "id": "2e0b755f-175c-4726-8754-4b36660b5c89",
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
              "id": "5f912f04-130f-43f1-b9a4-4de6e16b131b"
            }
          ]
        },
        {
          "id": "54dcfd6c-c575-40fc-ae38-0a45f06cff71",
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
              "id": "43d31df2-3f18-4c32-9807-6b3e87234609"
            }
          ]
        },
        {
          "id": "51c958cb-09f9-4257-a4c5-04023eeabb3f",
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
              "id": "1d3f72af-6103-4d85-b580-5be28b0c9121"
            }
          ]
        },
        {
          "id": "7b0b7c32-2d5d-456e-a62b-3ac226733eab",
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
              "id": "9abf06df-b06d-49c7-98ce-a5fa34143257"
            }
          ]
        },
        {
          "id": "7447040b-3df2-43ed-9d78-30f9f8d43a91",
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
              "id": "1b1d6422-2bc5-4110-b012-acf9513e98b3"
            }
          ]
        },
        {
          "id": "7ea75413-d813-45f9-980c-b5d9eb0113e5",
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
              "id": "36d0e905-f5de-40f8-b696-0487fc834fca"
            }
          ]
        },
        {
          "id": "958ab7aa-9cfe-4b15-957f-27283b2219d9",
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
              "id": "bbf16586-7d09-4711-9723-4307fa64fa7f"
            }
          ]
        },
        {
          "id": "535da720-81e6-4882-bdfb-6c447a321035",
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
              "id": "73ccb427-505e-4951-8409-077b4a07a804"
            }
          ]
        },
        {
          "id": "099907f8-60be-47cf-a9b9-8308030ce8be",
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
              "id": "54e5d489-3741-4abd-9852-75bb70450ee1"
            }
          ]
        },
        {
          "id": "c5127563-75d9-4c8a-b4b8-0089469d73a2",
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
              "id": "0969f628-4347-4ea0-8906-0aed57bfb6ea"
            }
          ]
        },
        {
          "id": "1e5e12bb-3fe2-442d-b930-1e41f3cf97b4",
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
              "id": "c707e96a-17ec-414d-b4e0-3b11d9e750c4"
            }
          ]
        },
        {
          "id": "ebc8f4a4-0c14-4008-a3cd-90e4a34a8adc",
          "name": "listKeys",
          "request": {
            "url": "http://example.com/api/?Action=ListKeys?Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the customer master keys."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e643d9aa-214d-4b5f-9662-689d2b734295"
            }
          ]
        },
        {
          "id": "8925fd7a-ad2f-43d3-aad1-250360ff5cf8",
          "name": "putKeyPolicy",
          "request": {
            "url": "http://example.com/api/?Action=PutKeyPolicy?BypassPolicyLockoutSafetyCheck=BypassPolicyLockoutSafetyCheck&KeyId=KeyId&Policy=Policy&PolicyName=PolicyName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Attaches a key policy to the specified customer master key (CMK)."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e79abed1-4899-4b4b-b09a-6c3154f2dd6b"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "d39c7aa3-3f4e-4314-86c7-a9447a2f1e39",
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
              "id": "00284c3c-80d7-4cfd-aaba-6836fc6bffe7"
            }
          ]
        },
        {
          "id": "6de6d483-6ecf-4970-8a8d-60891535be72",
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
              "id": "7b384eb5-64fb-4b02-84c4-a2e701ea3cd5"
            }
          ]
        },
        {
          "id": "dcf2a422-c7fa-4651-91ec-ec12bf878817",
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
              "id": "21b8a4c4-699d-45a8-8da3-f4972b2db862"
            }
          ]
        }
      ]
    },
    {
      "name": "Grants",
      "item": [
        {
          "id": "41b79259-7124-4f61-980d-1447ef861280",
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
              "id": "e882d109-37f3-4c29-8db2-b6c4410dfbb7"
            }
          ]
        },
        {
          "id": "746f27fb-bb55-438d-aeab-eb79337074c8",
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
              "id": "acc0960f-a74a-4066-ac60-a3bad621028d"
            }
          ]
        },
        {
          "id": "ebc0b169-f7af-4ea8-adba-689b0be81285",
          "name": "listRetirableGrants",
          "request": {
            "url": "http://example.com/api/?Action=ListRetirableGrants?Limit=Limit&Marker=Marker&RetiringPrincipal=RetiringPrincipal",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of all grants for which the grant's RetiringPrincipal\n      matches the one specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d0f996f-0d11-4bb1-813d-a035a374887f"
            }
          ]
        },
        {
          "id": "31f6c865-2640-45f6-9fd3-5e10ffcbc4bf",
          "name": "retireGrant",
          "request": {
            "url": "http://example.com/api/?Action=RetireGrant?GrantId=GrantId&GrantToken=GrantToken&KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retires a grant."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a374cae3-3cbd-4c0d-9d8a-6f57f2ac5fcb"
            }
          ]
        }
      ]
    },
    {
      "name": "Decrypt",
      "item": [
        {
          "id": "91cd964c-4131-4bf8-8fb2-6c8b56817127",
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
              "id": "55f25230-bdb0-44a4-9410-353b570c32d7"
            }
          ]
        }
      ]
    },
    {
      "name": "Encrypt",
      "item": [
        {
          "id": "a415ae45-fcff-4139-9385-2d3dce3a0075",
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
              "id": "1f81c61b-a1bf-4d71-9dae-b80bd3f7e370"
            }
          ]
        },
        {
          "id": "738c62d4-fbc3-4ad7-bb6f-1e0d641d0dec",
          "name": "reEncrypt",
          "request": {
            "url": "http://example.com/api/?Action=ReEncrypt?CiphertextBlob=CiphertextBlob&DestinationEncryptionContext=DestinationEncryptionContext&DestinationKeyId=DestinationKeyId&GrantTokens=GrantTokens&SourceEncryptionContext=SourceEncryptionContext",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Encrypts data on the server side with a new customer master key (CMK) without exposing\n      the plaintext of the data on the client side."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "78620a52-4558-4990-ae1b-4ea65d4c0015"
            }
          ]
        }
      ]
    },
    {
      "name": "Randoms",
      "item": [
        {
          "id": "19ebaef6-f6bf-4fa3-aa56-c4698b58674d",
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
              "id": "c165fb35-fb7f-4fe1-b2b4-4023294906f7"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Policies",
      "item": [
        {
          "id": "971f21b9-52d0-4ac2-a030-c81de0b0d951",
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
              "id": "26af7e11-7e72-432a-85a5-db9c358a4f06"
            }
          ]
        }
      ]
    },
    {
      "name": "Parameters",
      "item": [
        {
          "id": "e4f0256a-0222-4ef5-8072-dd88c7a2e402",
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
              "id": "f61c55e7-14e9-407a-ba07-9790ed8c2bf7"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "6c3544c7-44bf-4cf2-a378-1ded3832296e",
          "name": "listKeyPolicies",
          "request": {
            "url": "http://example.com/api/?Action=ListKeyPolicies?KeyId=KeyId&Limit=Limit&Marker=Marker",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a list of policies attached to a key."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9e76733e-6bfc-44cc-b41b-1ed77fda7ee6"
            }
          ]
        }
      ]
    }
  ]
}