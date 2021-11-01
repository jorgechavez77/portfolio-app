## Build

```shell
hugo -D
```

## Deployment

```shell
aws s3 cp public s3://etaipe-blog/ --recursive --acl public-read
```
