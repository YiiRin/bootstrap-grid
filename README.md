# bootstrap-grid
Only the base grid framework of Bootstrap.

## compile options

You can change the variables in src/grid/_variables.scss to control the behavior of comilation.

- `$enable-grid`
    + if set 'false', then will output nothing
- `$enable-grid-media-query`
    + if set `false`, then responsive content will not be compiled
- `$container-max-widths` | `$grid-breakpoints` | `$grid-columns` | `$grid-row-columns`
    + I think you will know that what is this
- `$grid-gutter-width`
    + if you don't like gutter, you can set it to `0`
    + if you want to keep the gutter of columns, but want to remove the space between container and column,you need to read the source code to change default behavior for satisfing your needs.(it's short and simple)


