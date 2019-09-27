**Inject a javascript code to existing dom**

```javascript
(function(d, script) {
    script = d.createElement('script');
    script.type = 'text/javascript';
    script.async = true;
    script.onload = function(){
        // remote script has loaded
    };
    script.src = 'https://cdn.jsdelivr.net/gh/krishnakumarvs/pseudo-code/api-call-pure-js.js';
    d.getElementsByTagName('head')[0].appendChild(script);
}(document));
```
