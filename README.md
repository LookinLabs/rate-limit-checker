# Rate Limit Checker

Rate limit checker written in Go. It's a simple tool to check the rate limit of a website. It sends a request to the website and checks the response code. If the response code is 429, it means the website has a rate limit. It can be used to check the rate limit of any website.

![preview](https://repository-images.githubusercontent.com/262951377/b248f480-936f-11ea-8cb7-ccd94da1fb2e)

## Install

## From Source

1. Clone this repository

`git clone https://github.com/lookinlabs/rate-limit-checker`

2. Use the raw file or build it

`&& cd rate-limit-checker && go build rate.go`

## Native

`go get github.com/lookinlabs/rate-limit-checker`

## Usage

```

Usage of rate:
  --method, -X string
      HTTP Method to use for the request (default "GET")
  --threads, -t int
      Number of threads to use (default 10)
  --requests-count -c int
      Number of requests to send (default 500)
  --ignore-code-change, -i
      Continue after the rate limiter code was changed
  --url, -u string
      URL to check
  --output, -o string
      Output file to save the results
```
