# p5js-extension
p5js-extension provides some missing functions in `p5.js`.

## Usage
Link to it in your HTML file. It's only working in combination with p5.js.

``` html
<script src="p5.js"></script>
<script src="addScreenPositionFunction.js"></script>
```

## Convert Canvas <-> World coordinate

```
addCoordinateConvertFunction();
```

## Acknowledgements
Thanks to Thibault Coppex (@tcoppex) for the 3d-modelview-projection-math he supplied in the issue discussion thread (https://github.com/processing/p5.js/issues/1553).

Thanks to Hartmut Bohnacker (@bohnacker) for the core code of adding 3d-modelview-projection-function he supplied in the repository (https://github.com/bohnacker/p5js-screenPosition).
