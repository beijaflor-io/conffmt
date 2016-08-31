# conffmt
**conffmt** is a `.conf` file auto-formatter. It uses
[`language-conf`](https://github.com/beijaflor-io/haskell-language-conf) to
parse and pretty-print files.

## Installing
Download a pre-built binary or package from
https://github.com/beijaflor-io/conffmt/releases

Or build from source with `stack build` or `cabal install conffmt`

## Usage
```
conffmt - Conf formatter using Haskell language-conf

Usage: conffmt [-i|--inplace] [-o|--output ARG] [INPUTFILE]
  Format a .conf FILE

Available options:
  -h,--help                Show this help text
  -i,--inplace             Format the FILE inplace, replacing it's contents
  INPUTFILE                The input file (omission will cause `conffmt` to use
                           stdin)
```

## License
MIT
