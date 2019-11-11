## cssreset

File: **reset.css**
Description: *simple CSS reset, based on*
- [Normalize v8.0.1](github.com/necolas/normalize.css)
- [CSS Reset v2.0-modified](meyerweb.com/eric/tools/css/reset)
*and some browser hooks...*


2019-11-10 *Update and add minified version*
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
- [x] Pre-release may be done  :smirk:
- [x] Add minified version *reset.min.css*  
