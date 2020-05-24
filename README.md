# go-freegeoip
Unofficial lib for https://freegeoip.app. Thank you for the awesome api

[![Build Status](https://travis-ci.com/Z-M-Huang/go-freegeoip.svg?branch=master)](https://travis-ci.com/Z-M-Huang/go-freegeoip)

# Example usage
```
  import "github.com/Z-M-Huang/go-freegeoip"

  resp, err := freegeoip.Get(host)
  if err != nil {
    panic(err)
  }
  fmt.Println(resp.IP)
```