Note. This is a fork of Lurker which looks to be abandoned and has not accepted pull requests in a year. It adds support for Symfony 4.0, which is required by newer packages (i.e. robo). How to use:

```
{
    "repositories": [
        {
            "name": "henrikbjorn/lurker",
            "type": "vcs",
            "url": "https://github.com/lesichkovm/lurker"
        }
    ],
    "require": {
        "henrikbjorn/lurker": ">=1.3",
        "consolidation/robo": "^1.4"
    }
}
```

Lurker
======

Resource tracking for PHP. Watch files and/or directories. For more information
[look at the documentation here](http://lurker.rtfd.org).

[![Build Status](https://travis-ci.org/flint/Lurker.png?branch=master)](https://travis-ci.org/flint/Lurker)

