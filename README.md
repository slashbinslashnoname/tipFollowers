# tipFollowers 

tipFollowers is a nodejs based twitter bot that send every followers of a given Screen Name (ie @itsnotan3rror) a given amount of bitcoins via the @changeTip bot.

Basically, it is a bot that sends a fixed amount of true money (yay) to all your followers.

## Usage

* Unpack tipFollowers on a working directory of a computer where [NodeJs](https://nodejs.org) is installed.
* Install twitter's package for nodeJs

      npm install twitter
      
* Specify your message by replacing the _tipFollowers.message_ variable.
* There is also some vars that you need to adjust, especially _tipFollowers.amount_ which is the amount you want to spread. 
* Put enough money on [ChangeTip](https://www.changetip.com)
* Launch it via

      node tipFollowers.js
    
Have a great tipping christmas !



-- _SlashBinSlashNoname_ - base64_decode(c2xhc2hiaW5zbGFzaG5vbmFtZQ==)@gmail.com