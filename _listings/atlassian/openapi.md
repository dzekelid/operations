swagger: "2.0"
x-collection-name: Atlassian
x-complete: 1
info:
  title: Stride API
  description: this-service-provides-public-api-for-the-stride-
  version: 1.0.0
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /content/{id}/restriction/byOperation:
    get:
      summary: Get restrictions by operation
      description: "Returns restrictions on a piece of content by operation. This
        method is \nsimilar to [Get restrictions](#api-content-id-restriction-get)
        except that \nthe operations are properties of the return object, rather than
        items in \na results array. \n\n**[Permissions](https://confluence.atlassian.com/x/_AozKw)
        required**: \nPermission to view the content."
      operationId: com.atlassian.confluence.plugins.restapi.resources.ContentRestrictionResource.getRestrictionsByOpera
      x-api-path-slug: contentidrestrictionbyoperation-get
      parameters:
      - in: query
        name: expand
        description: A multi-value parameter indicating which properties of the content
          restrictions to expand
      - in: path
        name: id
        description: The ID of the content to be queried for its restrictions
      responses:
        200:
          description: OK
      tags:
      - Restrictions
      - By
      - Operation