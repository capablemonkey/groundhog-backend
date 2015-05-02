# groundhog backend

Crowdsourced search

it's up on https://ghog.herokuapp.com/

## getting started

1. clone repo
2. `npm install`
3. `node bin/www`

## API reference

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
