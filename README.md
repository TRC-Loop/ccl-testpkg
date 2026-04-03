# ccl-testpkg

Test package for the CColon package manager

Licensed under the Unlicense
Public domain

## Requirements

> [!IMPORTANT]
> Requires at least CColon version 1.0.0

## Install

```
ccolon pkg install https://github.com/TRC-Loop/ccl-testpkg
```

## Usage

Create a `.ccl` file, for example `test.ccl`, and add:

```
function main() {
  test()
}
```

This calls the `test` function from the `ccl-testpkg` package, which prints:

```
If you see this, it works!
```

> [!NOTE]  
> In future versions of CColon, you'll have to **import the package** first, to use its functions. The Guide will be 

## Resources

CColon
[https://github.com/TRC-Loop/ccolon](https://github.com/TRC-Loop/ccolon)

Package Manager Docs
[https://ccolon.arne.sh/tools/packages/](https://ccolon.arne.sh/tools/packages/)
