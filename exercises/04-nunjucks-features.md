# Exercise 4: Using Nunjucks' features

As you've seen, Nunjucks doesn't do anything to our HTML, so let's start using some of Nunjucks' features to enrich our HTML.

Take a quick squizz through the [documentation for all the templating commands Nunjucks supports](https://mozilla.github.io/nunjucks/templating.html).

1. Edit `views/index.html.njk`, deleting everything inside it.

Now let's try to translate the following JavaScript into Nunjucks' template language, using `set` and `if` around the necessary HTML.

```javascript
const isItFriday = false;

if (isItFriday) {
  // Output the following HTML: 
  // <p>Hey hey hey! It's Friday! 🎉</p>
} else {
  // Output the following HTML: 
  // <p>Is it Friday yet? 🥱</p>
}
```

You can structure this in several ways in your `index.html.njk` template. Try write it as simply as possible.

Let's discuss.