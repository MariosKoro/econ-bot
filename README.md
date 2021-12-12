![Logo](https://www.clipartmax.com/png/full/447-4472338_cash-clipart-cash-stack-stacks-of-money-clipart.png)

<div align="center">
  
<br>![Windows](https://github.com/danielkrupinski/Osiris/workflows/Windows/badge.svg?branch=master&event=push)
[![Downloads](https://img.shields.io/github/downloads/jagrosh/MusicBot/total.svg)](https://discord.gg/9ZrzNkzeN4)
[![Discord](https://discordapp.com/api/guilds/147698382092238848/widget.png)](https://dsc.gg/dst74)<br>
[![PayPal](https://img.shields.io/badge/donate-PayPal-104098.svg?style=plastic&logo=PayPal)](https://paypal.me/mrmotchy)
  
  </div>
  
  # Features
  * **Watch my YT video & host your [bot 24/7](https://dsc.gg/dst74)** 
  * addmoney, removemoney, balance, buy, daily, deposit, givemoney, inventory, leaderboard, rob, shop, use, weekly, withdraw, work


# 💎 Preview
## This it what the bot looks like...
![](https://github.com/mrmotchy/stuff/blob/main/Bild_2021-12-12_130955.png?raw=true)

![](https://github.com/mrmotchy/stuff/blob/main/1.PNG?raw=true)

# 🔩 Installation
## Create [TOKEN](https://discord.com/developers/)
```
$ under bot_token
```

## Create [prefix]()
```
$ server prefixes could be -; +; !; ?;...
```

# 💻 Code example
This is a simple example of code using this package.

```js
module.exports = {
        name: "addmoney",
        category: "economy",
        description: "Adds Money To A user",
        aliases: ["addcoins"],
        usage: "addmoney [mention | ID]",
        
    run: async (bot, message, args) => {
```
&
```js
            let timeEmbed = new MessageEmbed()
                .setColor("RED")
                .setDescription(`You Have Already Collected Your Weekly Reward\nCollect It Again In ${time.days} Days ${time.hours} Hours ${time.minutes} Minutes ${time.seconds} Seconds `);
            message.channel.send(timeEmbed)
        } else {
            let moneyEmbed = new MessageEmbed()
                .setColor("GREEN")
                .setDescription(`You've Collected Your weekly Reward Of **${amount}${emote.coin}**\n**Collect It Again After 7 Days**`)
                .setFooter("https://dsc.gg/dst74")
            message.channel.send(moneyEmbed)
            db.add(`money_${user.id}`, amount)
            db.set(`weekly_${user.id}`, Date.now())
```

<br/>



## Installation


 ### Click [here](https://www.youtube.com/channel/UCmkPzf-eAJsiuCh-5kz4Abw) to watch my YouTube video !
 ![](https://github.com/mrmotchy/stuff/blob/main/Bild_2021-06-14_181143.png?raw=true)


 ### Click [here](https://dsc.gg/dst74) to join my discord server !
 [![Setup](https://github.com/mrmotchy/stuff/blob/main/adada.gif?raw=true)](https://dsc.gg/dst74)

