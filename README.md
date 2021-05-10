## Features
Currently the robot automatically connects to the server, and DMs any new users added while the bot is active.
The terminal will recieve various pieces of information on the channel the bot has joined, including name of the server, the owner of the server, and a few other details.

## Future Development
Here is a tennative list of functionality I want:

- Ability to auto play music similar to the GRoovy bot.
- Automatic & Timed anouncements
- Integration with a twitch channel to send anouncements
- Some fun image processing functions (for the memes)
- general moderation quality of life feautres (similar to the current bot commands)

If anyone thinks of anything else let me know and I'll add it. Anyone is free to contribute, just make a PR.

## Command List
### Each command must be used with the prefix '$', so the bot will recognize the message as a command.
### (Parentheses show what information, if any, to give to a command (Brackets mean that that argument is not required by the command.))
 
 - makechannel (makechannel [channel]) -> Creates a text channel with the given name.

 - translate (translate msg [lang]) -> Translates the message to the specified language, defaults to French.

 - ban_word (ban_word word) -> Adds a word to the server's current list of banned words.

 - timeout (timeout minutes) -> Puts a user in a timed-out state, effectively issuing a temporary ban without removing them from the server.

 - kick (kick user [reason]) -> Removes a user from the server. They may join back.

 - ban (ban user [reason]) -> Bans a user from the server.
