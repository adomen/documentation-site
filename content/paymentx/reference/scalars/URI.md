{
  "title": "URI",
  "description": "",
  "weight": 1,
  "fields": null,
  "requireby": [
    {
      "name": "Urls",
      "description": "Url's",
      "url": "/paymentx/reference/objects/urls"
    }
  ],
  "enumValues": null,
  "operator": "scalar",
  "typename": "URI",
  "hideGithubLink": true
}
The URI type represents a URI values. A good example mith be an Hotel Image URL.
In queries or mutations, URI fields have to be specified in RFC 3986, RFC 3987, and RFC 6570 (level 4) compliant URI string format with enclosing double quotes: "http:\\www.travelgatex.com".
## GraphQL schema definition

{{% graphql-schema-scalar %}}

## Required by

{{% graphql-require-by %}}
