# Migration Example

This is a test repo.

### Install:

With Docker:

```sh
docker run --name migration-postgres -p 5432:5432 -e POSTGRES_USER=admin -e POSTGRES_DB=migration -e POSTGRES_PASSWORD=password -d postgres:11.2
```

### Run:

```sh
go run main.go
```