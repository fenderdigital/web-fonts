# Fender Web Fonts

## Usage

Usage is class based, mapping to the following typefaces.

`.source-sans`
---

```
@font-face {
  font-family: 'SourceSansPro-Regular';
  font-weight: 400;
  font-style: normal;
  src: url(<relative_path>/SourceSansPro-Regular.otf);
}
```

`.source-sans-bold`
---
```
@font-face {
  font-family: 'SourceSansPro-Bold';
  font-weight: 800;
  font-style: normal;
  src: url(<relative_path>/SourceSansPro-Bold.otf);
}
```

`.source-sans-it` _(italic)_
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
