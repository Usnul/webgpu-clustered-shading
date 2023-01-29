

see https://github.com/FiloSottile/mkcert

see https://www.npmjs.com/package/http-server

```bash
brew install mkcert
mkcert -install
# cd to code directory
mkcert localhost
webpack-dev-server --cert ./localhost.pem --key ./localhost-key.pem
```
