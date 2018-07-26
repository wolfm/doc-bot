# Doc Bot

## Setup

Create a `token.json` file with the following contents, using your own bot token:
``` json
{
    "token": "YOUR BOT TOKEN"
}
```
Make sure your bot token does not find its way onto this public Github repo!

## Usage

Doc quotes can be triggered with any of the trigger words in the quoteTriggers array in `botconfig.json` or by the /quote command. The command prefix ("/" by default) can be changed with the prefix variable in `botconfig.json`.

A "Moron!" shoutout can be triggered with any of the trigger words in the moronTriggers array in `botconfig.json`.