# Mail Server

```sh
openssl req -newkey rsa:4096 -x509 -sha256 -days 365 -nodes -out .data/etc/dovecot/cert.pem -keyout .data/etc/dovecot/key.pem
```

<https://github.com/dovecot/core/tree/main/doc/example-config>
