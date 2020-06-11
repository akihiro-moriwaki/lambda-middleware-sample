# lambda-middleware-sample

middleware組み込みサンプル

## Setup process

### Installing dependencies & building the target

```shell
make
```

### Local development

**Invoking function locally through local API Gateway**

```bash
sam local start-api
```

## Packaging and deployment

```bash
sam deploy --guided
```

### Testing

```shell
go test -v ./...
```
# Appendix

### Golang installation

Please ensure Go 1.x
