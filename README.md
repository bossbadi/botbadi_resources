You are looking at the privacy policy for botbadi, a Discord bot by bossbadi. By having botbadi in your server, you agree to the following privacy policies:

### What information is stored?
Discord data collected from the bot:
* When a message is deleted and/or edited, the **author and contents** of the message are logged.
* When a message is sent, the **server, channel, author, and contents** of the message are logged.
* The **user ID** of anyone who creates an account in this application is logged.
* The **server ID** of anyone who configures server settings in this application is logged.

### Why is this data collected?
Whenever a message is deleted, the message contents and the author of the message are stored somewhere in a dictionary for that specific channel in the server. If there was a previous message deleted in that channel, it will be replaced with this newly deleted message. The reason is for the `snipe` command in the bot. This is especially useful when a user ghost pings another user. The pinged user can run the `snipe` command and the last deleted message in that channel will appear if any. The same holds for storing recently edited messages for the `editsnipe` command. If servers are uncomfortable with message sniping, there is a toggle in the bot settings which will toggle message sniping on and off which can be done using the `set` command. 

The reason certain data is logged when a message is sent is so the developer can see the usage and reach the bot gets. This can help the developer have a better understanding of which commands are malfunctioning and which can be improved. For example, the developer can see which commands users are running in this bot and their reactions to the commands. While a user is listening to music being played by the bot, they could complain that the music quality is lower than expected or it might be choppy. When the developer notices more users complaining about an issue, He will know that something needs to be fixed and will get to it right away. This means less frustration for the people using the bot as bugs and errors are quickly detected and fixed right away.

When a user creates an account for this application, their Discord ID is stored in a database. The ID is a reliable way of identification for the user. A user creates an account to access most of the economy commands in this application. Stuff like the user's money and the items in their inventory are stored in the database. Their bot settings are also stored.

The same holds for servers, with the server ID stored. This application has a few auto-moderation features which should be toggled in the server settings (using the `set` command).

### How long is this data stored?
Temporary data stored in cache:
* The author and contents of edited and/or deleted messages
* The server, channel, author, and contents of newly sent messages

Permanent data stored in the database:
* The IDs of users who created accounts for the economy/user settings in the bot
* The IDs of servers that have settings such as auto-moderation configured for the bot

### Who can see my data?
* Your recently edited/deleted messages can be seen by members in your server by running the `snipe` and `editsnipe` commands.

* If you registered for an account using the `bal` command, members in your server can see your balance and inventory in the economy system of the bot by invoking the corresponding commands.

The developer does not sell or release your name and/or messages to the public in any way, however, if the developer decides to share certain data from command usage, it will remain anonymous, unless stated otherwise.

### Can I remove my data?
If a user or a server admin would like their data removed from the database, they will first contact the developer with their concerns. This can be done through email or Discord itself. Then, the developer will do a search in the database for said user/server. If any rows contain the user or server's ID, whichever they want to be removed, the developer will simply delete that row in the database. It's as simple as that.

If you are concerned about the data stored, join the support server or contact the developer.
> **Note:** The developer reserves the right to change this policy at any time with or without notice.