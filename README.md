![blank.css](http://imgh.us/blank-logo.svg)

# [blank.css](http://github.com/blank-css) ‣ space
blank.css space utilities for consistent layouts

## configure

Like all of blank.css, the spacing utilites are completely configurable using
custom properties and custom media queries, like so:

```css
:root {
	--blank-space-n: 0;
	--blank-space-bb: .125rem;
	--blank-space-sm: .25rem;
	--blank-space-md: .5rem;
	--blank-space-lg: 1rem;
	--blank-space-gg: 2rem;
}

@custom-media --bb (min-width: 22rem);
@custom-media --sm (min-width: 29rem);
@custom-media --md (min-width: 36rem);
@custom-media --lg (min-width: 45rem);
@custom-media --gg (min-width: 54rem);
```

## install

`npm i -D blank-css-space`

## use

now you have these classes at your disposal, where

identifier | available
---------- | -----------
`{type}`     | `mg` or `pd`
`{Side}`     | `T` or `B` or `L` or `R` or `H` or `V`
`{size}`     | `n` or `bb` or `sm` or `md` or `lg`

```css
.blank-u-{type}{Side}{size}
```

for example, if I wanted a small amount of padding on all sides, but large horizontal margins, I'd do this:

```html
<div class="blank-u-pdAs blank-u-mgVlg">My item</div>
```

If I wanted the small padding to change to large when I hit the `md` breakpoint, I'd do:
```html
<div class="blank-u-pdAs blank-u-mgVlg blank-u-md-pdAlg">My item</div>
```

Mix and match in whichever way you choose.
