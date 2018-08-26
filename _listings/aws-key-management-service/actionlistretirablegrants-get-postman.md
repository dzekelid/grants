{
  "info": {
    "name": "AWS Key Management Service API List Retirable Grants",
    "_postman_id": "543a40cb-04da-4a14-92da-a616248ed7ba",
    "description": "Returns a list of all grants for which the grant's RetiringPrincipal\n      matches the one specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Keys",
      "item": [
        {
          "id": "690fbe11-4518-4958-b8ff-a7358c3c1b5c",
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
              "id": "0e5d1bc3-41d5-4f28-ba6a-9870d1590426"
            }
          ]
        },
        {
          "id": "2b97ee0c-5bb3-433b-9f96-9b5e610d6363",
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
              "id": "79da6232-8143-4c77-80b9-e63ad62c916f"
            }
          ]
        },
        {
          "id": "a3c426c4-895e-4a9c-9d01-59d9873ac972",
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
              "id": "020c0510-c07f-4d9b-9f77-6a4f03a048ba"
            }
          ]
        },
        {
          "id": "de148bfb-4b47-4feb-b93b-3dd0a5385c6b",
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
              "id": "7f0bb451-6e23-4320-822a-cbafcd2d3994"
            }
          ]
        },
        {
          "id": "13e67361-ff85-4d2b-b212-f90b60859695",
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
              "id": "122d0c49-3ac7-4baf-905f-4198bd568d02"
            }
          ]
        },
        {
          "id": "079b3dce-f3bf-4ee3-b0df-a072b28b22e9",
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
              "id": "b90eb28a-1a05-4e65-94fc-e4c913475f9b"
            }
          ]
        },
        {
          "id": "183e8e60-cb70-4fd4-83dc-9d20f85607ec",
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
              "id": "665c4873-71c0-4c21-8129-d04db8253533"
            }
          ]
        },
        {
          "id": "b70b0f5f-2652-4314-b2c4-e2bbcea95fcf",
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
              "id": "629f41dc-ccaa-447f-a451-52aa8f986c4a"
            }
          ]
        },
        {
          "id": "cbc59595-dc25-4d52-8764-788612bbec98",
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
              "id": "d1b82df1-1cc8-4d43-bcc0-b2e902bd95fd"
            }
          ]
        },
        {
          "id": "9641344f-1ae1-4b9e-af1c-0dd3f218f5ee",
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
              "id": "78be43f9-8711-47d7-8574-d28858c7f711"
            }
          ]
        },
        {
          "id": "91f35fd2-e45d-404a-9097-d706d99ee1da",
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
              "id": "ce347cc7-e62f-4023-b95b-37fcfd290d22"
            }
          ]
        },
        {
          "id": "d555d1f8-db91-4cbb-87ce-8a3e4a967c30",
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
              "id": "5a211abc-64e7-480a-892c-004152ada03d"
            }
          ]
        },
        {
          "id": "bf9b4181-51c0-4238-96b7-933c5ae475d5",
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
              "id": "85df1f35-0994-449a-b3cb-541f42ab2f41"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "c2708239-0785-4b66-a0c4-a24710f3777e",
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
              "id": "d9799406-042e-4d6a-98f9-918296f8752d"
            }
          ]
        },
        {
          "id": "ec57783a-d454-4efb-85f9-45b8ae0b228a",
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
              "id": "610250dd-e3bf-44e4-aaf4-281c34e7da13"
            }
          ]
        },
        {
          "id": "1a7bdc5a-9d3f-42e8-9845-6bf148b81878",
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
              "id": "fcd199be-f503-4046-9636-738ec0257b01"
            }
          ]
        }
      ]
    },
    {
      "name": "Grants",
      "item": [
        {
          "id": "04f7a614-06b4-4c18-878a-76eb92c2355a",
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
              "id": "78507cd0-7ac6-4ef1-b6ac-daf4a75be2ec"
            }
          ]
        },
        {
          "id": "201a29f4-e94f-4193-9fa3-fd92bd61dc29",
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
              "id": "371bdea1-2aca-44be-8a7d-7c82c9e5acf9"
            }
          ]
        },
        {
          "id": "87bd0ccb-3e87-486e-80be-f03f66929131",
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
              "id": "3c3b745f-1a18-4743-81a8-929bc4fec5e3"
            }
          ]
        }
      ]
    },
    {
      "name": "Decrypt",
      "item": [
        {
          "id": "56923305-8e48-4d15-9bb5-bfa1014acc96",
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
              "id": "d39b860b-b40d-4da2-bba1-82be286ff540"
            }
          ]
        }
      ]
    },
    {
      "name": "Encrypt",
      "item": [
        {
          "id": "e566952d-8815-481b-ae9c-0e498e055387",
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
              "id": "dd3eed01-91a7-4249-ba69-eb3b5060ed6b"
            }
          ]
        }
      ]
    },
    {
      "name": "Randoms",
      "item": [
        {
          "id": "8fbc782b-8d28-4939-811f-81fb4231b060",
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
              "id": "d4978d49-2fc9-45a7-b288-6f2fbb4f6bd1"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Policies",
      "item": [
        {
          "id": "ec33c302-4e0f-4d49-a736-6125b5dbabcf",
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
              "id": "c6ae33e9-00fe-4586-a2e1-f800106cc908"
            }
          ]
        }
      ]
    },
    {
      "name": "Parameters",
      "item": [
        {
          "id": "21564cf0-6be6-4480-8e30-f789eed6d2b8",
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
              "id": "e0256947-7509-4850-b8c1-89dbbf287468"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "d5d85fd1-f163-4d65-9728-23b9c782d1dc",
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
              "id": "3bed9470-6273-4a3c-94e7-4cbdff2ab4b1"
            }
          ]
        }
      ]
    }
  ]
}