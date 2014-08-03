SASS Mixins
===========

A collection of [SASS](http://sass-lang.com/ "SASS") mixins for your project.

* [Animation](#animation)
   * [Keyframes](#keyframes)
* Background size
* Box shadow
* Opacity
* Clearfix
* Border radius
* Box-sizing
* Transition
* Columns
* Transform
    * Default
    * Translate
    * Skew
    * Scale
    * Rotate
* Gradients
    * Horizontal
    * Vertical

## Animation

```
.class { @include animation(animationName 1s); }
```

### Keyframes
```
@include keyframes(animationOne) {
    from { background-color: red; }
    to { background-color: black; }
}
```
