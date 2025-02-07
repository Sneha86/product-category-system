# product-category-system
INTRODUCTION:
Build a system that syncs product data from external sources and provides query capabilities. Create a endpoint which calls fakestore API to fetch data and store it in a local database. Then expose data from the local database through APIs.

PATTERN:
External Data Fetcher - Fetching product data from the FakeStore API
Local Database - Storing fetched product data
Data Syncing Mechanism - Automatically syncing data from the external source
REST API -Exposing stored product data through a REST API

SOLUTION DESIGN:
Create RAML Specification for Product Synchronization and Product Query
Develop the Mule applications in Any Point Studio and expose the API’s
Error Handling
MUnit Testing
