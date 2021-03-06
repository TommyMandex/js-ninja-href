# js-ninja-href

> Javascript native library to hide / cloak your real url link.

## Why
Really useful to hide your referral link. Get all your lost revenue, because some people don't want to use your referral link.

It will innocently show a clean url, but when the user click ( left , middle, right ) it will redirect them to somewhere else.

It use native javascript, no additional library like jQuery needed.

## Release Info

    Next version might completely hidden from the element ( not using data-ninja-url and data-ninja-target ) anymore.

## Install
Download and extract the .zip file: [download a ZIP](https://github.com/michaelhartomo/js-ninja-href/archive/master.zip)


## Setup
Include the script: ninja-href.min.js
```html
<script src="js/ninja-href.min.js"></script>
```

Now run the ninja-href function ( by default, it will listen to ninja-href class )
```js
    ninja_href(".ninja-href");
```

Set the link you want to hide / cloak just like this ( open in new window ):
```html
<a href="http://google.com/" class="ninja-href" data-ninja-url="http://frozenfire.us/" data-ninja-target="_blank"> Go to Google </a>
```

You can also open the link in current window :
```html
    <a href="https://tomplayer.top/" class="ninja-href" data-ninja-url="https://m.do.co/c/9072c848dc6e" data-ninja-target="_self"> TOP Charts 100 WORLD & 50 K-POP! </a>
```

Very useful to cloak referral link just like this :
```html
    <a href="https://google.com/free/RlJPWkVORklSRS1UT01QTEFZRVIuQVBQLU1JQ0hBRUxIQVJUT01PLkNPTQ==" class="ninja-href" data-ninja-url="https://m.do.co/c/9072c848dc6e" data-ninja-target="_self"> GET FREE 10 USD FOR SSD VPS HOSTING! ( You can use it for 2 months ) </a>
```

jsFiddle Example : https://jsfiddle.net/t5f7n7gL/1/
