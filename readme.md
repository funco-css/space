# Funco :: space

## Functional CSS Spacing Utility

### setup

`@import "lib/{margin|padding}/{short|long}"`

```css
:root {
	--funco-space--5: .125rem;
	--funco-space--4: .25rem;
	--funco-space--3: .333rem;
	--funco-space--2: .5rem;
	--funco-space--2: .666rem;
	--funco-space--1: .8rem;
	--funco-space-0: 1rem;
	--funco-space-1: 1.125rem;
	--funco-space-2: 1.25rem;
	--funco-space-3: 1.5rem;
	--funco-space-4: 1.75rem;
	--funco-space-5: 2rem;
	--funco-space-6: 3rem;
	--funco-space-7: 4rem;
	--funco-space-8: 5rem;
	--funco-space-9: 6rem;
	--funco-space-10: 7rem;
}

@custom-media --mq-xs (min-width: 20em);
@custom-media --mq-sm (min-width: 30em);
@custom-media --mq-md (min-width: 37em);
@custom-media --mq-lg (min-width: 43em);
@custom-media --mq-xl (min-width: 50em);
```

### usage

`.mg/a/2` or `.margin/all/2`

```css
.{margin|padding}/{all|horizontal|vertical|top|bottom|left|right}/{-5 – 10|none}{@xs|sm|md|lg|xl}
```
