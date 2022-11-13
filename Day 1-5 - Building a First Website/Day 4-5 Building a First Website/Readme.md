# Storing CSS code in External

```An external style sheet is a separate CSS file that can be accessed by creating a link within the head section of the webpage. Multiple webpages can use the same link to access the stylesheet. The link to an external style sheet is placed within the head section of the page.```

## Example:

#### Create a file using .css extention => style.css

#### Then link with html page:

<head> 
    <link rel="stylesheet" href="style.css"> 
</head>

<img src="external-css.jpg" alt="External CSS Code">

## What is a CSS selector?

```A CSS selector is the first part of a CSS Rule. It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them.```

## CSS Selectors

```Simple selectors (select elements based on name, id, class)```


#image{
    margin: auto; /* We can seletct id using hash sign = (#) */
}

.heading3{
    color: black; /* We can seletct class using dot sign = (.) */

}

# Working with font-size and px 

```To allow users to resize the text (in the browser menu), many developers use pixels. 1em is equal to the current font size. The default text size in browsers is 16px. So, the default size of 1em is 16px. em is the some as px```

# Using Other Fonts from Google Fonts

1. https://fonts.google.com
2. Find your fav font and select it
3. copy it for your html page or css 

## Example

```@import url('https://fonts.googleapis.com/css2?family=Ubuntu&display=swap');```

``` font-family: 'Ubuntu', sans-serif;```
