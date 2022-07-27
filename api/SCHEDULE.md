# Schedule

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://www.livechart.me/api/v1/schedule `

___

#### POTENTIAL ARGUMENTS:
```http
start_date: {exemple: 2022-07-26},
end_date: {exemple: 2022-07-27},
offset: 0,
sort: title | airdate | popularity | modified | countdown | anime.avg_rating,
titles: romaji | english,
hide_skipping: true | false
```

___

#### HEADERS:

```http
accept-encoding: gzip
connection: Keep-Alive
host: www.livechart.me
user-agent: me.livechart.android/6.4.8
