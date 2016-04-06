# Media Query Mixin

An SCSS Mixin to easily target different media queries


### Usage

```scss
.div_wrapper {
@include media_query( $prop, $default : null, $sm : null, $md : null, $lg : null ) {
@include media_query( width, 100%, 90%, 80%, 70% );
@include media_query( font-size, 1em, 1.3em, 1.5em, 1.6em );
}
```