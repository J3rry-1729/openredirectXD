## Thanks to the main author noobexploiter for making tool.
# openredirectXD
Tool to find open redirects in get parameters. It take inputs from stdin. It simply change all parameters to http://evil.com and check if the response is a redirect and if the location header is pointing to http://evil.com

# How to install 
```go get github.com/J3rry-1729/openredirectXD```

# How to use
```cat vulnweb_all_urls.txt | openredirectXD -t 5```
### You can specify the payload too
```cat vulnweb_all_urls.txt | openredirectXD -t 5 -p 'http://anywhere.com'```
