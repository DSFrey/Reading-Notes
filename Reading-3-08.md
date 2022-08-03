# APIs

## API Design Best Practices

1. Representational State Transfer

2. APIs are designed around resources.

3. An identifier is anything that uniquely identifies a resource, e.g. a URL.

4. GET, POST, PUT, PATCH, DELETE

5. URIs should be based on the resource and not the operations on the resource.

6. >https://adventure-works.com/orders // Good
    >
    >https://adventure-works.com/create-order // Avoid

7. A chatty API requires multiple small requests to retrieve all the necessary data. Making one big request is better, as it reduces the load on the web server.

8. Successful GET returns 200 (OK)

9. Unsuccessful GET returns 404 (Not Found)

10. Successful POST returns 201 (Created)

11. Successful DELETE returns 204 (No Content)
