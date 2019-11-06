# strcase
[![Godoc Reference](https://godoc.org/github.com/floydspace/strcase?status.svg)](http://godoc.org/github.com/floydspace/strcase)
[![Build Status](https://travis-ci.org/floydspace/strcase.svg)](https://travis-ci.org/floydspace/strcase)
[![Coverage](http://gocover.io/_badge/github.com/floydspace/strcase?0)](http://gocover.io/github.com/floydspace/strcase)
[![Go Report Card](https://goreportcard.com/badge/github.com/floydspace/strcase)](https://goreportcard.com/report/github.com/floydspace/strcase)

strcase is a go package for converting string case to various cases (e.g. [snake case](https://en.wikipedia.org/wiki/Snake_case) or [camel case](https://en.wikipedia.org/wiki/CamelCase)) to see the full conversion table below.

## Example

```go
s := "AnyKind of_string"
```

| Function                          | Result               |
|-----------------------------------|----------------------|
| `ToSnake(s)`                      | `any_kind_of_string` |
| `ToScreamingSnake(s)`             | `ANY_KIND_OF_STRING` |
| `ToKebab(s)`                      | `any-kind-of-string` |
| `ToScreamingKebab(s)`             | `ANY-KIND-OF-STRING` |
| `ToDelimited(s, '.')`             | `any.kind.of.string` |
| `ToScreamingDelimited(s, '.')`    | `ANY.KIND.OF.STRING` |
| `ToCamel(s)`                      | `AnyKindOfString`    |
| `ToLowerCamel(s)`                 | `anyKindOfString`    |


## Install

```bash
go get -u github.com/floydspace/strcase
```
