# message.js 
free jquery plugin to display a message at the top of the browser

### Features
- Easy to use
- Fully Resonsive
- 4 types of messages
- Cross-browser compatible
- Automatic closing message
- Callback function
- Lightweight
- Only 8 KB

### How to use?
This plugin is very easy to use!
#### Call the plugin
1. Download this plugin
2. This plugin put into your project folder
3. Call the plugin in your project file
```html
<head>
...
<!-- requires jquery version 1.7.x or higher -->
<script src="path-to-jquery/jquery.min.js"></script>

<!-- requires font-awesome -->
<link href="path-to-font-awesome/css/font-awesome.min.css" rel="stylesheet">

<!-- message.js -->
<script src="path-to-message-js/message.js"></script>
<link href="path-to-message-js/message.css" rel="stylesheet">
...
</head>
```
#### Create a new message
```javascript
message({
  id: "my_message",
  text: "i am a string",
  type: "info", // error, success, warning, info
  autohide: true, // default is true
  hide: function(){ // callback function when the message is closed
    alert("the message is closed");
  }
})
```

### About
#### Author
@author Muhamad Nauval Azhar<br>
@link http://www.nauvalazhar.net<br>
@version 1.0.0
#### License
[Please click here!](https://github.com/nauvalazhar/message.js/blob/master/LICENSE)
