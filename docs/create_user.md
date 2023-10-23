# 1. JSON Example
**URL** : https://fitcrea.com/api-v2/users/ - POST


|Parameter| Required/Optional | Description|
|----|------------|---------
|first_name| Requried | String |
|last_name| Requried | String |
|email| Requried  | String, Email |
|courses| Requried | Array |

Request :
```javascript
{
    "first_name":"Janez",
    "last_name":"Novak",
    "email" : "janez.novak@gmail.com",
    "courses" : [1]
}
```


Respond : 
```javascript
{
    "opr_code":"0",
    "opr_time_ms":"33",
    "mk_id":"1600001744",
    "count_code":"eshop_002"
}
```