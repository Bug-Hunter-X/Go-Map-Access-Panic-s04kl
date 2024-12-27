# Go Map Access Panic

This repository demonstrates a common error in Go: accessing a map without first checking if it's nil. Attempting to access a nil map will result in a runtime panic.

The `bug.go` file shows the problematic code. The `bugSolution.go` file provides a corrected version.

This is a concise example highlighting a frequently encountered issue in Go development.  Always ensure your maps are initialized before accessing their elements.