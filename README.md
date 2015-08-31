# Telegram-api-msg-bot
Shell Script to send messages to Telegram using BOT

# Install

<code>
git clone https://github.com/area31/Telegram-api-msg-bot.git
</code>

<code>
mv Telegram-api-msg-bot /opt
</code>

# Add to crontab

<code>
* * * * *     root    /opt/Telegram-api-msg-bot/send-msg-telegram msg
</code>


# Msg format

<code>
Time | MSG
</code>

Example:

<code>
22:40|Hora de dormir
4:20|virjes everywhere
</code>
