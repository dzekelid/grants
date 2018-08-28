{
  "info": {
    "name": "AWS Key Management Service API Revoke Grant",
    "_postman_id": "57d33a72-8827-4652-8670-20f553bf105f",
    "description": "Revokes a grant.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Keys",
      "item": [
        {
          "id": "bdb38a32-0a69-42e1-9325-bf08b793c315",
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
              "id": "edbd6648-6b95-4b3e-a375-fdde6b5f2182"
            }
          ]
        },
        {
          "id": "d0c6d705-a887-4f65-b02e-f6568a1aac50",
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
              "id": "acc697d6-5cc5-45be-b6ba-e1b2c0427750"
            }
          ]
        },
        {
          "id": "2a65686b-e62e-470f-a3b1-33c87d37f7bb",
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
              "id": "7ae04718-fc3a-4d1b-bf47-334a3e2fd89d"
            }
          ]
        },
        {
          "id": "b2989e13-d877-464b-8756-365490c1d40f",
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
              "id": "01bf5b75-a8d2-4812-a6b9-eadd3fae869c"
            }
          ]
        },
        {
          "id": "adbe8c09-eb4a-496c-93a6-c758792aa74c",
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
              "id": "b27e0144-5d95-495c-b9ec-cf897bba40de"
            }
          ]
        },
        {
          "id": "db07b2d6-9a58-4392-be45-6097b41c70c8",
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
              "id": "e129531a-42e9-4719-9ffa-8b51700a42be"
            }
          ]
        },
        {
          "id": "b689fd1f-fc17-4598-849d-75922ffb7d3f",
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
              "id": "2db9dbf8-e6cf-433e-aae4-bfba12c43bfc"
            }
          ]
        },
        {
          "id": "b4a08bf4-8173-4c62-bcfb-a245fd929145",
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
              "id": "8f8b542d-e688-4659-9fec-0a39af62f6d1"
            }
          ]
        },
        {
          "id": "09743561-e3c3-43a6-a5ce-115f3382e116",
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
              "id": "fea156be-0df6-4e8b-8a09-6b17a5af2dd6"
            }
          ]
        },
        {
          "id": "c872dd8c-be3b-416d-900c-8b41eb047d33",
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
              "id": "0663046e-4de3-40a4-b1cd-be91c50ffbc4"
            }
          ]
        },
        {
          "id": "02d448ee-1871-4c5f-a7ba-f4cdeff99ef6",
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
              "id": "9c84a35f-8ceb-4e94-bd7e-f0a96d9783b9"
            }
          ]
        },
        {
          "id": "5da746cc-8922-4029-b10c-78ff70c0741f",
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
              "id": "615b4f73-1667-4b5c-9ed8-973abb278766"
            }
          ]
        },
        {
          "id": "17a11e2b-76bf-4b9a-abd1-68559bbbcc48",
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
              "id": "d73bfc67-4bcd-4bd2-8160-9f890438be38"
            }
          ]
        },
        {
          "id": "072ef5e4-ee98-4a1b-8fa2-c8c989f33538",
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
              "id": "98bc4388-0e3f-42d0-978c-5da2ce1e6b79"
            }
          ]
        }
      ]
    },
    {
      "name": "Aliases",
      "item": [
        {
          "id": "5455923c-b0b2-47ba-a41d-0321de59ff78",
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
              "id": "2e57b159-756a-45e5-b9d8-6861664c5b05"
            }
          ]
        },
        {
          "id": "928d3a90-7c60-4634-b7cf-82f13999d2ee",
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
              "id": "ea8ad1cf-7dae-4516-b815-2c856bc8cd99"
            }
          ]
        },
        {
          "id": "ff8e7a29-9f1f-4a97-9774-7821bfee78a7",
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
              "id": "3f5e78a9-755b-40de-a0fa-d9b9e749f607"
            }
          ]
        }
      ]
    },
    {
      "name": "Grants",
      "item": [
        {
          "id": "164695be-55ef-4dc7-a84f-1e386b083fcf",
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
              "id": "58dc02e1-b745-4cae-970b-3102edd85d48"
            }
          ]
        },
        {
          "id": "67f172bb-fa40-4d73-95db-06e15d9a1634",
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
              "id": "428a5057-f21e-4b4d-9dbf-56f569888952"
            }
          ]
        },
        {
          "id": "b5a5886f-509d-4720-8f88-2e822e9ee9cd",
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
              "id": "c59ee1f6-c59d-46f5-89fe-c750c8aa334d"
            }
          ]
        },
        {
          "id": "0a39599e-1e90-4ad1-a805-9c83da28f347",
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
              "id": "c36f1f2a-6d9c-4588-a543-3b07bfc368ac"
            }
          ]
        },
        {
          "id": "13e50696-314d-4d58-9012-02ba6d0cfdbd",
          "name": "revokeGrant",
          "request": {
            "url": "http://example.com/api/?Action=RevokeGrant?GrantId=GrantId&KeyId=KeyId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Revokes a grant."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26803e9d-bca9-4ad2-bfa9-872fb639b9b9"
            }
          ]
        }
      ]
    },
    {
      "name": "Decrypt",
      "item": [
        {
          "id": "525aae5c-b7a0-466b-8374-e13400c3e8de",
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
              "id": "9b9a12cc-0f52-4207-9f0b-613b65aa0720"
            }
          ]
        }
      ]
    },
    {
      "name": "Encrypt",
      "item": [
        {
          "id": "31b54b4b-0a3e-4703-bc5f-0b4b2a337c26",
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
              "id": "85c7ddba-36c3-426b-af41-bf41efd27fb9"
            }
          ]
        },
        {
          "id": "acc5b67a-e858-489a-8031-0c55ece343e2",
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
              "id": "db1b55ff-1fbe-4459-a5af-50712e2cb773"
            }
          ]
        }
      ]
    },
    {
      "name": "Randoms",
      "item": [
        {
          "id": "a8d7cc7a-5f46-40e2-bff6-0ac332a5ac96",
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
              "id": "6f0c7e05-3991-47db-9e48-1b964eb492a8"
            }
          ]
        }
      ]
    },
    {
      "name": "Key Policies",
      "item": [
        {
          "id": "e33dbf6d-147c-4eec-b75a-19dcd1e9b918",
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
              "id": "3da15057-b27f-47c6-ad19-8e295b9e1ebe"
            }
          ]
        }
      ]
    },
    {
      "name": "Parameters",
      "item": [
        {
          "id": "a9a757fa-8487-40c2-abea-5a93feef8476",
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
              "id": "cfb13b9e-1da1-4591-8bb9-8a9942d08286"
            }
          ]
        }
      ]
    },
    {
      "name": "Policies",
      "item": [
        {
          "id": "2c05258e-9593-4d81-84cf-1517c891389f",
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
              "id": "a0a917d8-1962-42a8-bf11-ee74f0d5ad70"
            }
          ]
        }
      ]
    }
  ]
}