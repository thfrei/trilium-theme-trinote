# Development

run

```cmd
npx live-server
```

## Dark Theme Literature

- <https://css-tricks.com/a-complete-guide-to-dark-mode-on-the-web/>
- <https://css-tricks.com/dark-modes-with-css/>
- Palette generator: <http://colormind.io/bootstrap/>
  - F3F8EF, EFA765, E8523F, 706C74, 325892
- Convert colors: <https://www.w3schools.com/colors/colors_picker.asp>
- Relative Colors css: <https://stackoverflow.com/questions/55329996/how-to-create-color-shades-using-css-variables-similar-to-darken-of-sass>

```css
--color: 0, 100%;
--l: 50%;

--color-primary: hsl(var(--color), var(--l));
--color-primary-darker: hsl(var(--color), calc(var(--l) - 5%));
--color-primary-darkest: hsl(var(--color), calc(var(--l) - 10%));
```
