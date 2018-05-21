---
swagger: "2.0"
x-collection-name: Azure DocumentDB
x-complete: 1
info:
  title: DocumentDB
  description: azure-documentdb-database-service-resource-provider-rest-api
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts/{accountName}:
    get:
      summary: Database Accounts Get
      description: Retrieves the properties of an existing Azure DocumentDB database
        account.
      operationId: DatabaseAccounts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountname-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
    patch:
      summary: Database Accounts Patch
      description: Patches the properties of an existing Azure DocumentDB database
        account.
      operationId: DatabaseAccounts_Patch
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountname-patch
      parameters:
      - in: query
        name: No Name
      - in: body
        name: updateParameters
        description: The tags parameter to patch for the current database account
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - Patch
    put:
      summary: Database Accounts Create Or Update
      description: Creates or updates an Azure DocumentDB database account.
      operationId: DatabaseAccounts_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountname-put
      parameters:
      - in: body
        name: createUpdateParameters
        description: The parameters to provide for the current database account
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - Or
    delete:
      summary: Database Accounts Delete
      description: Deletes an existing Azure DocumentDB database account.
      operationId: DatabaseAccounts_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountname-delete
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts/{accountName}/failoverPriorityChange
  : post:
      summary: Database Accounts Failover Priority Change
      description: Changes the failover priority for the Azure DocumentDB database
        account. A failover priority of 0 indicates a write region. The maximum value
        for a failover priority = (total number of regions - 1). Failover priority
        values must be unique for each of the regions in which the database account
        exists.
      operationId: DatabaseAccounts_FailoverPriorityChange
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountnamefailoverprioritychange-post
      parameters:
      - in: body
        name: failoverParameters
        description: The new failover policies for the database account
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - Failover
      - Priority
      - Change
  /subscriptions/{subscriptionId}/providers/Microsoft.DocumentDB/databaseAccounts:
    get:
      summary: Database Accounts List
      description: Lists all the Azure DocumentDB database accounts available under
        the subscription.
      operationId: DatabaseAccounts_List
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftdocumentdbdatabaseaccounts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - List
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts:
    get:
      summary: Database Accounts List By Resource Group
      description: Lists all the Azure DocumentDB database accounts available under
        the given resource group.
      operationId: DatabaseAccounts_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccounts-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - ListResource
      - Group
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts/{accountName}/listKeys
  : post:
      summary: Database Accounts List Keys
      description: Lists the access keys for the specified Azure DocumentDB database
        account.
      operationId: DatabaseAccounts_ListKeys
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountnamelistkeys-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - List
      - Keys
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts/{accountName}/listConnectionStrings
  : post:
      summary: Database Accounts List Connection Strings
      description: Lists the connection strings for the specified Azure DocumentDB
        database account.
      operationId: DatabaseAccounts_ListConnectionStrings
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountnamelistconnectionstrings-post
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - List
      - Connection
      - Strings
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts/{accountName}/readonlykeys
  : get:
      summary: Database Accounts List Read Only Keys
      description: Lists the read-only access keys for the specified Azure DocumentDB
        database account.
      operationId: DatabaseAccounts_ListReadOnlyKeys
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountnamereadonlykeys-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - List
      - Read
      - Only
      - Keys
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DocumentDB/databaseAccounts/{accountName}/regenerateKey
  : post:
      summary: Database Accounts Regenerate Key
      description: Regenerates an access key for the specified Azure DocumentDB database
        account.
      operationId: DatabaseAccounts_RegenerateKey
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdocumentdbdatabaseaccountsaccountnameregeneratekey-post
      parameters:
      - in: body
        name: keyToRegenerate
        description: The name of the key to regenerate
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - Regenerate
      - Key
  /providers/Microsoft.DocumentDB/databaseAccountNames/{accountName}:
    head:
      summary: Database Accounts Check Name Exists
      description: Checks that the Azure DocumentDB account name already exists. A
        valid account name may contain only lowercase letters, numbers, and the '-'
        character, and must be between 3 and 50 characters.
      operationId: DatabaseAccounts_CheckNameExists
      x-api-path-slug: providersmicrosoftdocumentdbdatabaseaccountnamesaccountname-head
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Database
      - Accounts
      - Checks
      - Name
      - Exists
---