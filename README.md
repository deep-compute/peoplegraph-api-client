# peoplegraph-api-client [![Build Status][travis-ci-status-img]][travis-ci-peoplegraph-api-client]

API client for deep-compute's peoplegraph product http://www.deepcompute.com/peoplegraph/

# Installation

```
pip install peoplegraph-api-client
```

# Usage

Grab your api secret key from http://www.deepcompute.com/peoplegraph/settings

```bash
peoplegraph -H "http://www.deepcompute.com" -u "<username>" -s "<api-secret-key>" -n "John Doe" --wait
```

If you have a webserver that accepts POST requests, you can give peoplegraph a callback, to which it will
POST the result.

```bash
peoplegraph -H "http://www.deepcompute.com" -u "<username>" -s "<api-secret-key>" -n "John Doe" --callback "http://www.myserver.com"
```

[travis-ci-status-img]: https://travis-ci.org/deep-compute/peoplegraph-api-client.svg?branch=master
[travis-ci-peoplegraph-api-client]: https://travis-ci.org/deep-compute/peoplegraph-api-client
