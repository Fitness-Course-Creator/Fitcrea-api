# MANAGING USER COURSES

|Parameter| Required/Optional | Description|
|----|------------|---------
|courses| Requried | Array |


## 1 Adding course to user

**URL** : https://fitcrea.com/api-v2/users/1/courses - POST

Request :

```javascript
{
    "courses" : [1]
}
```

Respond :

```javascript
{
   "message" : "Course has been successfully assigned."
}

```

## 2 Adding course to user

**URL** : https://fitcrea.com/api-v2/users/1/courses - DELETE

Request :

```javascript
{
    "courses" : [1]
}
```

Respond :

```javascript
{
   "message" : "Course has been successfully deassigned."
}

```
