# Season Chart

#### METHOD: GET
> The HTTP GET method requests a representation of the specified resource. [Find out more](https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/GET)

___

#### ENDPOINT:
` https://www.livechart.me/api/v1/charts/{nearest-slug}/full_instances `

___

#### POTENTIAL ARGUMENTS:
```http
fields[]: next_episode,
category: tv | movies | ovas | all,
offset: 0,
limit: 0,
sort: title | airdate | popularity | modified | countdown | anime.avg_rating,
titles: romaji | english,
leftovers: true | false,
hide_skipping: true | false
```

___

#### HEADERS:
```http
accept-encoding: gzip
connection: Keep-Alive
host: www.livechart.me
user-agent: me.livechart.android/6.4.8
```