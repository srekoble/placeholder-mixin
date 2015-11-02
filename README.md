# Placeholder mixin (scss)

There are situations where we want to create a dummy prototype (wireframe) of a layout or a website without any real content, images or text. So what we really need is just dummy placeholders. Instead of searching the web for
landscape images or lorem texts we can add wireframe boxes to create elements.

## How to import

Placeholder mixin can be easily imported into any sass project.

````scss
@import "placeholder-mixin";
````

## How it works

Placeholder mixin contain 3 arguments:

* Width
* Height
* Name (optional)

## How to use

An example:

````scss
// with name
.foo {
  @include placeholder(100%, auto, header);
}

// without name
.bar {
  @include placeholder(100px, 200px);
}
````

Check a wireframe example with placeholder mixin usage: [http://srekoble.github.io/placeholder-mixin/](http://srekoble.github.io/placeholder-mixin/)

With the usage of some basic layout styles we can create the above page. See the following scss partial for a
better understanding of placeholder mixin usage.

[https://github.com/srekoble/placeholder-mixin/blob/master/sass/demo.scss](https://github.com/srekoble/placeholder-mixin/blob/master/sass/demo.scss)

## Future tasks

* Add placeholder boxes with dummy text
