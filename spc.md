# JSON Data struc

---

- [**memder**](#member)

- **member_card**

## member

```json
    {
        "uid": firebase_login,
        "level":{
            "type": level_list,
            //type sales
            "card_id": string,
            "uid_chief": string,
            //type chief sales
            "card_id":string,
        },
        "profile":{
            "type":string,
            "name":string,
            "img": url_img,
            "contact":{
                "type": contact_list,
                "details" string
            },
        },
        "package":{
            "business":{
                "count" int,
                "expire" time,
            },
            "name":{
                "count" int,
                "expire" time,
            },
        },
        "friend":{
            "code": string,
            "invited": string,
            "point" int,

        },
        "time_create":time,
        "time_update":time,
    }
```

## member_card

```json
    {
        "":{},
    }
```
