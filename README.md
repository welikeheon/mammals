# Mammals 

------
An Easiest way to get Random Nicknames
------

## TL;DR
A... Well.. I was need to generate nickname randomly in recent project. When if you use the package, you can help to get the random nickname.

## Installation
```
npm i --save mammals
```

## How to use it?
```javascript
const mammals = require('mammals')

// When you didn't give the parameters, It will be return KOREAN language, You can use ENGLISH TOO. (like this)
mammals.mammals('en');
// ==> African Elephant

// What's the purpose? Simply You can combine it like a google docs style :)
let anonymous_user = 'Anonymous ' + mammals.mammals('en')
console.log(anonymous_user)
// ==> 'Anonymous Bobcat'
```

## Supported Language

* Korean(default)
* English

## Need Help?
Do not hesitate and leave the issue :)