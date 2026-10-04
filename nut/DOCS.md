# Network UPS Tools TLS

Custom Home Assistant app catalog entry for the NUT TLS fork.

## TLS options

```yaml
tls: true
tls_certfile: /ssl/fullchain.pem
tls_keyfile: /ssl/privkey.pem
```

The `ssl` directory is mounted read-only. If TLS is enabled and the configured certificate or key cannot be read, the app stops instead of starting without TLS.
