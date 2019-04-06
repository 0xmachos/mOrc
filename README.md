# mOrc
mOrc is a post-exploitation framework for macOS written in Bash

Based on and inspired by [zMarch/Orc](https://github.com/zMarch/Orc) a "post-exploitation framework for Linux written in Bash".

## Script Start

It takes the form of an ENV script, so load mOrc into a shell by running

```
ENV=mo.rc sh -i 
```

HISTFILE is unset, and we use ulimit -c 0 to try and prevent any corefiles showing up.
