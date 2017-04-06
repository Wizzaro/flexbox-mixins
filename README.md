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
@include flex-direction([$value]) //default $value: row
@include flex-direction-row();
@include flex-direction-row-reverse();
@include flex-direction-column();
@include flex-direction-column-reverse();
```
#### Flex wrap
```
@include flex-wrap([$value]); //default $value: nowrap
@include flex-wrap-nowrap();
@include flex-wrap-wrap();
@include flex-wrap-wrap-reverse();
```
#### Flex flow
```
@include flex-flow([$direction][, $wrap]); //default $direction: row, $wrap: nowrap
@include flex-flow-row-nowrap();
@include flex-flow-row-wrap();
@include flex-flow-row-wrap-reverse();
@include flex-flow-row-reverse-nowrap();
@include flex-flow-row-reverse-wrap();
@include flex-flow-row-reverse-wrap-reverse();
@include flex-flow-column-nowrap();
@include flex-flow-column-wrap();
@include flex-flow-column-wrap-reverse();
@include flex-flow-column-reverse-nowrap();
@include flex-flow-column-reverse-wrap();
@include flex-flow-column-reverse-wrap-reverse();
```
#### Justify content
```
@include justify-content([$value]); //default $value: flex-start
@include justify-content-flex-start();
@include justify-content-flex-end();
@include justify-content-center();
@include justify-content-space-between();
@include justify-content-space-around();
```
#### Align items
```
@include align-items([$value]); //default $value: stretch
@include align-items-flex-start();
@include align-items-flex-end();
@include align-items-center();
@include align-items-baseline();
@include align-items-stretch();
```
#### Align content
```
@include align-content([$value]); //default $value: stretch
@include align-content-flex-start();
@include align-content-flex-end();
@include align-content-center();
@include align-content-space-between();
@include align-content-space-around();
@include align-content-stretch();
```
### Mixins for the Item Element
#### Align self
```
@include align-self([$value]); //default $value: auto
@include align-self-auto();
@include align-self-flex-start();
@include align-self-flex-end();
@include align-self-center();
@include align-self-baseline();
@include align-self-stretch();
```
#### Order
```
@include order([$int]); //default $int: 0
```
#### Flex grow
```
@include flex-grow([$int]); //default $int: 0
```
#### Flex shrink
```
@include flex-shrink([$int]); //default $int: 0
```
#### Flex basis
```
@include flex-basis([$value]); //default $value: auto
```
#### Flex
```
@include flex([$flex-grow][, $flex-shrink][, $flex-basis]); //default $flex-grow: 0, $flex-shrink: 0, $flex-basis: auto
```
## Licence

Licensed under MIT.
