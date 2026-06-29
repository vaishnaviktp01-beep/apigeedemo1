# README for the apiproxy bundle

This directory contains a minimal Apigee API proxy bundle used by the GitHub Actions workflow.

- proxies/default.xml: ProxyEndpoint
- targets/default.xml: TargetEndpoint

BasePath: /hello
Target backend: https://postman-echo.com/get
