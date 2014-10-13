# artcat

A cat(1) like utility for text mode art.

## Installation

You can use either `pip` or `easy_install`:

    $ pip install artcat

## Upgrading from a previous release

You can use either `pip` or `easy_install`:

    $ pip install -U artcat

## Usage

Artcat will inspect your current locale settings to autodetect the target
output encoding. If no suitable encoding can be detected, UTF-8 output is
assumed.

    usage: artcat [-h] [-s SOURCE_ENCODING] [-t TARGET_ENCODING] [-o OUTPUT]
                  [filename [filename ...]]

    positional arguments:
      filename

    optional arguments:
      -h, --help            show this help message and exit
      -s SOURCE_ENCODING, --source-encoding SOURCE_ENCODING
                            source encoding (default: cp437)
      -t TARGET_ENCODING, --target-encoding TARGET_ENCODING
                            target encoding (default: autodetect)
      -o OUTPUT, --output OUTPUT
                            output (default: STDOUT)

## Bugs/Features

Please use the [GitHub issue tracker](https://github.com/tehmaze/artcat/issues).
