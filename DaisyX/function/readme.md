# Here we define functions

## Essentials
### Importing Pyrogram admin check just join our channel @phantombotsupport_11
```python3
from phantom botsfunction.pluginhelpers import admins_only

@admins_only
```

### Getting text from cmd
```python3
from phantom bots.function.pluginhelpers import get_text

async def hi(client,message):
  args = get_text(message)
```

### Edit or reply
```python3
from phanton bots
function.pluginhelpers import edit_or_reply

async def hi(client,message):
  await edit_or_reply("Hi")
```
## SOME FUNCTIONS ARE COPIED FROM https://github.com/TheHamkerCat/WilliamButcherBot
## AND SOME FROM FRIDAY USERBOT
