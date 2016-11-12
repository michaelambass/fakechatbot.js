# FakeChatBot.JS (1ko)

FakeChatBot.JS v.1.0 is a leightweight (1ko) jQuery plugin that allow you to simulate a chat conversation.

## Demo
![FakeChatBot.JS](https://media.giphy.com/media/l0MYKFw1eUIe5uXuM/giphy.gif)

## How to use
### Dependencies
FakeChatBot.JS need to have jQuery installed to work.

### CSS & JS files
``` html
<link rel="stylesheet" href="../src/fakechatbot.css" />
```

``` html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="../src/fakechatbot.js"></script>
```

### Usage
``` html
<div id="chatbot">
	<div class="fakechatbot-message" data-pause="1000"><strong>User:</strong> Hello</div>
	<div class="fakechatbot-message" data-pause="3000"><strong>Bot:</strong> Good morning! How can I help you?</div>
	<div class="fakechatbot-message" data-pause="2000"><strong>User:</strong> What's the weather today?</div>
	<div class="fakechatbot-message" data-pause="1000"><strong>Bot:</strong> Cloudy, +9°C in Geneva, Switzerland</div>
	<div class="fakechatbot-typing">is typing ...</div>
</div>

<script type="text/javascript">
$(document).ready(function(){

	// Initialize FakeChatBot.JS on #chatbot
	$('#chatbot').fakechatbot();

});
</script>
```

#### Pause beetween each interaction
You can use the data-param attribute __data-pause__ to set a delay beetween each communication (in miliseconds)

## Contribution
Pull requests are always welcome, but not all suggested features will get merged. Feel free to contact me if you have an idea for a feature.


## License

This plugin is available under [the MIT license](http://mths.be/mit).

## Author

The __FakeChatBot.JS__ plugin is written by Michael Ambass, aka @michaelambass

* [http://twitter.com/michaelambass](http://twitter.com/michaelambass)
