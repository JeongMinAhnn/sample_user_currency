
# Currency API
```

```
|Method|기능|URL|상태코드|
|------|---|---|------|
|`POST`|환전 요청 수행|/api/schedules|201: 정상 등록, 400: 비정상 값|
|`GET`|환전 요청 조회|/api/schedules|200: 정상 조회, 404: 비정상 조회|
|`PATCH`|환전 요청 상태 변경|/api/schedules/{schedule_id}|200: 정상 조회, 404: 비정상조회, 400: 비정상 값|
|`DELETE`|고객삭제|/api/schedules/{schedule_id}|200: 정상 수정, 404: 비정상조회|

