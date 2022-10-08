---
author: Shashank Srivastava
title: REST To Do - Create a REST API Using PHP & MySQL
date: 2018-05-14
---
## Introduction:  
Writing this code helped me create another API to perform the integration of a Service Desk tool with XL Release. Below is what the `GET` request looks like.

```bash
{
    https://localhost/~admin/REST-TO-DO/info?task=Write Code
}
```

The response returned is.

```
{
    "status": 1,
    "info": [
        {
            "Task": "Write Code",
            "Date": "18/06/2019",
            "Priority": "1"
        }
    ]
}
```

---
Detailed Medium article: https://shashanksrivastava.medium.com/create-a-rest-api-using-php-mysql-60ba1ad918d2
