# heroku-oauth2-proxy-buildpack

Adds Oauth2 support to heroku deployed applications.

## Usage

Append  '{ "url": "https://github.com/denzuko/heroku-oauth2-proxy-buildpack"}' to  
`buildpack[]` in ones `app.json` file.


## Configuration

https://oauth2-proxy.github.io/oauth2-proxy/docs/configuration/oauth_provider/

Using Environment variables one can configure the provider, secret, id, and cookie. Do note
the cookie has should be no longer than a 32 char hash.
