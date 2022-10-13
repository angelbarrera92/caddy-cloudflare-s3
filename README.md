# caddy-cloudflare-s3

A [Caddy](https://caddyserver.com/) container image that uses Cloudflare as a DNS provider and S3 as a storage backend.

## Build

```bash
$ docker build -t caddy-cloudflare-s3:local .
```

## Published images

The image is built and published every day at 00:00 UTC.

- [ghcr.io/angelbarrera92/caddy-cloudflare-s3:latest](https://github.com/angelbarrera92/caddy-cloudflare-s3/pkgs/container/caddy-cloudflare-s3)

```bash
$ docker pull ghcr.io/angelbarrera92/caddy-cloudflare-s3:latest
```

## License

[Apache License 2.0](LICENSE)
