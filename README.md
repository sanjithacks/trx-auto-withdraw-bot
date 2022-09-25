# tron-auto-withdraw-bot
Tron auto withdraw bot, tron sweeper bot

### <div align="center">I'm freelance developer 👨‍💻 working remotely since 2017 🚀</div>  
  
## Bot code written in Nodejs

## How it works?
- Bot was deployed and set on a cronjob for every minutes. When it found the trx balance > 2 trx. It transfer the whole amount to owner address.
- It calculate the multisign fee before transfer which is 1 trx. And if the wallet has enough bandwidth which is 337, the transfer fee will be only 1 trx.
- If wallet have not enough bandwith then 1 trx (for multisign) + 0.337 trx (as bandwidth) will be deducted as fee. 


- 🔭 I’m currently working on [Fiverr](https://www.fiverr.com/betrosmedia)
