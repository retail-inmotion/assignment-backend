# Development assignment back-end developer

Create a .NET Core (version 2.1 or higher) RESTful API with the following exposed actions:
* Create and persist a new product with the following mandatory fields:
    * Id (Guid)
    * Name (string)
    * Description (string)
* Update an existing product
* Delete an existing product
* Get an existing product by its identifier
* Get a paged list of products (query parameters are page and page size) where the response contains the following information:
    * the total count of persisted products
    * the products on the requested page

Some additional requirements on the created service:
* The created solution has to build without errors with the command "dotnet build"
* The service has to be production ready, so make sure its correctness is verified

Some additonal notes:
* Feel free to use whatever persistence layer and database you want 
* Feel free to use whatever code editor you want

