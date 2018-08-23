FORMAT: 1A

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

# Group Player APIs
    
## 新規登録 [/player/info]

### /player/info [GET]

+ Response 200 (text/plain)

        Hello World!

## ログイン [/player/login]

### /player/login [GET]

+ Response 200 (text/plain)

        Hello World!

# Group Chara APIs
    
## 新規登録 [/chara/info]

### /chara/info [GET]

+ Response 200 (text/plain)

        Hello World!

## ログイン [/chara/list]

### /chara/list [GET]

+ Response 200 (text/plain)

        Hello World!!





## Data Structures
### SysInfo
+ api_status_code: 1 (number)
+ is_maintenance: false (boolean)