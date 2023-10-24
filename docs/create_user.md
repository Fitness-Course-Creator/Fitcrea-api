# Create user

**URL** : https://fitcrea.com/api-v2/users/ - POST


|Parameter| Required/Optional | Description|
|----|------------|---------
|first_name| Required | String |
|last_name| Required | String |
|email| Required  | String, Email |
|courses| Required | Array |

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
    "data": {
        "id": 17,
        "first_name": "Janez",
        "last_name": "Novak",
        "email": "janez.novak@gmail.com",
        "deleted_at": null,
        "created_at": "2023-08-09T09:40:55.000000Z",
        "updated_at": "2023-08-09T09:41:26.000000Z",
        "active": 1,
        "courses": [
            {
                "id": 1,
                "name": "test1",
                "sku": "234234",
                "mailchimp_tag_name": "test1",
                "description": "<p>This is the course description</p>",
                "price": 0,
                "full_price": 0,
                "drip_content_type": null,
                "status": "published",
                "status_title": "Published",
                "program_type": "follow_along",
                "program_type_title": "Follow Along",
                "use_simple_layout": true,
                "feedback_type": "workout_completed",
                "feedback_type_title": "Lesson Completed",
                "duration": null,
                "duration_days": 0,
                "duration_unit": "week",
                "frequencies": [],
                "difficulty": null,
                "difficulty_title": "",
                "image": "/images/video.jpg",
                "deleted": null,
                "started_at": null,
                "created_at": "2023-07-16T15:21:28.000000Z",
                "updated_at": "2023-08-04T16:30:07.000000Z",
                "account_id": 1,
                "user_id": 1
            }
        ],
        "account_id": 1
    }
}
```
