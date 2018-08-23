# Group Auth APIs

## 新規登録 [/auth/create]

### /auth/create [GET]

+ Response 200 (application/json)

    + Attributes

        + sysinfo (SysInfo)
        + auth_result:
            + hash_token
            + pass

## セッション取得 [/auth/session]

### /auth/session [GET]

+ Response 200 (application/json)

    + Attributes

        + sysinfo (SysInfo)
