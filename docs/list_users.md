# Listing users

**URL** : https://fitcrea.com/api-v2/users


Response :

```javascript
{
  "data": [
        {
            "id": 9,
            "first_name": "Mirko",
            "last_name": "Cerar",
            "email": "mirko.cerar@gmail.com",
            "deleted_at": null,
            "created_at": "2023-08-04T14:07:48.000000Z",
            "updated_at": "2023-08-04T14:07:48.000000Z",
            "active": 0,
            "courses": [
                {
                    "id": 11,
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
        },
        {
            "id": 10,
            "first_name": "TEST",
            "last_name": "Test",
        .
        .
        .
        }
    ]
}
```