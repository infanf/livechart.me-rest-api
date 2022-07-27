# Refresh Token

#### METHOD: POST
> The HTTP POST method sends data to the server. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/POST)

___

#### ENDPOINT:
` https://www.livechart.me/api/v1/auth/refresh `

___

#### HEADERS:

```http
accept-encoding: gzip
connection: Keep-Alive
content-type: application/x-www-form-urlencoded
host: www.livechart.me
user-agent: me.livechart.android/6.4.8
```

___

#### REQUEST BODY:

| refresh_token | {refresh_token} |
|---|---|
| old_access_token | {old_access_token} |
