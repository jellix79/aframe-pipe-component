## aframe-pipe-component

> Creates a cylinder with an inner and outer radius.

Size, orientation and default-values are same as an <a-cylinder>.

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|outerRadius     |The outer radius of the pipe.            |1               |
|innerRadius          |Inner radius of the pipe. If the value is 0, the pipe is a cylinder with no rings but caps at the ends.             |0.9               |
|height          |The height of the pipe.             |1               |
|segments          |Radial segments             |64               |


#### Browser

Install and use by directly including the browser files:

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.4.0/aframe.min.js"></script>
  <script src="https://github.com/jellix79/aframe-pipe-component/dist/pipe.js"></script>
</head>

<body>
  <a-scene>
    <a-entity pipe=""></a-entity>
  </a-scene>
</body>
```