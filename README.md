# Telegram-api-msg-bot
Shell Script to send messages to Telegram using BOT

# Install

<code>
git clone https://github.com/area31/Telegram-api-msg-bot.git
</code>

<code>
mv Telegram-api-msg-bot /opt
</code>

# Configure your API KEY in file send-msg-telegram.conf

<pre>
DEBUG="0"
KEY="KEY HERE"
MSG_FILE="/opt/Telegram-api-msg-bot/msg.txt"
</pre>

* To debug, set 1 on $DEBUG


# Configure your alerts on correct format in file msg.txt

<code>
Time | MSG
</code>

Example:

<pre>
22:40|Hora de dormir
4:20|virjes everywhere
</pre>

# Add to crontab

<code> * * * * *     root    /opt/Telegram-api-msg-bot/send-msg-telegram msg</code>

