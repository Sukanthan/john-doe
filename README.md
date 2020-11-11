This website is a single HTML file. It simply uses the `#anchor` suffix (from 1992) and the `:target` CSS selector to show and hide pages/content. This setup is databaseless, javascriptless, and buildshit-free, so you can edit your website with a text editor and upload it somewhere like a normal person.

To create a new page, add a `<section>` with a unique `id`
```html
<section id="contact">
   Contact me!
</section>
```
Then add link to it inside `<nav>`
```html
<a href="#contact">Contact</a>
```
