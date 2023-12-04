# CSS Directory
This directory contains all of the CSS files for your website. You can add as many files as you want, but make sure 
to link them to your HTML files. All of the CSS used in your website should be external stylesheets that can be 
reused throughout the website.

## CSS Reset
A CSS reset file is included in this directory. Be sure to add this to your `html` pages _before_ your own custom CSS 
files.

## Hints
CSS is meant to be reusable. This means that you should be thinking of CSS as self-contained styles that can be used 
on multiple elements throughout your website.

For example, if you want to make a `a` look like a `button`, you should create a class called `button` and apply it 
to any `a` elements that you want to look like a button.

```css
.button {
  background-color: tomato;
  color: #fff;
  padding: 1rem 1.5rem;
  border-radius: .25rem;
}
```

Don't overthink CSS Grid. It's a lot easier than it looks. For example, to create a 3-column layout, you can use 
`grid-template-columns`

```css
.container {
  display: grid;
  gap: 2rem;
  grid-template-columns: repeat(3, 1fr);
}
```