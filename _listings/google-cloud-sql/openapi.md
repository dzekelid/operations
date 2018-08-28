swagger: "2.0"
x-collection-name: Google Cloud SQL
x-complete: 1
info:
  title: Cloud SQL Administration
  description: creates-and-configures-cloud-sql-instances-which-provide-fullymanaged-mysql-databases-
  contact:
    name: Google
    url: https://google.com
  version: v1beta4
host: www.googleapis.com
basePath: /sql/v1beta4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{project}/operations:
    get:
      summary: Get Projects Project Operations
      description: Lists all instance operations that have been performed on the given
        Cloud SQL instance in the reverse chronological order of the start time.
      operationId: sql.operations.list
      x-api-path-slug: projectsprojectoperations-get
      parameters:
      - in: query
        name: instance
        description: Cloud SQL instance ID
      - in: query
        name: maxResults
        description: Maximum number of operations per response
      - in: query
        name: pageToken
        description: A previously-returned page token representing part of the larger
          set of results to view
      - in: path
        name: project
        description: Project ID of the project that contains the instance
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Project
      - Operations
  /projects/{project}/operations/{operation}:
    get:
      summary: Get Projects Project Operations Operation
      description: Retrieves an instance operation that has been performed on an instance.
      operationId: sql.operations.get
      x-api-path-slug: projectsprojectoperationsoperation-get
      parameters:
      - in: path
        name: operation
        description: Instance operation ID
      - in: path
        name: project
        description: Project ID of the project that contains the instance
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Project
      - Operations
      - Operation