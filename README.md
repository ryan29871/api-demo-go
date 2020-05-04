### Configure and launch app

Install dependencies:

```bash
$ cd src
$ go get
```

Running the app:

```bash
$ cd src
$ go rum main.go
```

Run unit tests:

```bash
# unit tests
$ cd src
$ go test ./...

# bench tests - cd into directory of benchmark test
$ cd src
$ cd user
$ npm run test:e2e

# test coverage
$ cd src
$ go test ./... -cover
```

Test endpoints:

```
http://localhost:11111
http://localhost:11111/users
```