# ESEP Grade Calculator

This library is a simple utility to calculate student's final grades, they're calculated based on three assignment categories: assignments, exams, and essays. Each category is averaged separately, then weighted, then combined and converted into a final letter grade (A-F).

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade-calculator/
go test -coverprofile=coverage.txt ./...
```