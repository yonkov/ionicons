## Ionicons

### Usage

Ionicons is a completely open-source icon set with 1,300 icons crafted for web, iOS, Android, and desktop apps. Ionicons was made for Ionic Framework, a cross-platform hybrid and Progressive Web App framework.
Using the Web Component

The Ionicons Web Component is an easy and performant way to use Ionicons in your app. The component will dynamically load an SVG for each icon, so your app is only requesting the icons that you need.

Also note that only visible icons are loaded, and icons which are "below the fold" and hidden from the user's view do not make fetch requests for the svg resource.
Installation

### Installation

Place the following ```<script>``` near the end of your page, right before the closing ```</body>``` tag, to enable them.

```<script src="/ionicons/ionicons.esm.js" type="module"></script>```
```<script nomodule src="/ionicons/ionicons.js"></script>```

### License

Released by the Ionic Team under MIT License