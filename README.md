# GolabiJs
add features to jquery easily

[![jQuery version][jquery-version]](#)
[![download size][download-size]](#)

[jquery-version]: https://img.shields.io/badge/jQuery-1.0%2B-brightgreen.svg
[download-size]: https://img.shields.io/badge/download-1kb-brightgreen.svg

Requirements
------------
features requires the following to run:

  * [jQuery][jQuery] 1.0+


[jQuery]: https://jQuery.com/

Usage
-----

to put element in the center of page:
```js
$('#elm').center();
```

to put element in the center of a box element:
```js
$('#elm').center('#box');
```

convert english digit to persian digit:
```js
toPersianNum(1); //output: ۱
```

convert persian digit to english digit:
```js
toEnglishNum(۱); //output: 1
```

get url parameter:
```js
//url: http://www.example.com/?id=51&name=test
getUrlParameter('id'); //output: 51
getUrlParameter('name'); //output: test
```

get url parameter:
```js
formatBytes(51250000, 2); //output: 51.25 MB
formatBytes(51250000, 1); //output: 51.2 MB
```


License
-------
GolabiJs is licensed under the [MIT](#) license.  
Copyright &copy; 2018, Amirhossein Hashemi
