# Fender Web Fonts

## Example Usage

```
@font-face {
  font-family: 'SourceSansPro-Regular';
  font-weight: 400;
  font-style: normal;
  src: url(<some_path>/SourceSansPro-Regular.otf);
}

@font-face {
  font-family: 'SourceSansPro-Bold';
  font-weight: 800;
  font-style: normal;
  src: url(<some_path>/SourceSansPro-Bold.otf);
}

@font-face {
  font-family: 'SourceSansPro-It';
  src: url(<some_path>/SourceSansPro-It.otf);
}

@font-face {
  font-family: 'FuturaPT-Book';
  src: url(<some_path>/ParaType-FuturaPTBook.eot);
  src: url(<some_path>/ParaType-FuturaPTBook.eot?#iefix) format('embedded-opentype'),
    url(<some_path>/ParaType-FuturaPTBook.woff2) format('woff2'),
    url(<some_path>/ParaType-FuturaPTBook.woff) format('woff'),
    url(<some_path>/ParaType-FuturaPTBook.ttf) format('truetype');
}


@font-face {
  font-family: 'FuturaPT-Heavy';
  src: url(<some_path>/ParaType-FuturaPTHeavy.eot);
  src: url(<some_path>/ParaType-FuturaPTHeavy.eot?#iefix) format('embedded-opentype'),
    url(<some_path>/ParaType-FuturaPTHeavy.woff2) format('woff2'),
    url(<some_path>/ParaType-FuturaPTHeavy.woff) format('woff'),
    url(<some_path>/ParaType-FuturaPTHeavy.ttf) format('truetype');
}
```
