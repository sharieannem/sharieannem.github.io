---
layout: essay
type: essay
title: Do You Want A Skeleton or Do You Want A Body?
date: 2017-10-05
labels:
  - Semantic UI
  - UI Frameworks
  - HTML
  - CSS
---

<img class="ui fluid centered image" src="../images/frameworks-humour.jpg">

## Skeletons

You can think of programming in HTML as building a skeleton or maybe a doll that has absolutely no facial features, clothes, accessories, and hair. When you build that image in your mind, it can be a bit terrifying! Looking at it might even give you an urge to wanna add those special features to make the doll "pretty" and more easy to look at. In terms of programming, this is where CSS is put into play. You add a sprinkle of CSS to your HTML code and voila! Out comes a program that is more aesthetically appealing.

<hr style="border= 1px dashed black;">

<b>HTML Only:</b>

<h1 style="text-align: center">This is just a plain header</h1>

```html
<!DOCTYPE HTML>
<html>
<head>
</head>

<body>
<h1>This is just a plain header</h1>
</body>
</html>
```

<b>HTML + CSS:</b>

<h1 style="text-shadow: 2px 2px 10px #99FFFF; color: #FFFFFF; text-align: center">This is just a plain header</h1>

```html
<!DOCTYPE HTML>
<html>
<head>
</head>

<body>
<h1 style="text-shadow: 0 0 3px #99FFFF; color: #FFFFFF; text-align: center">This is just a plain header</h1>
</body>
</html>
```
<hr style="border= 1px dashed black;">

## The Process and Time Commitment

The combination of HTML with CSS can produce beautifully designed websites but coding from scrath can result to some cons that you are likely to experience. First of all, to be able to create sylish user interfaces, you would need an extensive knowledge of the HTML and CSS programming languages plus A LOT of practice to enhance your application of your knowledge. Even with that, you would still be troubled by the responsibility of making and maintaining your web application's compatibility with multiple browsers and platforms (which could take more time than it took you to code). All the while, debugging would be a nightmare with the hundreds of lines of code that you had written.

## UI Frameworks to the rescue!

When I used to code from scratch, majority of the time, I needed to refer back to a previous program or online documentation for the proper values for certain properties of a selector (such as how position can take on the values "static", "relative", "fixed", "absolute", or "sticky"). Then I became exposed to UI frameworks (in particular, Semantic UI) and I was AMAZED! The functionality of UI frameworks make it "easier" and extremely faster to create standard 21st century web applications. Although there is still a big learning curve because of the amount of memorization due to the extensiveness of certain UI frameworks, most of the "nitpicking" of specific styling components are done for you.
For example, when displaying an image that is centered, circular, and bordered, <a href="https://semantic-ui.com/">Semantic UI</a>— which is a UI framework that provides web developers with semantic friendly HTML in order to build "beautiful, responsive layouts"—can do that for you using those exact keywords.

<hr style="border=1px dashed black;">

<img style="width: 300px; margin-left: 40%; border: 1px solid black; border-radius: 50%;" src="../images/frameworks-example.jpg">

<b>Code without framework:</b>

```html
<img style="width: 300px; margin-left: 40%; border: 1px solid black; border-radius: 50%;" src="../images/frameworks-example.jpg">
```

<img class="ui medium centered bordered circular image" src="../images/frameworks-example.jpg">

<b>Code with framework</b>

```html
<img class="ui medium centered bordered circular image" src="../images/frameworks-example.jpg">
```

Although it does not look like it with this single image component, Semantic and all other UI frameworks take care of the itty-bitty styling components for you all the while using a minimal amount of lines of code as possible. Also, compatibility across multiple browsers and platforms is handled by the framework itself so you, as the developer, can divert more of your focus on the design and functionality of your web app.

## Conclusion

Discovering Semantic UI and reading about other front-end frameworks as well (such as <a href="http://getbootstrap.com/">Bootstrap</a>, <a href="https://foundation.zurb.com/">Foundation</a>, <a href="http://materializecss.com/">Materialize</a>, etc.) has made me realize a whole new side of web development. If you are tired of coding HTML and CSS from scratch and want to be able to make modern user interfaces more quickly, then try incorporating UI frameworks into your code!
