##### HTML History

 * Tim Berners-Lee invented HTML in 1991
 * 1991 to 1999, HTML developed from version 1 to version 4
 * 2004 WHATWG (Web Hypertext Application Technology Working Group) was formed.
 * 2006 W3C announced that they would support WHATWG.
 * 2008 the first HTML5 public draft was released.
 * W3C HTML5 recommendation was released 2014.

### What is New in HTML5?

Basic useful feature list:

 * The DOCTYPE declaration for [HTML5](#) is simple
 * The character encoding (charset) declaration is simple

```
<!DOCTYPE html>
```
```
<meta charset="UTF-8">
```
#### New HTML5 Elements
 
 ``` 
  - semantic elements like <header>, <footer>, <article>, and <section>
  - Form elements and Attributes like number, date, time, calendar, and range
  - graphic elements: <svg> and <canvas>
  - multimedia elements: <audio> and <video>
 ```	
 
#### HTML5 API's (Application Programming Interfaces)

Most interesting new HTML5 APIs are
 * HTML Geolocation
 * Drag and Drop
 * Local Storage
 * Application Cache
 * Web Workers
 * SSE

#### HTML5 Browser Support

```
HTML5 is supported in all modern browsers.
```

#### New Semantic Elements (listed few)

```html
<header>,<footer>,<nav>,<section>,<figure>,<figcaption>,<aside>, <summary>, <progress>, <details>
```

#### New Form Elements

```html
<datalist>, <keygen>, <output>
```


#### New Input Types (listed few)

```html
<color>, <email>, <search>, <tel>, <date>, <datetime>, <number>, <url>, <range>
```

#### Graphics Elements

```html
<canvas>, <svg>
```

#### Media Elements

```html
<video>, <audio>, <source>, <track>, <embed>
```

#### Use of HTML5Shiv

HTML5Shiv is a JavaScript workaround to enable styling of HTML5 elements in versions of Internet Explorer prior to version 9.

Add the HTML5Shiv:

```html
<!--[if lt IE 9]>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js"></script>
<![endif]-->
```

#### Setting The Viewport

HTML5 introduced a method to control over the viewport, through the ``` <meta> ``` tag.

The viewport is the user's visible area of a web page. It varies with the device, and will be smaller on a mobile phone than on a computer screen.

You should include the following <meta> viewport element in all your web pages:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

The width=device-width part sets the width of the page to follow the screen-width of the device (which will vary depending on the device).

The initial-scale=1.0 part sets the initial zoom level when the page is first loaded by the browser.

