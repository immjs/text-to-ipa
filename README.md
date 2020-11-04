## Before reading
This is a customised fork of npm package text-to-ipa.
Please keep in mind, that the original author of this project is [Shukri Adams<surrsurus>](https://github.com/surrsurus)

# node-text-to-ipa

https://www.npmjs.com/package/text-to-ipa

NPM port of the amazing [text-to-ipa](https://github.com/surrsurus/text-to-ipa) project. 

## Use
```js
const TextToIPA = require('text-to-ipa');
TextToIPA.lookup('word'); // > wɚˈd
```
If your lookup call needs to respond immediately, you can explicitly load the built-in dictionary
```js
const TextToIPA = require('text-to-ipa');
TextToIPA.loadDict(); // blocking load

TextToIPA.lookup('word'); // > wɚˈd
```

The dictionary is loaded once only.
       
