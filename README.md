SASS Mixins
===========

A collection of [SASS](http://sass-lang.com/ "SASS") mixins for your project.

* [Animation](#animation)
   * [Keyframes](#keyframes)
* [Background size](#background-size)
* [Box shadow](#box-shadow)
* [Opacity](#opacity)
* [Clearfix](#clearfix)
* [Border radius](#border-radius)
* [Box-sizing](#box-sizing)
* [Transition](#transition)
* [Columns](#columns)
* [Transform](#transform)
    * [Default](#default)
    * [Translate](#translate)
    * [Skew](#skew)
    * [Scale](#scale)
    * [Rotate](#rotate)
    * [Transform-origin)(#transform-origin)
* [Gradients](#gradients)
    * [Linear Horizontal](#linear-horizontal)
    * [Linear Vertical](#linear-vertical)

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

## Background size

```
.class { @include background-size(auto 100%); }
```

## Box shadow

```
.class { @include box-shadow(1px 1px 10px 10px #666, 2px 2px 5px 5px #ddd inset); }
```

## Opacity

```
.class { @include opacity(0.5); }
```

## Clearfix

```
.class { @include clearfix(); }
```

## Border-radius

```
.class { @include border-radius(10px); }
```

## Box-sizing

```
.class { @include box-sizing(); }
```

## Transition

```
.class { @include transition(color 1s .5s ease-out); }
```

## Columns

```
.class { @include columns(3, 150px, solid 1px red); }
```

## Transform

### Default

```
.class { @include transform(rotate(45deg); }
```

### Translate

```
.class { @include translate(100px, 100px); }
```

### Skew

```
.class { @include skew(10px, 10px); }
```

### Scale

```
.class { @include scale(0.75); }
```

### Rotate

```
.class { @include rotate(45deg); }
```

### Transform-origin

```
.class { @include transform-origin(left, top); }
```

## Gradients

### Linear horizontal

```
.class { @include horizontal-gradient(#666, #000); }
```

### Linear vertical

```
.class { @include vertical-gradient(#666, #000); }
```

