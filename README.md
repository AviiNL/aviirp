## About AviiRP

AviiRP is a discord bot that transforms a channel into a role playing experience.

Everyone starts out as "Unknown" until they create their first character with `!name <firstname> <lastname>`. Every message that is not a command will be removed and replaced by the bot with your first name or Unknown. You can also perform actions using `!me <action>` which will be replaced by **_FirstName|Unknown [action]_**, note the lack of a colon character. or you can use `!rp <action>` to add narrative, this is an italic message with no name.  
Text wrapped in doublequotes are interepreted as spoken within an `!me` or `!rp` command.

## Install

1.  [Add to server](https://discordapp.com/api/oauth2/authorize?client_id=438250098619580416&permissions=125968&scope=bot)
2.  Type `!story enable` in the channel you wish to activate the bot
3.  Type `!help` for an up to date list of allowed commands
4.  Give the AviiRP Role `Manage Channel` permission in the channel(s) of your story to be able to update the channel topic
5.  (Optional) Create a role that has `Manage Messages` for Game Masters to control `!story` and `!gm`
6.  (Optional) Deny the bot access to any other channel than the channel you want to play in
7.  (Optional) Change the nickname of the bot in your server to something that makes sense for your story (for example, Storyteller)

## Getting Started

When the bot has been enabled using `!story enable` you can supply the story with information using the other `!story` commands. You can set a title, summary, color, image and icon for the base story to set the mood. When you are finished setting all the parameters you can apply the changes to the story using `!story update`. Optionally you can add properties to the story using `!story property set <key> <value>`. For example to set a location for the story. `!story property set Location Downtown`  
An example story can be found [here](https://aviinl.github.io/aviirp/sample.html).

## Commands

**RuleCommands**  
!rules - Get a pm with the rules and guidelines that go with the story  

**rule**  
!rule add <text> - Add a new rule  
!rule remove <text> - Remove a rule (supply the beginning of the rule)  

**ActionCommands**  
!roll [dice=1d20] - Roll dice  

**AdminCommands**  
!clear - Clears the channel log  
!gm <text> - A message from a GM  
!whois <discriminator> - Find out who someone really is  

**HelpModule**  
!help - Show list of commands  

**CharacterCommands**  
!switch <name> - Switch to a different character (partial name allowed)  
!characters - Get a list of all your characters  

**PlayerCommands**  
!title <title> - Sets a title for your character.  
!name <firstname> [lastname=] - Create a new character with a name with an optional last name  
!perma [notify=False] - Delete your character  
!me <text> - Perform an action.  
!rp <text> - Perform an action without prepending name.  
!showid - Show your ID.  
!ooc <text> - Speak out of character  
!fix - Removes your last message  

**story**  
!story enable - Enable the bot in the current channel  
!story disable - Disable the bot in the current channel  
!story link <ChannelID> - Link a channels character database  
!story title <value> - Change the title  
!story summary <value> - Update the summary  
!story color <value> - Change the color  
!story icon <value> - Change the icon. Use "" to remove  
!story image <value> - Change the image. Use "" to remove  
!story update - Apply changes to the story card  

**property**  
!story property set <key> <value> - Set a property on the story card  
!story property remove <key> - Remove a property from the story card  

## Help

For questions join my discord [here](https://discord.gg/uTxXTVt)
