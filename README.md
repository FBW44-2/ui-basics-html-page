# Intro to HTML

## Markup

> In computer text processing, a markup language is a system for annotating a document in a way that is syntactically distinguishable from the text, meaning when the document is processed for display, the markup language is not shown, and is only used to format the text.

> -**Wikipedia**

HTML has a tree like structure. The `<html>` element is the root of the document.
What we see in the browser is what we place inside the `<body>` element.

![](images/grumpy-cat-small.png)

Read more on [MDN](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics).

HTML is very forgiving - you can write with mistakes and the browser will try to render it by autofixing it. Use the dev tools to identify what is going wrong.

It is important to us as developers that we indent the HTML file so that the file can be easly read and use editor features like collapsing a set of elements, but also so we can debug our code easily.

## Styles

We use CSS (Cascading Style Sheets) for styling.

![](images/css-declaration-small.png)

Read more on [MDN](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics).

We can write styles inline, directly on the element, but these are very difficult to overwrite with other styles - it general they are to be avoided.

We can add a `<style>` element directly in the `<head>` but this will quickly get out of hand as our CSS and HTML grow.

The 3rd option is to use an external stylesheet. This means we will create a file with the `.css` extension and add our rules in there. We will also need to link it with the HTML file. We do this by including a `<link>` pointing to the CSS file like this: `<link rel="stylesheet" href="styles.css">`. This is the approach we will be taking in our future projects.


## Editor

The editor is where we are going to spend most of our time.
It might be a good idea to get to know your editor well. Ger familiar with various shortcuts - you dont need to learn them all at once, but try to add a shortcut to your mind every now and then.

To open the command pallet in visual code:

```
CMD + Shift + P (mac)
CTTL + Shift + P (linux)
```

Once you are there you can search for the command you are looking for.

For example if you are in a markdown file, you can open the Markdown Preview and see the md file rendered.

You can also get to the UI Settings of VS Code.

### Resources

- [VS Code Tips and Tricks](https://code.visualstudio.com/docs/getstarted/tips-and-tricks)
- [VS Code + Emmet](https://code.visualstudio.com/docs/editor/emmet)
- [VS Code + Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)