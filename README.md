# golang_effective_notes
# https://golang.org/doc/effective_go.html
# https://golang.org/doc/code.html

## Naming conventions

Public vs Private:

Go doesn't have the concept of Public and Private but if you name with a capital ,it will be
"public" from other packages perspective.

type IamPublic struct {}

type IamPrivate struct {}
