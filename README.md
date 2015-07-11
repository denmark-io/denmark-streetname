#denmark-streetname

> A list of streetname given a zipcodes

## Installation

```sheel
npm install denmark-streetname
```

## Documentation

```javascript
streetname = require('denmark-streetname')
```

This is a function with the signature `streetname(zipcode, callback)`:

```javascript
streetname(2800, function (err, list) {
  // Invalid zipcodes will produce an error.
  list = [
    'Vinagervej',
    'Vintappersøen',
    'Aldershvilevej',
    'Amundsensvej',
    'Bagsværd Møllevej',
    'Bagsværdvej',
    ...
  ]
});
```

## Source

The source is: http://dawa.aws.dk/vejedok

This uses the autocomplete feature, with an empty search. This way a
minimal (in terms of size) response is obtained.

##License

**The software is license under "MIT"**

> Copyright (c) 2015 Andreas Madsen
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in
> all copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
> THE SOFTWARE.