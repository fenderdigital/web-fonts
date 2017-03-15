# Fender Web Fonts

## Quick Start

**In Development:**

Add:
`<link rel="stylesheet" href="https://rawgit.com/fenderdigital/fender-web-fonts/master/fonts/fonts.css">` to the `head` of your project

**In Production:**

Add: `<link rel="stylesheet" href="https://cdn.rawgit.com/fenderdigital/fender-web-fonts/`TAGVERSION`/fonts/fonts.css">` to the `head` of your project

## Usage

`.source-sans-b`

```
@font-face {
  font-family: 'SourceSansPro-Regular';
  src: url(<relative_path>/SourceSansPro-Regular.otf) format("opentype");
}
```

`.source-sans-b` **(bold)**
---
```
@font-face {
  font-family: 'SourceSansPro-Bold';
  src: url(<relative_path>/SourceSansPro-Bold.otf) format("opentype");
}
```

`.source-sans-i` _(italic)_
---
```
@font-face {
  font-family: 'SourceSansPro-It';
  src: url(<relative_path>/SourceSansPro-It.otf) format("opentype");
}
```

`.futura-book`
---
```
@font-face {
  font-family: 'FuturaPT-Book';
  src: url(<relative_path>/ParaType-FuturaPTBook.otf) format("opentype");
}
```

`.futura-heavy`
---
```
@font-face {
  font-family: 'FuturaPT-Heavy';
  src: url(<relative_path>/ParaType-FuturaPTHeavy.otf) format("opentype");
}
```
