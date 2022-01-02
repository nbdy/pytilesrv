# pytilesrv

## features

- [X] rendering
- [X] caching
- [X] web api

## install

`pip3 install pytilesrv`

## usage

```shell
usage: pytilesrv [-h] -s STYLESHEET [--width WIDTH] [--height HEIGHT] [--host HOST] [--port PORT] [--debug] [--directory DIRECTORY]

optional arguments:
  -h, --help            show this help message and exit
  -s STYLESHEET, --stylesheet STYLESHEET
                        Path to the mapnik xml stylesheet
  --width WIDTH         Width of the tiles
  --height HEIGHT       Height of the tiles
  --host HOST           Host to listen on
  --port PORT           Port to listen on
  --debug               Enable debug mode
  --directory DIRECTORY
                        Directory to store the tiles in
```
