# ccl-testpkg
Package to test CColon's package manager

*Public Domain*

To try:

```
ccolon pkg install https://github.com/TRC-Loop/ccl-testpkg
```

then create a `.ccl` file, eg. `test.ccl`, and put this in it:

```
function main() {
  test()
}
```

It calls function test from `ccl-testpkg`-package, which prints:

```
If you see this, it works!
```

CColon: https://github.com/TRC-Loop/ccolon

Package Manager Docs: https://ccolon.arne.sh/tools/packages/
