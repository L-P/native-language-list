# native-language-list
A list of ISO 639-1 codes and their name in the language they represent.

## Data
The data is based on [umpirsky's language list][1] available in the [data](data/) directory in three formats: CSV, PHP
and JSON.

[1]: https://github.com/umpirsky/language-list

## Build
```shell
git submodule update --init
./build-list # PHP ≥ 7 is required.
```
