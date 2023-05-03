# css 

**CSS stands for Cascading Style Sheets, and it is a language used to describe the presentation of HTML (Hypertext Markup Language) and XML (Extensible Markup Language) documents. CSS is used to control the layout, fonts, colors, and other visual aspects of web pages and user interfaces.**

## CSS provides several methods to define the styles. 

> Inline Styles

> Internal Style Sheets

> External Style Sheets

<hr>

## Inline Styles: 

**This method allows you to apply styles directly to an HTML element using the style attribute. This method is useful for making quick, one-off style changes.**

```
<h1 style="color: red;">This heading containt red color</h1>
```
<hr>

## Internal Style Sheets: 

**This method allows you to define the styles within the <head> section of your HTML document, using the <style> tag. This method is useful when you want to apply styles to a specific page only.**

```
<head>
  <style>
    h1 {
      color: red;
    }
  </style>
</head>
```
<hr>

## External Style Sheets: 

**In this method, you can define the styles in a separate CSS file, which is then linked to your HTML document using the <link> tag. This method allows you to maintain consistent styles across multiple pages.**

```
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>

```
### My Great Heading {#myId}

### CSS File Code Like

```
/* Element Selector */
h1 {
  font-size: 24px;
}

/* Class Selector */
.myClass {
  background-color: #fff;
}

/* ID Selector */
#myId {
  border: 1px solid black;
}

```

<hr>
