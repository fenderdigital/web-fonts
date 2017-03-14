# Fender Web Fonts

## Quick Start

**In Development:**

Add:

`<link rel="stylesheet" href="https://rawgit.com/fenderdigital/fender-web-fonts/master/fonts/fonts.css">`

to the `head` of your project

**In Production:**

TBD

## Usage

```
@font-face {
  font-family: 'SourceSansPro-Regular';
  src: url(<relative_path>/SourceSansPro-Regular.otf);
}
```

`.source-sans-b` **(bold)**
---
```
@font-face {
  font-family: 'SourceSansPro-Bold';
  src: url(<relative_path>/SourceSansPro-Bold.otf);
}
```

`.source-sans-i` _(italic)_
---
```
@font-face {
  font-family: 'SourceSansPro-It';
  src: url(<relative_path>/SourceSansPro-It.otf);
}
```

`.futura-book`
---
```
@font-face {
  font-family: 'FuturaPT-Book';
  src: url(<relative_path>/ParaType-FuturaPTBook.eot);
  src: url(<relative_path>/ParaType-FuturaPTBook.eot?#iefix) format('embedded-opentype'),
    url(<relative_path>/ParaType-FuturaPTBook.woff2) format('woff2'),
    url(<relative_path>/ParaType-FuturaPTBook.woff) format('woff'),
    url(<relative_path>/ParaType-FuturaPTBook.ttf) format('truetype');
}
```

`.futura-heavy`
---
```
@font-face {
  font-family: 'FuturaPT-Heavy';
  src: url(<relative_path>/ParaType-FuturaPTHeavy.eot);
  src: url(<relative_path>/ParaType-FuturaPTHeavy.eot?#iefix) format('embedded-opentype'),
    url(<relative_path>/ParaType-FuturaPTHeavy.woff2) format('woff2'),
    url(<relative_path>/ParaType-FuturaPTHeavy.woff) format('woff'),
    url(<relative_path>/ParaType-FuturaPTHeavy.ttf) format('truetype');
}
```
