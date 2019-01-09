# Spacers
Create sass space helpers similar to Bootstrap 4 Spacing

## Spacing helpers
  Best way to use it as a '@extend' to not litter markup:

  '.myButton
    @text-rendering:  .pvxl //padding vertical x-large
    will give you: padding-top: 4rem; padding-bottom: 4rem;''

  With the current default settings, generates classes like:

  '.mts = margin-top: 0.5rem'
  '.phm = padding-left: 1rem; padding-right: 1rem;'

   m - margin
   p - padding
   v - vertical
   h - horizontal
   n, xxs, xs, s, m, l, xl, xxl - sizes
