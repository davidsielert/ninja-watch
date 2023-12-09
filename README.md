# Ninja watch
Original work by [Niklas](https://github.com/NickeZ) Forked from https://github.com/NickeZ/ninja-watch in order to fix bug in the regex

Ninja watch is a helper script that uses inotify on linux to listen for changed
and created files that would trigger a rebuild by ninja.

It passes through any argument to the real ninja build.

## Example usage

```
ninja-watch -C build
```


### @todo
- [] More documentation
- [] pypy Package
