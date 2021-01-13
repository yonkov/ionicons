## Ionicons

### Usage

[Ionicons](https://ionicons.com/) is a completely open-source icon set with 1,300 icons crafted for web, iOS, Android, and desktop apps. Ionicons was originally made for the Ionic Framework, a cross-platform hybrid and Progressive Web App framework.

Using the Web Component

The Ionicons Web Component is an easy and performant way to use Ionicons in your app. The component will dynamically load an SVG for each icon, so your app is only requesting the icons that you need.

```html
<ion-icon name="logo-facebook"></ion-icon>
```

Also note that only visible icons are loaded, and icons which are "below the fold" and hidden from the user's view do not make fetch requests for the svg resource.

### Installation
Download this repo and place it in your project or use a cdn.
#### Load Ionicons locally

Download this repo and place the following ```<script>``` near the end of your page, right before the closing ```</body>``` tag, to enable the font. If you have placed the ionicons folder in the project's root folder, use the following relative paths:

```html
<script src="/ionicons/ionicons.esm.js" type="module"></script>
<script src="/ionicons/ionicons.js"></script>
```

For more information on how to load the icons locally, check the following article: [2 Ways to Load Ionicons in WordPress (Locally and with CDN)](https://nasiothemes.com/2020/11/24/2-ways-to-load-ionicons-in-wordpress-locally-and-with-cdn/)

#### Load Ionicons via CDN

Use the following ```<script>``` to load the icons via CDN:

```html
<script src="https://unpkg.com/ionicons@5.2.3/dist/ionicons.js"></script>
```

For more information on how to load the icons with a CDN, check Ionicons official [documentation](https://ionicons.com/usage).

### Cross-browser Support
The 5-th version of the icons works great on all modern browsers (Chrome, Firefox, Safary, Opera, etc.) and has partial support for Internet Explorer. With a few small css tweaks it can be made to work flowlessly with Internet Explorer 11. If you need to support this aging browser, you should add the following css to display icons in outline version:
```css
/* IE 11 Ionicons fix */
.ionicon-stroke-width {
  stroke-width: 32px;
  stroke: #333;
}

.ionicon-fill-none {
  fill: none;
}
``` 
### License

(C) 2013-2021 Ben Sperry, [MIT](https://opensource.org/licenses/MIT)