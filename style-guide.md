# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link
  href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500;600;700&family=Poppins:wght@400;500;700&display=swap"
  rel="stylesheet">
```

Ionicon

``` html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

## Colors

``` css
--raisin-black-1: hsl(234, 14%, 14%);
--raisin-black-2: hsl(231, 12%, 12%);
--raisin-black-3: hsl(228, 12%, 17%);
--eerie-black: hsl(240, 11%, 9%);
--light-gray: hsl(0, 0%, 80%);
--platinum: hsl(0, 4%, 91%);
--xiketic: hsl(275, 24%, 10%);
--orange: hsl(31, 100%, 51%);
--white: hsl(0, 0%, 100%);
--onyx: hsl(240, 5%, 26%);
```

## Typography

### Font Family

``` css
--ff-refault: "Refault", Georgia;
--ff-oswald: 'Oswald', sans-serif;
--ff-poppins: 'Poppins', sans-serif;
```

### Font Size

``` css
--fs-1: 54px;
--fs-2: 34px;
--fs-3: 30px;
--fs-4: 26px;
--fs-5: 22px;
--fs-6: 20px;
--fs-7: 18px;
--fs-8: 15px;
--fs-9: 14px;
--fs-10: 13px;
--fs-11: 12px;
```

### Font Weight

``` css
--fw-400: 400;
--fw-500: 500;
--fw-700: 700;
```

## Transition

``` css
--transition-1: 0.15s ease-in-out;
--transition-2: 0.15s ease-in;
--transition-3: 0.25s ease-out;
```

## Spacing

``` css
--section-padding: 60px;
```

## Clip path

``` css
--polygon-1: polygon(90% 0, 100% 34%, 100% 100%, 10% 100%, 0 66%, 0 0);
--polygon-2: polygon(0 0, 100% 0%, 82% 100%, 0% 100%);
--polygon-3: polygon(0 0, 100% 0%, 100% 100%, 18% 100%);
--polygon-4: polygon(96% 0, 100% 36%, 100% 100%, 4% 100%, 0 66%, 0 0);
```

## Custom font

``` css
/* Webfont: Refault-Italic */
@font-face {
    font-family: 'Refault';
    src: url('../fonts/REFAULT.eot'); /* IE9 Compat Modes */
    src: url('../fonts/REFAULT.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
         url('../fonts/REFAULT.woff') format('woff'), /* Modern Browsers */
         url('../fonts/REFAULT.woff2') format('woff2'), /* Modern Browsers */
         url('../fonts/REFAULT.ttf') format('truetype'); /* Safari, Android, iOS */
    font-style: italic;
    font-weight: normal;
    text-rendering: optimizeLegibility;
}
```
