# CSS Playground

This project is heavily inspired by [JankCSS](https://jankcss.com/), JankCSS project is also available on [Github](https://github.com/jamezmca/jankcss).

## What is this?

This is a playground for CSS, it's a place to experiment with CSS and see what you can do with it. It's also a place to learn about CSS and how it works.
On the top of the page you will see a big textarea, this is where you write your CSS. You can write any CSS you want in here and it will be applied in real time to the page below. The only thing you can't modify is the textarea itself, this is so you can't screw up the page.
Whatever you type in will be stored in the localstorage, so you can come back to it later and continue learning.

## Known issues

```css
* {
    display: none;
}
```
Also hides the textarea, so you can't undo it. If you do this, you will have to clear your localstorage to get it back.

## TODO

- [ ] Allow to use tabs in the textarea
- [ ] Let users see the raw HTML as well as the rendered HTML
- [ ] Add a button to clear the localstorage
- [ ] Give actual tips instead of just dummy text
