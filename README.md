# GIMP thumbnailer

## Description

This tool is a thumbnailer for XDG desktops. It generates thumbnails for XCF image files (and compressed variants) using GIMP in batch mode.

It uses `gimp-console` when available, otherwise it uses `gimp` without interface.


## Installation

```sh
make install
make update-db
```

The install prefix can be modified with the `PREFIX` environment variable.

On systems supported by checkinstall, one may also produce a package this way:

```sh
make checkinstall
```

The package will be written in the `build/` directory.


## About the thumbnailer

The thumbnailer can be used by third party tools like that:

```sh
gimp-thumbnailer -s SIZE INFILE OUTFILE
```


## Warning

No warranty is given, use this at your own risk.


## Author

Thomas Debesse <hidden mail='dev ad illwieckz.net'/>


## License

This tool is distributed under the highly permissive and laconic [MIT License](LICENSE.md).
