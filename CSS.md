# CSS

## CSS Tags
```CSS
tag{
  property-name: value;
}
```

## CSS filenames
Name your file `filename.css`

## Link the HTML <=> css
Add this to your **HTML** file. NOT your .css file
```HTML
<link rel="stylesheet" href="folder1/folder2/style.css" type="text/css" />
```
## Colors
```CSS
tag{
  /* Background colors */
  background-color: lightblue;
  /* RGBA is Red, Green, Blue, Alpha (transparency) */
  background-color: rgba(255, 0, 0, .5);
  background-color: black;

  /* Text-color with a word */
  color: darkblue;
  /* Text -colors with a HEX Code */
  /* Hex code is created with Red, Green, Blue: #RRGGBB */
  /* Hex numbers are 0-15 represented by 1-9,a-f */
  color: #ffffff;
  color: #000000;
  color: #00ff00;
  /* chrome browser supports opacity with additional hex values */
  color: #00ff00f0;
}
```

## Background-Images
```css
tag{
  /* Background image (repeats by default) */
  background-image: url("images/back.png");

  /* Host a REMOTE Image */
  background-image: url("https://upload.wikimedia.org/wikipedia/commons/5/58/Sunset_2007-1.jpg");

  background-size: 200px;
  /* Show the full image */
  background-size: contain;
  /* Cover entire page with the image */
  background-size: cover;

  background-repeat: no-repeat;
  background-position: top right;
}
```

## fonts
```css
/* import custom fonts from fonts.google.com */
@import url('https://fonts.googleapis.com/css?family=Abel');
tag{
  font-size: 40px;
  /* em = the current font-size */
  line-height: 2em;
  text-align: center;
  text-align: right;
  font-family: 'Abel', sans-serif;
}
```

## Class vs Id
- use `class` to define customization across multiple tags
  - grouping styles for many elements
  - class will override a "global" style i.e. a tag styling
  ```CSS
  /* this is like a global */
  p{
    /* styles */
  }
  ```
- use `id` to define customization for a single type
  - used for overriding class settings

```css
/* this is a class */
.yellow-text{
  color: yellow;
}

/* this is an id */
/* id overrides class */
#urgent{
  color: red;
}
```

## Global Tag, Class and ID

```css
p{
  color: #111;
}
/* classes and IDs name must start with a letter */
.class-name{
  color: #222;
}
#ID-name{
  color: #333;
}
```
- a global tag is generic like `p`
- a class will override a global
- an ID will override a class

## Padding vs Margin vs border
- Padding is the space inside a div
- Margin is the spacing outside the div
- Border goes between padding and margin and takes up actual pixel space.
