# WARNING: this library uses an unofficial api and is against cleverbot.com TOS, use the official cleverbot api instead https://www.cleverbot.com/api/

# cleverbot-go [![Build Status](https://travis-ci.org/ugjka/cleverbot-go.svg?branch=master)](https://travis-ci.org/ugjka/cleverbot-go)
Cleverbot wrapper written in Go https://godoc.org/github.com/ugjka/cleverbot-go

## Example

```go
session, _ := cleverbot.New()
answer, _ := session.Ask("How are you?")
```
