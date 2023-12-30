# powerschool-reporter-go

Tooling to generate a report card from the power school data export. Implemented in Golang.
This is a successor to [powerschool-reporter](https://github.com/sberczuk/powerschool-reporter) which is in Python


# Notes

Data types were generated with [go-xmlstruct](https://github.com/twpayne/go-xmlstruct) using
this command:

```shell
cat myData.xml| go  run github.com/twpayne/go-xmlstruct/cmd/goxmlstruct@latest >types.go
```