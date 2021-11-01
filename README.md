# Portfolio App

## Build

```shell
hugo -D
```

## Local Deploy

```shell
aws s3 cp public s3://etaipe-blog/ --recursive --acl public-read
```

## URL
http://etaipe-blog.s3-website-us-east-1.amazonaws.com/
