# groundhog backend

Crowdsourced search

## requests:

### Get comments for a query and result
`GET /comments?query={query}&resultURL={url}`

### Create a new comment
POST `/comments?query={query}&resultURL={url}`

JSON:

```
{
  comment: 'foo',
  author: '',
  authToken: 'wlkfjlwkejfkwjfl' // user's authentication token
}
```