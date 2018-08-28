swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 1
info:
  title: Microsoft Graph API
  description: microsoft-graph-exposes-multiple-apis-from-office-365-and-other-microsoft-cloud-services-through-a-single-endpoint-httpsgraph-microsoft-com--microsoft-graph-simplifies-queries-that-would-otherwise-be-more-complex-
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
  /workbook/worksheets(&lt;id|name&gt;)/protection/unprotect:
    post:
      summary: Worksheet Protection Unprotect
      description: 'WorksheetProtection: unprotect Unprotect a worksheet'
      operationId: WorksheetProtection:Unprotect
      x-api-path-slug: workbookworksheetsltidnamegtprotectionunprotect-post
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
      - Unprotect