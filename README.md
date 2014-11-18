Framework MX
============
Base simple responsive framework to rapidly build websites.  This framework it ment to be simply a OCSS framework.  It provides all the basic OCSS one needs to set the foundation to a simple responisve site. With that said, you'll more than likley need to create additional stylesheets for the polish and custom styles one needs for a given project.

## Base HTML
Framework MX uses HTML5 as its backbone.  We use a number of HTML5 elements that make our lives easier that require the HTML5 doctype.  Include it at the beginning of your projects.

```html
<!DOCTYPE html>
<html lang="en">
  ...
</html>
```

## Normalize and Reset
You'll notice at the top of the file we use a number or reset properites. Although we're not using the whole file, we are using the best parts in our option.


## Layout & Grid
Our grid system is a 12-grid percentage based layout that spans the full 100% of its container. We have an ```.inner``` class that limits the width to 1024px if needed in the layout.

### Example
<div class="row">
  <div class="span-2"></div>
  <div class="span-2"></div>
</div>


## Basic Grid HTML
```html
<div class="row">
  <div class="span-2"></div>
  <div class="span-2"></div>
</div>
```

