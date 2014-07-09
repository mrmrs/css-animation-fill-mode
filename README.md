# CSS ANIMATION FILL MODE

  Mobile-first classes for css-animation-fill-mode.
  Set the desired css-animation-fill-mode on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-animation-fill-mode
```
or download the css on github and include in your project.

## File Size


## The Code
```
  .a-fil-non { animation-fill-mode: none; }
  .a-fil-frw { animation-fill-mode: forwards; }
  .a-fil-bck { animation-fill-mode: backwards; }
  .a-fil-bth { animation-fill-mode: both; }

@include break(not-small) {
  .a-fil-non-ns { animation-fill-mode: none; }
  .a-fil-frw-ns { animation-fill-mode: forwards; }
  .a-fil-bck-ns { animation-fill-mode: backwards; }
  .a-fil-bth-ns { animation-fill-mode: both; }
}

@include break(medium) {
  .a-fil-non-m { animation-fill-mode: none; }
  .a-fil-frw-m { animation-fill-mode: forwards; }
  .a-fil-bck-m { animation-fill-mode: backwards; }
  .a-fil-bth-m { animation-fill-mode: both; }
}

@include break(large) {
  .a-fil-non-l { animation-fill-mode: none; }
  .a-fil-frw-l { animation-fill-mode: forwards; }
  .a-fil-bck-l { animation-fill-mode: backwards; }
  .a-fil-bth-l { animation-fill-mode: both; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

