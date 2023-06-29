#[Listen Your Papa Amir HeRe]

## Important !

This package is Made By Jordan Ka Papa AmiR JusT FeeL LoRo and EnjoY PaPa ka FCA 😌🤞🍬

## Notification !
If you are facing any error then contact me on Facebook Or Whatsapp.👇👇
https://www.facebook.com/F4R3BII.AMIR
whatsapp= +923477034310

This is Original Project

Made By Mr Amir(29/06/2023)

## Support For : 

+ Support English, VietNamese !,
+ All bot if using listenMqtt first.

# Api ChatBot Messenger

```bash
npm i fca-amir-farebii
```
or
```bash
npm install fca-amir-farebii
```

It Will Load Into node_modules (Your Lib) - Note Replit Won't Show Where to Find 😪 from English

How To Update:
```bash
npm install fca-amir-farebii@latest
```Or
```bash
npm i fca-amir-farebii@latest
```



## Using

```javascript
const login = require("fca-amir-farebii"); // get from lib

// log in
login({email: "Gmail Account", password: "Your Facebook Password"}, (err, api) => {

     if(err) return console.error(err); // error case

     // create bots that automatically copy you:
     api.listenMqtt((err, message) => {
         api.sendMessage(message.body, message.threadID);
     });

});
```

As a result, it will copy you as shown below:
<img width="517" alt="screen shot 2016-11-04 at 14 36 00" src="https://cloud.githubusercontent.com/assets/4534692/20023545/f8c24130-a29d-11e6-9ef7-47568bdbc1f2.png">

If You Want Advanced Use Then Use The Bots Listed Above!

## List

You Can Read Full Api At => [here](DOCS.md).

## Install For Mirai:

You Need To Go To Mirai.js File, Then Find The Line
```js
     var login = require('depending on bot');
     /* Maybe :
         var login = require('fca-horizon');
\\Etc
     ...
     */
```

And Replace It With:

```js
     var login = require('fca-amir-farebii')
```

Then Run As Normal!


------------------------------------

### Save Login Information.

To Save You Need 1 Apstate Type (Cookie, etc,..) To Save Or Use Login Code As Above To Login !

And This Mode Is Available In Some Bots In Vietnam So You Can Rest assured!

__Instructions With Appstate__

```js
const fs = require("fs");
const login = require("fca-amir-farebii");

var credentials = {email: "FB_EMAIL", password: "FB_PASSWORD"}; // info tk

login(credentials, (err, api) => {
     if(err) return console.error(err);
     // log in
     fs.writeFileSync('appstate.json', JSON.stringify(api.getAppState(), null,'\t')); //create appstate
});
```

Or Easier (Professional) You Can Use => [c3c-fbstate](https://github.com/c3cbot/c3c-fbstate) To Get Fbstate And Rename To Apstate Also ! (appstate.json)
------------------------------------

## FAQS

FAQS => Koi LinK Ni Hai BabY DaFa Ho Jao 😌🤞
