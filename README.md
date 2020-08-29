# blink.css
Everyone loves blinking text! Bring it to your site with `blink.css`.

`blink.css` brings back the HTML `<blink>` tag – using a single line<sup>1</sup> of CSS.

<sup>**1.** I mean, it really is just multiple lines without line breaks and indentation; but you get the idea.</sup>

## Installation
Using `blink.css` is very easy! All you have to do is add a simple style tag to your `<head>`:
```html
<style>blink{animation:blink 1s infinite}@keyframes blink{0%{opacity:0}59%{opacity:0}60%{opacity:1}}</style>
```
