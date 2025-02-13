# axolgo-lib, the Axolotl Library in Golang
[![CodeQL](https://github.com/tchiunam/axolgo-lib/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/tchiunam/axolgo-lib/actions/workflows/codeql-analysis.yml)
[![Go](https://github.com/tchiunam/axolgo-lib/actions/workflows/go.yml/badge.svg)](https://github.com/tchiunam/axolgo-lib/actions/workflows/go.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftchiunam%2Faxolgo-lib.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Ftchiunam%2Faxolgo-lib?ref=badge_shield)

This is the library of the Axolotl series in Golang. It serves as the base of other axol libraries.

Go package: https://pkg.go.dev/github.com/tchiunam/axolgo-lib

## Use it with your Go module
To add as dependency for your package or upgrade to the latest version:
```
go get github.com/tchiunam/axolgo-lib
```

To upgrade or downgrade to a specific version:
```
go get github.com/tchiunam/axolgo-lib@v1.2.3
```

To remove dependency on your module and downgrade modules:
```
go get github.com/tchiunam/axolgo-lib@none
```

See 'go help get' or https://golang.org/ref/mod#go-get for details.

## Run test
To run test:
```
go test ./...
```

To run test with coverage result:
```
go test -coverpkg=./... ./...
```

---
#### See more  
1. [axolgo-aws](https://github.com/tchiunam/axolgo-aws) for using AWS SDK
1. [axolgo-gcp](https://github.com/tchiunam/axolgo-gcp) for using GCP API
2. [axolgo-cli](https://github.com/tchiunam/axolgo-cli) for using Axolgo in command line


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Ftchiunam%2Faxolgo-lib.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Ftchiunam%2Faxolgo-lib?ref=badge_large)