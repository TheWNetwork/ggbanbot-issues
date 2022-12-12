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
> | ok  | boolean | Status | Yes  | 
> | data.ban | boolean  | Is the user banned |
