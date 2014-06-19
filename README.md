# go-shellwords

[![Coverage Status](https://coveralls.io/repos/mattn/go-shellwords/badge.png?branch=master)](https://coveralls.io/r/mattn/go-shellwords?branch=master)
[![Build Status](https://travis-ci.org/mattn/go-shellwords.svg?branch=master)](https://travis-ci.org/mattn/go-shellwords)

Parse line as shell words.

## Usage

```
args, err := shellwords.Parse("./foo --bar=baz")
// args should be ["./foo", "--bar=baz"]
```

# License

under the MIT License: http://mattn.mit-license.org/2014

# Author

Yasuhiro Matsumoto (a.k.a mattn)
