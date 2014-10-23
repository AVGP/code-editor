code-box
========

Code editor web component, wrapping CodeMirror

Usage
-----
* Import the code-editor.html into your application
* Insert a `<code-editor>` tag

Example:

```html
<!doctype html>
<html>
<head>
  <link rel="import" href="http://components.geekonaut.de/code-editor/code-editor.html">
</head>
<body>
  <h1>Example for a code editor</h1>
  <code-box>
    var msg = "Hello World";
    alert(msg);
  </code-box>
</body>
</html>
```