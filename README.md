# SidebarJS
Create mobile sidebar/sidenav experiance in pure javascript.

```ssh
npm install sidebarjs --save
```

## Demo
*Open the demo on your device and try the touch gestures!*

* [CodePen](http://codepen.io/lorenzodianni/full/VaqZJL/)
* [RawGit](https://rawgit.com/lorenzodianni/SidebarJS/master/demo/index.html)

## Fast Implementation
Insert **sidebarjs.min.css** and **sidebarjs.min.js** in your index.html file and create a tag (div, aside or what you prefer) with the attribute **[sidebarjs]**.
All contents you will write inside tag[sidebarjs] will be rendered inside the sidebar.
For open/close the sidebar, put wherever you want the **[sidebarjs-toggle]** attribute.
Then simply init it with **new SidebarJS()** and you are ready!
```html
<head>

  <link rel="stylesheet" href="sidebarjs.min.css">

</head>
<body>

  <div sidebarjs-toggle>Open/Close</div>

  <div sidebarjs>
    <div sidebarjs-toggle>Open/Close</div>
    <nav>
      <a href="link">Home</a>
      <a href="link">About</a>
      <a href="link">Contacts</a>
    </nav>
  </div>

  <script src="sidebarjs.min.js"></script>
  <script>
  // Init SidebarJS
  var sidebarjs = new SidebarJS();
  </script>

</body>
```
