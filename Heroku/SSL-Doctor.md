## [SSL Doctor](https://github.com/heroku/heroku-ssl-doctor)

### Prerequisites

* A Heroku application and the [SSL Endpoint](https://devcenter.heroku.com/articles/ssl-endpoint) addon.
* [SSL Certificates](https://dnsimple.com/ssl-certificate)

### Just The Tip

```bash
heroku certs:add *.{pem,crt,key} -a <application>
```
