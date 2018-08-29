---
name: Azure DocumentDB
x-slug: azure-documentdb
description: Azure DocumentDB is a fully-managed NoSQL document database service that
  offers querying and transaction-processing over schema-free data, predictable and
  reliable performance, and rapid development.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure DocumentDB
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/apis.md
specificationVersion: "0.14"
apis:
- name: DocumentDB - Database Accounts Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-get
  description: Retrieves the properties of an existing Azure DocumentDB database account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-get-openapi.md
- name: DocumentDB - Database Accounts Patch
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-patch
  description: Patches the properties of an existing Azure DocumentDB database account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-patch-openapi.md
- name: DocumentDB - Database Accounts Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-put
  description: Creates or updates an Azure DocumentDB database account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-put-openapi.md
- name: DocumentDB - Database Accounts Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-delete
  description: Deletes an existing Azure DocumentDB database account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountname-delete-openapi.md
- name: DocumentDB - Database Accounts Failover Priority Change
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamefailoverprioritychange-post
  description: Changes the failover priority for the Azure DocumentDB database account.
    A failover priority of 0 indicates a write region. The maximum value for a failover
    priority = (total number of regions - 1). Failover priority values must be unique
    for each of the regions in which the database account exists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamefailoverprioritychange-post-openapi.md
- name: DocumentDB - Database Accounts List
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-documentdbdatabaseaccounts-get
  description: Lists all the Azure DocumentDB database accounts available under the
    subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidprovidersmicrosoft-documentdbdatabaseaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidprovidersmicrosoft-documentdbdatabaseaccounts-get-openapi.md
- name: DocumentDB - Database Accounts List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccounts-get
  description: Lists all the Azure DocumentDB database accounts available under the
    given resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccounts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccounts-get-openapi.md
- name: DocumentDB - Database Accounts List Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamelistkeys-post
  description: Lists the access keys for the specified Azure DocumentDB database account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamelistkeys-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamelistkeys-post-openapi.md
- name: DocumentDB - Database Accounts List Connection Strings
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamelistconnectionstrings-post
  description: Lists the connection strings for the specified Azure DocumentDB database
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamelistconnectionstrings-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamelistconnectionstrings-post-openapi.md
- name: DocumentDB - Database Accounts List Read Only Keys
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamereadonlykeys-get
  description: Lists the read-only access keys for the specified Azure DocumentDB
    database account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamereadonlykeys-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnamereadonlykeys-get-openapi.md
- name: DocumentDB - Database Accounts Regenerate Key
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnameregeneratekey-post
  description: Regenerates an access key for the specified Azure DocumentDB database
    account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-documentdbdatabaseaccountsaccountnameregeneratekey-post-openapi.md
- name: DocumentDB - Database Accounts Check Name Exists
  x-api-slug: providersmicrosoft-documentdbdatabaseaccountnamesaccountname-head
  description: Checks that the Azure DocumentDB account name already exists. A valid
    account name may contain only lowercase letters, numbers, and the '-' character,
    and must be between 3 and 50 characters.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-document-db-03-replicate.png
  humanURL: https://azure.microsoft.com/en-us/services/documentdb/
  baseURL: ://management.azure.com//
  tags: Microsoft, Documents, Stack Network, API Service Provider, API Provider, Databases,
    Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/providersmicrosoft-documentdbdatabaseaccountnamesaccountname-head-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-documentdb/master/_listings/azure-documentdb/providersmicrosoft-documentdbdatabaseaccountnamesaccountname-head-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.dns.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.documentdb.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/documentdb/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/documentdb/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/documentdb/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/documentdb/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---