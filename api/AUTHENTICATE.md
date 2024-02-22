# Authenticate

#### METHOD: POST
> The HTTP POST method sends data to the server. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/POST)

___

#### ENDPOINT:
` https://www.livechart.me/api/v1/auth/authenticate `

___

#### REQUIRED ARGUMENTS:
| email    | test@livechart.me |
| -------- | ----------------- |
| password | test              |

___

#### HEADERS:
```http
accept-encoding: gzip
connection: Keep-Alive
content-type: application/x-www-form-urlencoded
host: www.livechart.me
user-agent: me.livechart.android/6.4.8
```
> This endpoint accepts both content-type json or urlencoded

___

## Short note:
Once connected, and you have retrieved the access_token, it is possible to pass it in the header for EVERY request, this will not cause any problems for the API, even for requests where connection is not required

___

### Valid auth headers
```http
x-auth-token: {access_token}
authorization: {access_token}
authorization: {token_type} {access_token}
```