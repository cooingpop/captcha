# captcha

#### Random captcha generator.

###### Initialization

- initialize CAPCHA.
```
var captcha;
$(function () {
    captcha = new CAPTCHA({
        selector: '#captcha',
        width: 350,
        height: 140,
        onSuccess: function () { alert('Correct!'); }
    });
});
```

###### Usages
- generate captcha code.
```
var result = captcha.generate({captcha-length});
var result = captcha.generate(5);

```