---
layout: default
---

# API
> - URL: https://api.elsa.yuuu.es/v1/[group]/[endpoint]
> - Format: JSON

## User

### Query

Endpoint: https://api.elsa.yuuu.es/v1/user/query

> Parameters:
> 
> | Parameter | Type | Description | Required |
> | --- | --- | --- | --- |
> | id  | numeric | Your telegram ID          | Yes  | 
> | api | string  | Private Key given by Elsa | Yes  |
> | telegram_id | numeric | User to query | Yes |

> Return data:
>
> | Parameter | Type | Description | 
> | --- | --- | --- |
> | ok  | boolean | Status |
> | data.ban | boolean  | Is the user banned |
> | data.ban_reason | string  | Reason why the user is banned* |
> 
> Sometimes we have some private data and the reason will be "Restricted reason"


## Report
> **Only available to special users**

### Query

Endpoint: https://api.elsa.yuuu.es/v1/report/query

> Parameters:
> 
> | Parameter | Type | Description | Required |
> | --- | --- | --- | --- |
> | id  | numeric | Your telegram ID          | Yes  | 
> | api | string  | Private Key given by Elsa | Yes  |
> | report_id | numeric | Report to query | Yes |

> Return data:
>
> | Parameter | Type | Description | View Level |
> | --- | --- | --- | --- |
> | ok  | boolean | Status | all |
> | data.origin_id | numeric | User who report | 2 |
> | data.reported_id | numeric | User the report is | 1 |
> | data.status | string | Current Status of the report | 1 |
> | data.date | string | Date of the report | 1 |
> | date.comment | array | | 1 |
> | date.comment[].number | number | Position | 1 |
> | date.comment[].date | date | Date | 1 |
> | date.comment[].user | number | Message Sender | 3 |
> | date.comment[].message | string | Message | 1 |

### New

Endpoint: https://api.elsa.yuuu.es/v1/report/new

> Parameters:
> 
> | Parameter | Type | Description | Required |
> | --- | --- | --- | --- |
> | id  | numeric | Your telegram ID          | Yes  | 
> | api | string  | Private Key given by Elsa | Yes  |
> | telegram_id | numeric | User to query | Yes |
> | reason | string | Reason to Ban | Yes |
> | author_id | numeric | If your service identify the user who creates the report, send it here | No |
> | proof[] | array | Array of proofs, list of PNG/JPG Base64 Encoded Images* | No |

* Limits may apply

> Return data:
>
> | Parameter | Type | Description | 
> | --- | --- | --- |
> | ok  | boolean | Status | 
> | data.report_id | numeric  | Number of the report to query |
