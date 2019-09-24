# The web

Web pages at their most basic are comprised of HTML.

# What is HTML I hear you ask?

HTML (short for hypertext markup language) was invented in 1990. It is used as the bones of any website and provides a number of different 
components to give structure to a site and also to tell a browser how to display certain elements of your site.

Here are some HTML tags:

- `<div>` (short for division - a section of your site)
- `<h1>` through to `<h6>` - these are header elements used to give prominence to more titles and similar
- `<p>` - short for paragraph
- `<button>` 
- `<a>` (this is used to tell the browser you're providing a link whether to a third party site or a link within your site)
- `<li>` (this is short for list item - your list items would then be surrounding by either `<ul>` (unordered list) or `<ol>` (ordered list) tags)

As you can see each tag is enclosed with < >. Reading HTML should give the reader an indication of the intention of whoever
wrote the code. A browser reading HTML will apply certain basic styles to give effect to the user's intention. For example a <button> will look
like a button, an <a> will be highlighted to make it clear it's a link, or a list item will have a bullet point.

Let's have a play with some basic html elements. Go [https://jsbin.com/?html,output](here). 

One important thing to remember is that HTML tags will always have an opening tag (`<div>`) and a closing tag of the same kind (`</div`). Your content 
then goes in between the tags. For example: `<p>This is a paragraph of text</p>`. Note the backslash in the closing tag also. 

With HTML elements you can have a parent - child structure so that you have a series of elements enclosed within other elements. For example:

```
<div>
   <h1>Title</h1>
   <p>I'm a paragraph</p>
   <p>I'm also a paragraph</p>
</div>
```

HTML will generally stack like blocks, one on top of another so you have a vertical structure rather than horizontal.

# CSS

Things would get pretty boring if all we could use were HTML elements. This is where CSS (or cascading style sheets). The word cascading is used 
between if more than one style is applied to an element, there's an order of precedence applied to ensure consistency in terms of which style is applied.

CSS is intended to give power to users to style html and is meant to ensure separation of presentation (CSS) and content.

CSS can be used to add colour to your site, change the layout, add different fonts and much, much more.

Go back to JSBin and click the CSS button. Writing CSS requires a specific format as follows:

```
.[name of class] {
  add in styles here
  [rule name]: [value]
}
```

For example here a CSS rule which makes the color of the text red and the background black:

```
.appearance {
  color: red;
  background: black;
}
```

The `width` and `height` of elements can also be defined using CSS (different units can be used but go with `px` initially. Try creating some coloured blocks in JSBin. 

Other important rules in CSS are `margin` and `padding`. If you have a `<div>` element then the margin defines the spacing around the outside of the element, and padding defines the spacing inside the element. Margin and padding are important because they can be used to create space between different elements to help a site be visually appealing. You don't want everything crammed into a small space.

