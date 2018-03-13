# tvmailbot

### Visual trading bot for tradingview.com

Bot is monitoring email server and each time email received, the command in email body is parsed and the order to specified exchange is placed. After successful order placement bot sends you notification message. You can also send direct trading commands via email, too.

## Requirements
It will be the best if you run this bot on a Linux server (VPS or dedicated)

## Installation
$ git clone https://github.com/314phagor/tvmailbot.git

## Configuration

* Go tradingview.com -> profile settings -> private details -> specify work email box in SMS email field
* Copy config file $ cp config.py.sample config.py
* Edit config.py: specify your email, telegram API and exchanges API credentials
* After configuration start your bot $ python tvmailbot.py config.py


## Usage
* Create an alert on tradingview.com
* Enable email-to-sms feature for this alert
* Put trading command to message textbox
 

