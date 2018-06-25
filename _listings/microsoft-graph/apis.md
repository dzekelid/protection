---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Protection
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Get Format Protection
  x-api-slug: microsoft-graph
  description: Get FormatProtection Retrieve the properties and relationships of formatprotection
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/protection
  tags: Format, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-get-openapi.md
- name: Microsoft Graph Get Format Protection
  x-api-slug: microsoft-graph
  description: Get FormatProtection Retrieve the properties and relationships of formatprotection
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/protection
  tags: Format, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-get-openapi.md
- name: Microsoft Graph Get Format Protection
  x-api-slug: microsoft-graph
  description: Get FormatProtection Retrieve the properties and relationships of formatprotection
    object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/protection
  tags: Format, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-get-openapi.md
- name: Microsoft Graph Update Formatprotection
  x-api-slug: microsoft-graph
  description: Update formatprotection Update the properties of formatprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/names(&lt;name&gt;)/range/format/protection
  tags: Formatprotection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooknamesltnamegtrangeformatprotection-patch-openapi.md
- name: Microsoft Graph Update Formatprotection
  x-api-slug: microsoft-graph
  description: Update formatprotection Update the properties of formatprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/range(&lt;address&gt;)/format/protection
  tags: Formatprotection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtrangeltaddressgtformatprotection-patch-openapi.md
- name: Microsoft Graph Update Formatprotection
  x-api-slug: microsoft-graph
  description: Update formatprotection Update the properties of formatprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/tables(&lt;id|name&gt;)/columns(&lt;id|name&gt;)/range/format/protection
  tags: Formatprotection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbooktablesltidnamegtcolumnsltidnamegtrangeformatprotection-patch-openapi.md
- name: Microsoft Graph Get Worksheet Protection
  x-api-slug: microsoft-graph
  description: Get WorksheetProtection Retrieve the properties and relationships of
    worksheetprotection object.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/protection
  tags: Worksheet, Protection
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotection-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotection-get-openapi.md
- name: Microsoft Graph Worksheet Protection Protect
  x-api-slug: microsoft-graph
  description: 'WorksheetProtection: protect Protect a worksheet. It throws if the
    worksheet has been protected.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/protection/protect
  tags: Worksheet, Protection, Protect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionprotect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionprotect-post-openapi.md
- name: Microsoft Graph Worksheet Protection Unprotect
  x-api-slug: microsoft-graph
  description: 'WorksheetProtection: unprotect Unprotect a worksheet'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////workbook/worksheets(&lt;id|name&gt;)/protection/unprotect
  tags: Worksheet, Protection, Unprotect
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionunprotect-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/workbookworksheetsltidnamegtprotectionunprotect-post-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Protection
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/protection/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---