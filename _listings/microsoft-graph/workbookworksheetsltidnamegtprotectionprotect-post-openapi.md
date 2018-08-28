---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Worksheet Protection Protect
  description: 'WorksheetProtection: protect Protect a worksheet. It throws if the
    worksheet has been protected.'
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workbook/names(&lt;name&gt;)/range/format/protection:
    get:
      summary: Get Format Protection
      description: Get FormatProtection Retrieve the properties and relationships
        of formatprotection object.
      operationId: GetFormatProtection
      x-api-path-slug: workbooknamesltnamegtrangeformatprotection-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Format
      - Protection
  /workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/protection:
    get:
      summary: Get Format Protection
      description: Get FormatProtection Retrieve the properties and relationships
        of formatprotection object.
      operationId: GetFormatProtection
      x-api-path-slug: workbookworksheetsltidnamegtrangeltaddressgtformatprotection-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Format
      - Protection
  /workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/protection:
    get:
      summary: Get Format Protection
      description: Get FormatProtection Retrieve the properties and relationships
        of formatprotection object.
      operationId: GetFormatProtection
      x-api-path-slug: workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Format
      - Protection
  /workbook/worksheets(&lt;id|name&gt;)/protection:
    get:
      summary: Get Worksheet Protection
      description: Get WorksheetProtection Retrieve the properties and relationships
        of worksheetprotection object.
      operationId: GetWorksheetProtection
      x-api-path-slug: workbookworksheetsltidnamegtprotection-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Worksheet
      - Protection
  /workbook/worksheets(&lt;id|name&gt;)/protection/protect:
    post:
      summary: Worksheet Protection Protect
      description: 'WorksheetProtection: protect Protect a worksheet. It throws if
        the worksheet has been protected.'
      operationId: WorksheetProtection:Protect
      x-api-path-slug: workbookworksheetsltidnamegtprotectionprotect-post
      parameters:
      - in: header
        name: Authorization
        description: Bearer
      responses:
        200:
          description: OK
      tags:
      - Worksheet
      - Protection
      - Protect
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---