# typesmith
Responsive typography system

## Installation

### Install via NPM

```bash
npm i --save typesmith-lib`
```

```scss
// your-project/style.scss
@import 'node_modules/mq/mq';
@import 'node_modules/typesmith/typesmith';
```

### Manual

#### Using @import
Download the `_typesmith.scss` file and move it in your sass/scss folder. You need a Sass `@import` to include it in your project. Choose this way in order to customize **typesmith** according to project needs.

#### Add CSS files
Download the files located in /dist/ folder choosing between default or minified version. Include them in your project as normal CSS files. In this case you couldn't customize typography values but use those by default.

## Dependencies
I order to use the libary you will need following tools:
- [mq](https://github.com/zetareticoli/mq)

## License
MIT License

Copyright (c) [2020] [Francesco Improta]

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
