## Generate Self Signed Certificate

```
openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout ssl/nginx-selfsigned.key -out ssl/selfsigned.crt
```

### [Open GitHub Pages](https://abusalam.github.io/orange-kite/)