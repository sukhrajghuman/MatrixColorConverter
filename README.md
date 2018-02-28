# MatrixColorConverter
  Takes a user selected Fe Color Matrix and applies it to a user selected color, effectively applying a filter to said color


### Install

```
$npm install fe-color-matrix-converter
```
### Usage

```
@import node-modules/fe-color-matrix-converter/dist/index

body {
      color: applyFilterToColor($feColorMatrix, $color)
}
```

### Parameters

The applyFilterToColor function takes two parameters

1. `$filterA:` this is the fe color matrix. It should be in the form of a nested list. See below
    * e.g. ((1 0 0 0 0), 
            (0 0 0 0 0),
            (0 0 0 0 0),
            (0 0 0 1 0))
          
2. `$color:` this could be in the form of either RGBA, HSL, HEX or just plain text. 

### Release History

* v1.0.0 - First release
