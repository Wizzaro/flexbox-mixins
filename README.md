# Wizzaro Sass Flexbox Mixins

## Basic information

This is a set of sass mixins for CSS Flexible Box Layout.
For more information about layout look on: https://www.w3.org/TR/css-flexbox-1/

Browsers Support:
- Chrome 21+
- Firefox 18+
- Opera 12.1+
- Safari 6.1+
- Edge
- IE10+

This mixins supports old browsers flexbox syntax.

## Install
`bower install wizzaro-sass-flexbox-mixins`

## Usage mixins
### Mixins for the Parent Element
#### Display
```
@include display-flex();
@include display-inline-flex();
```
#### Flex direction
```
@include flex-direction([$value: row])
```
#### Flex wrap
```
@include flex-wrap([$value: nowrap]);
```
#### Flex flow
```
@include flex-flow([$direction: row][, $wrap: nowrap]);
```
#### Justify content
```
@include justify-content([$value: flex-start]);
```
#### Align items
```
@include align-items([$value: stretch]);
```
#### Align content
```
@include align-content([$value: stretch]);
```
### Mixins for the Item Element
#### Align self
```
@include align-self([$value: auto]);
```
#### Order
```
@include order([$int: 0]);
```
#### Flex grow
```
@include flex-grow([$int: 0]);
```
#### Flex shrink
```
@include flex-shrink([$int: 0]);
```
#### Flex basis
```
@include flex-basis([$value: auto]);
```
#### Flex
```
@include flex([$flex-grow: 0][, $flex-shrink: 0][, $flex-basis: auto]);
```
## Licence

Licensed under MIT.
