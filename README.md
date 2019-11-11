## cssreset
<p>
File: <strong>reset.css</strong><br>
Description: simple CSS reset, based on <br>
- <a href="//github.com/necolas/normalize.css" target="_blank" rel="nofollow">Normalize.css v8.0.1</a>, <br>
- <a href="//meyerweb.com/eric/tools/css/reset/" target="_blank" rel="nofollow">Reset v2.0-modified</a> <br>
and some browser hooks...
</p>

2019-11-10 *Update and minify*
  ```css
html,
body {height: 100%;}  
...
select::-ms-expand {display: none;}
select::-ms-value {color: currentColor;}
:-ms-input-placeholder, 
::-moz-placeholder, 
::-webkit-input-placeholder {color: rgba(0,0,0,.54);}
::-ms-reveal {display: none;}
...
:invalid,
:-moz-submit-invalid,
:-moz-ui-invalid {box-shadow:none;-moz-box-shadow: none;outline: none;border: none;}
...
[aria-hidden="false"][hidden] {display: initial;}
[aria-hidden="false"][hidden]:not(:focus) {clip: rect(0,0,0,0);position: absolute;}
```
TODO:
- [x] Pre-release may be done :simple_smile:
