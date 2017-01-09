## aframe-tube-component

> Creates a tube with an inner and outer radius.

Size, orientation and default-values are same as an <a-cylinder>.

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|outerRadius     |The outer radius of the tube.            |1               |
|innerRadius          |Inner radius of the tube. If the value is 0, the tube is a cylinder with no rings but caps at the ends.             |0.9               |
|height          |The height of the tube.             |1               |
|segments          |Radial segments             |32               |


#### Browser

Install and use by directly including the browser files:

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.4.0/aframe.min.js"></script>
  <script src="https://github.com/jellix79/aframe-tube-component/index.js"></script>
</head>

<body>
  <a-scene>
    <a-entity tube=""></a-entity>
  </a-scene>
</body>
```