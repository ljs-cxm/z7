## z7 [![GoDoc](https://godoc.org/pkg.re/essentialkaos/z7.v4?status.svg)](https://godoc.org/pkg.re/essentialkaos/z7.v4) [![Go Report Card](https://goreportcard.com/badge/essentialkaos/z7)](https://goreportcard.com/report/essentialkaos/z7) [![License](https://gh.kaos.io/ekol.svg)](https://essentialkaos.com/ekol)

`z7` package provides methods for working with 7z archives (`p7zip` wrapper).

### Installation

Before the initial install allows git to use redirects for [pkg.re](https://github.com/essentialkaos/pkgre) service (reason why you should do this described [here](https://github.com/essentialkaos/pkgre#git-support)):

```
git config --global http.https://pkg.re.followRedirects true
```

Make sure you have a working Go 1.5+ workspace ([instructions](https://golang.org/doc/install)), then:

```
go get pkg.re/essentialkaos/z7.v4
```

### Compatibility

|      Version |      1.x |    2.x+ |
|--------------|----------|---------|
|  `p7zip 9.x` |    Full  | Partial |
| `p7zip 15.x` |  Partial |    Full |

### License

[EKOL](https://essentialkaos.com/ekol)
