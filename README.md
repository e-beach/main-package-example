# Example of importing a main package
`cd test && go test` should work, but fails with this message:

\# github.com/e-beach/main-package-example/test
main_test.go:4:2: import "github.com/e-beach/main-package-example" is a program, not an importable package
FAIL	github.com/e-beach/main-package-example/test [setup failed]
