# tvmailbot

Visual trading bot for tradingview.com

## Requirements
It will be the best if you run this bot on a Linux server (VPS or dedicated)

## Installation
git clone https://github.com/314phagor/tvmailbot.git

## Configuration

Go tradingview.com -> profile settings -> private details -> specify work email box in SMS email field
Go bot.cfg in bot folder and specify your email credentials, telegram bot API keys, and exchanges API keys
After configuration start your bot 
$ python tvmailbot.py bot.cfg


## Usage
  -create an alert on tradingview.com
  -enable email-to-sms feature for this alert
  -add command to message textbox
 
Bot is monitoring email server and each time email received, the command in email body is parsed and the order to specified exchange is placed. After successful order placement bot sends you notification message. You can also send direct trading commands via telegram bot, too.
  
