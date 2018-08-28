swagger: "2.0"
x-collection-name: Lufthansa
x-complete: 1
info:
  title: LH Public
  version: "1.0"
host: api.lufthansa.com
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /operations/flightstatus/arrivals/{airportCode}/{fromDateTime}:
    get:
      summary: Flight Status at Arrival Airport
      description: Status of all arrivals at a given airport up to 4 hours from the
        provided date time.
      operationId: OperationsFlightstatusArrivalsByAirportCodeAndFromDateTimeGet
      x-api-path-slug: operationsflightstatusarrivalsairportcodefromdatetime-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: airportCode
        description: 3-letter IATA aiport code (e
      - in: path
        name: fromDateTime
        description: Start of time range in local time of arrival airport (YYYY-MM-DDTHH:mm)
      - in: query
        name: limit
        description: Number of records returned per request
      - in: query
        name: offset
        description: Number of records skipped
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Flightstatus
      - Arrivals
      - AirportCode
      - FromDateTime
  /operations/flightstatus/departures/{airportCode}/{fromDateTime}:
    get:
      summary: Flight Status at Departure Airport
      description: Status of all departures from a given airport up to 4 hours from
        the provided date time.
      operationId: OperationsFlightstatusDeparturesByAirportCodeAndFromDateTimeGet
      x-api-path-slug: operationsflightstatusdeparturesairportcodefromdatetime-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: airportCode
        description: Departure airport
      - in: path
        name: fromDateTime
        description: Start of time range in local time of departure airport (YYYY-MM-DDTHH:mm)
      - in: query
        name: limit
        description: Number of records returned per request
      - in: query
        name: offset
        description: Number of records skipped
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Flightstatus
      - Departures
      - AirportCode
      - FromDateTime
  /operations/flightstatus/route/{origin}/{destination}/{date}:
    get:
      summary: Flight Status by Route
      description: Status of flights between a given origin and destination on a given
        date.
      operationId: OperationsFlightstatusRouteDateByOriginAndDestinationGet
      x-api-path-slug: operationsflightstatusrouteorigindestinationdate-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: date
        description: Departure date (YYYY-MM-DD) in local time of departure airport
      - in: path
        name: destination
        description: 3-letter IATA airport code (e
      - in: query
        name: limit
        description: Number of records returned per request
      - in: query
        name: offset
        description: Number of records skipped
      - in: path
        name: origin
        description: 3-letter IATA airport (e
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Flightstatus
      - Route
      - Origin
      - Destination
      - Date
  /operations/flightstatus/{flightNumber}/{date}:
    get:
      summary: Flight Status
      description: Status of a particular flight (boarding, delayed, etc.).
      operationId: OperationsFlightstatusByFlightNumberAndDateGet
      x-api-path-slug: operationsflightstatusflightnumberdate-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: date
        description: The departure date (YYYY-MM-DD) in the local time of the departure
          airport
      - in: path
        name: flightNumber
        description: Flight number including carrier code and any suffix (e
      - in: query
        name: limit
        description: Number of records returned per request
      - in: query
        name: offset
        description: Number of records skipped
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Flightstatus
      - FlightNumber
      - Date
  /operations/schedules/{origin}/{destination}/{fromDateTime}:
    get:
      summary: Flight Schedules
      description: Scheduled flights between given airports on a given date.
      operationId: OperationsSchedulesFromDateTimeByOriginAndDestinationGet
      x-api-path-slug: operationsschedulesorigindestinationfromdatetime-get
      parameters:
      - in: header
        name: Accept
        description: 'http header: application/json or application/xml (Acceptable
          values are: application/json, application/xml)'
      - in: path
        name: destination
        description: Destination airport
      - in: query
        name: directFlights
        description: Show only direct flights (false=0, true=1)
      - in: path
        name: fromDateTime
        description: Local departure date and optionally departure time (YYYY-MM-DD
          or YYYY-MM-DDTHH:mm)
      - in: query
        name: limit
        description: Number of records returned per request
      - in: query
        name: offset
        description: Number of records skipped
      - in: path
        name: origin
        description: Departure airport
      responses:
        200:
          description: OK
      tags:
      - Operations
      - Schedules
      - Origin
      - Destination
      - FromDateTime