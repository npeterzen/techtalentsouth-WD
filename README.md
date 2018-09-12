# Introduction to web design

##  Naming your files:
- Always use lowercase
- Don't use spaces
- If you need a space, add a - like-this.html
- For the "homepage" file, call it `index.html`
- At the end of your file name, include the file type. Example `file.html` or `file.css`

## HTML Tags
```HTML
<tag property="value" another-property="value"></tag>

<anothertag property="value" />
```

## Head
- The head tag is for information that the browser needs to help Google Search, Social media sharing.  Presents description information.

```HTML
<head>
  <title>My First Website</title>
  <meta name="description" content="Some quick description about my website. 150-160 characters long" />
  <meta charset="UTF-8" />
</head>
```

- **Title**: Title of the page, used in Google Search
- **Meta Description**: Used in Google Search preview text and social share text.
- __Charset__: Tells the browser about special characters like quotes, copyright symbols and non-English letters.    

## Body
- The `<body>` tag is all of your content that is visible on the page.

## headlines H1 - H6
- Headlines are topics of your page.
- H1 is the primary topics
- Each headline is a sub-topic of the previous level

**Example:**
```HTML
<body>
  <h1>My First Website: Planet Earth</h1>
  <h2>North America</h2>
  <h3>United States</h3>
  <h4>North Carolina</h4>
  <h5>Raleigh</h5>
  <h6>HQ Raleigh, 310 S. Harrington St. </h6>
</body>
```

## Main
- The `<main>` tag tells Google where the main content is located for SEO.  

## Paragraphs and styles
- `<p>` is for paragraph
- `<strong>` is bold
- `<em>` is italic
- `<u>` is underline

## Ordered Lists and Unordered Lists
- `<ul>` is for Unordered list of bulleted items
- `<ol>` is a numbered list of items

```HTML
<ul>
  <li>Coding</li>
  <li>Puns </li>
  <li>Haikus </li>
</ul>
<ol>
  <li>Gather the ingredients</li>
  <li>Mix the ingredients</li>
  <li>Grease the pan </li>
  <li>Bake the cake at 300 degrees for 35 minutes</li>
  <li>Let the cake chill and serve.</li>
</ol>
```

## Horizontal Rule - Thematic Change
- Use `<hr>` or `<hr/> ` to define a thematic change in the content

```HTML
<h1>HTML</h1>
<p>HTML is a language for describing web pages.....</p>

<hr>

<h1>CSS</h1>
<p>CSS defines how to display HTML elements.....</p>
```

## Images
- In HTML, images are defined with the `<img>` tag.
- The `<img>` tag is empty, it contains attributes only, and does not have a closing tag.
- The `src` attribute specifies the URL (web address) of the image:

```HTML
<img src="url">
```
- The `alt` attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the `src` attribute, or if the user uses a screen reader).
- The value of the `alt` attribute should describe the image:
- __Note:__ The alt attribute is required. A web page will not validate correctly without it.
- You can use the style attribute to specify the width and height of an image.

```html
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
```
- Alternatively, you can use the width and height attributes:

```HTML
<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
```

- Use relative sizes to make your image responsive

```HTML
<img src="profile.jpg" width="100%" />
```

## Links
- The `<a>` tag defines a hyperlink, which is used to link from one page to another.
- The most important attribute of the <a> element is the `href` attribute, which indicates the link's destination.

```HTML
<a href="https://instagram.com/swaggyp317" target="_blank">
  Follow me on instagram
</a>
```
