code-editor
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
  <h1>Examples for a code editor</h1>
  <h2>Hardcoded source (editable)</h2>
  <code-editor mode="javascript">
    var msg = "Hello World";
    alert(msg);
  </code-editor>

  <h2>Source loaded from a file</h2>
  <code-editor src="http://components.geekonaut.de/code-editor/code-editor.html" mode="htmlmixed"></code-editor>

  <h2>Using a different theme</h2>
  <code-editor theme="monokai" mode="ruby">puts "Hi"</code-editor>

  <h2>Setting the content from a string</h2>
  <code-editor id="editor" mode="css"></code-editor>
  <script>document.getElementById("editor").srcText = "html, body { height: 100%; }"</script>
</body>
</html>
```