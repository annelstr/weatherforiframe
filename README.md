I use those files to be able to insert an iframe into obsidian 
This workd across all my machines (winodws, linux, android)
I did no succes using an html local file

Iframe

```html
<a class="weatherwidget-io" href="https://forecast7.com/en/48d577d75/strasbourg/" data-label_1="STRASBOURG" data-label_2="WEATHER" data-font="Jura" data-theme="weather_one" >STRASBOURG WEATHER</a>
<script>
!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
</script>
```
