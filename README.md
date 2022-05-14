# Task 3 : Connecting esp32 to telegram
### What is Telegram?

Telegram is a cloud based instant messaging app. It has features like

* **End to End encryption :** - The communication is end to end encrypted only end users will be able to see the messages.

* **Self destructing messages :**- Secret messages can be configured to self-      destruct after a set period of time, making it even more secure.
*  **Ability to send large size files :**-Telegram supports file attachments up to 2 GB in size.
*  **Creating bots :**-Telegram bots are AI-based apps that can be configured      to serve many different functions, some examples would be like, send relevant information about the weather or useful news articles, some are preconfigured to send reminders, also there are some which can play tunes or create to-do lists, and so much more.

## Steps to create Telegram bot

*	Download telegram app from play store and install it.
*	Create your telegram account.
*	Search for “botfather”(botfather is a built-in bot that allows you to create and manage bots).
*	Click on start and press /newbot.
*	Then give your bot a name and username.
*	After creating bot, you will receive access token id which will be used to communicate with the bot.

## Steps to Telegram chat id
* Search for “idbot”.
* Start the conversation and press /getid.
*	You will receive your chat id.

## Procedure 
* Open arduino IDE and paste the code

    Code:https://github.com/bhooshan11/connecting-esp32-to-telegram/blob/main/task_3_code.ino
* Upload the code to Esp32.
*	Press enable/reset key, so the it starts connecting to wifi
*	Open telegram app.
*	Start conversation with your bot by the link provided by the botfather.
*	Type /start.
*	Bot will give you list of operations that can perform.
*	Select /led_on.
*	Built in led in esp32 will turn on.

## Errors

* I was not able to connect the telegram bot to esp32 as the telegram bot is not responding to any commands.
![this is an image](https://github.com/bhooshan11/connecting-esp32-to-telegram/blob/main/error%20photo.jpg)

## References

https://iotdesignpro.com/projects/telegram-bot-with-esp32-control-gpio-pins-through-telegram-chat 
