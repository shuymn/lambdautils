# lambdautils

lambdautils is a Go package that provides a function called `IsLambda` to determine if the execution environment is AWS Lambda.

## Usage

```golang
package main

import "github.com/shuymn/lambdautils"

func main() {
    if lambdautils.IsLambda() {
        // do something on AWS Lambda
    } else {
        // do something on the other execution environment
    }
}
```

## TODO

- [x] Implement
- [ ] Write unit tests