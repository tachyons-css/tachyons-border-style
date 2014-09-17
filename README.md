# TACHYONS-BORDER-STYLE

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-border-style
```
or download the css on github and include in your project.

## The Code
```

/*

   BORDER STYLES

 */

.bs-none {   border-style: none; }
.bs-dotted { border-style: dotted; }
.bs-solid {  border-style: solid; }

@include break(not-small) {
  .bs-none-ns {   border-style: none; }
  .bs-dotted-ns { border-style: dotted; }
  .bs-solid-ns {  border-style: solid; }
}

@include break(medium) {
  .bs-none-m {   border-style: none; }
  .bs-dotted-m { border-style: dotted; }
  .bs-solid-m {  border-style: solid; }
}

@include break(large) {
  .bs-none-l {   border-style: none; }
  .bs-dotted-l { border-style: dotted; }
  .bs-solid-l {  border-style: solid; }
}
```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

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

