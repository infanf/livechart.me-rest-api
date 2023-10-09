# Nearest

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://www.livechart.me/api/v1/charts/nearest `

___

#### POTENTIAL ARGUMENTS:
```http
fields[]: previous_chart | next_chart (both can be used in same time),
season: winter | spring | summer | fall
```

___

#### HEADERS:
```http
accept-encoding: gzip
connection: Keep-Alive
host: www.livechart.me
user-agent: me.livechart.android/6.4.8
```

___

## It is also possible to get all kinds of season slugs

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://www.livechart.me/api/v1/charts `

___

#### POTENTIAL ARGUMENTS:
```http
offset: 0,
limit: 0
```

___

#### HEADERS:
```http
accept-encoding: gzip
connection: Keep-Alive
host: www.livechart.me
user-agent: me.livechart.android/6.4.8
```