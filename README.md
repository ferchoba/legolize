# legolize

LEGOlize your images - budget [Mosaic Maker](https://petapixel.com/2017/03/02/lego-photo-booth-helps-build-portrait-bricks/) with [Pillow](https://python-pillow.org/).

## Example

![example](example.png)

## Usage

```shell
$ legolize --h
usage: legolize [-h] -i INPUT_IMAGE [-o OUTPUT_IMAGE] [-m {median,quant}]
                [-c COUNT]

LEGOlize given image

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT_IMAGE, --input-image INPUT_IMAGE
                        image to legolize
  -o OUTPUT_IMAGE, --output-image OUTPUT_IMAGE
                        output path
  -m {median,quant}, --method {median,quant}
  -c COUNT, --count COUNT
```

## License

MIT License

Copyright (c) 2017 Łukasz Hryniuk

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
