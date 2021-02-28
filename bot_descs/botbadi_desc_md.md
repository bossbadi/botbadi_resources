Botbadi is a multipurpose Discord bot that features commands in moderation, music, images, gaming, math and so much more. Type `%help` for all the commands and you'll be glad you did.

### Music
Let's start by talking about the music commands. Botbadi can search and play songs from YouTube and Spotify as well as file uploads and direct links to audio sources. Most of the classic music commands are here, but there may be bugs now and then.

`%join` Join your voice channel
`%play [Keywords]` Play from Keywords/URL/file upload
`%search [Keywords]` Perform a YouTube search

`%pause` Pause audio
`%resume` or `%unpause` Resume audio
`%stop` Stop audio

`%skip` Skip to the next song in queue if any
`%vol [Num]` Change volume/show current volume
`%np` Show the currently playing song

`%queue [Keywords]` Show the music queue/add song to queue
`%pop <Num>` Remove a song from the queue
`%clear` Clear the queue

`%leave` or `%disconnect` Disconnect from voice channel
`%debug` Attempt to debug the voice client
`%plugin` More neat features in my music commands

### Moderation
Next, let's take a look at the moderation commands. Although there are fewer commands than other moderation bots, the commands prove to be functioning and easy to use. The user parameter in many of these commands can be in the form of either a mention or the identification number (ID) of the user.

**No permission**
`%whois [User]` Display user information

**Manage messages permission**
`%set` Configure server settings including auto moderation
`%slow [Num] [s/m/h]` Set slowmode - max 6 hrs
`%dm <User> <Msg>` DM user through me

`%del [0-100] [User]` Delete channel messages
`%wipe <User>` Delete user history (100/channel)
`%rmr <MsgID>` Remove all reactions from a message

**Mute permission**
`%mute [User] [Reason]` Mute user/set up muted role
`%unmute <User> [Reason]` Unmute user

**Kick/Ban permission**
`%kick <User> [Reason]` Kick user
`%ban <User> [Reason]` Ban user/hack ban user
`%unban <User ID> [Reason]` Unban user
 
### Images
Similar to other popular Discord bots, Botbadi can manipulate images in various ways. Surprise your friends by adding filters, mods, and special effects to their profile pictures.

`%suck [User/URL]` Get sucked into a black hole at the center
`%swirl [User/URL]` Create a whirlpool effect by rotating the pixels
`%ripple [User/URL]` Create a ripple or wave effect with the image

`%carve [User/URL]` Carve the image on a gray surface
`%kuwahara [User/URL]` Add smoothing to reduce noise but preserve edges
`%spray [User/URL]` Give the image a spray-painted feel

`%edge [User/URL]` Detect edges on images with a simple convolution filter
`%burn [User/URL]` Burn the image like it just came out of the furnace
`%emboss [User/URL]` Generate a 3D print relief effect

`%sepia [User/URL]` Give the image a brownish tone just like the early days
`%noise [User/URL]` Add bits of color over the image
`%sketch [User/URL]` Make it look like an artist sketched it

`%png [Text]` Generate a PNG image with your text
`%triggered [User/URL]` Well someone is triggered (returns a GIF)
`%sharp [User/URL]` Sharpen up an image making it more vivid

`%jail [User/URL]` They broke the law. They pay the consequences.
`%rain [User/URL]` It's raining, very sad times indeed...
`%bright [User/URL]` Discord light theme flashbacks...oww my eyes!

`%dark [User/URL]` Turn the brightness down real low
`%invert [User/URL]` Invert the colors of an image
`%updown [User/URL]` Turn an image upside down, or 180 degrees

`%blur [User/URL]` Gaussian blur an image (basically blurring it)
`%pixel [User/URL]` Pixelate an image (like blurring but broader)
`%gray [User/URL]` Grayscale an image (I know, everyone's least favorite)

### Economy
Botbadi has a rather basic currency system, but many users find it addicting. Users can earn coins by completing tasks such as completing a typing challenge or solving a math problem and spend their earnings on cool items from the shop. This feature is still developing as more jobs and products are added.

`%bal [User]` Balance (do first if a new user)
`%inv [User]` Fetch someone's inventory

`%rich` Show richest users in the server
`%shop` Visit the shop to spend your coins

**Earning money**
`%bake` Bake something for `1-5 coins`
`%h.games` Any multiplayer for `10-20 coins`
`%h.math` Any math game for `20-30 coins`
`%type` or `%work` 20s typing game for `90-120 coins`

### General
Here are some general commands for the bot. These are mostly fun commands which might be useful at times.

`%snipe [Channel]` Last deleted msg in the channel
`%editsnipe [Channel]` Last edited msg in the channel
`%hack [User]` Hack someone (definitely not real)

`%emojify <Text>` Turn text into thick, blue emojis
`%ascii <Text>` Transform it into ascii-looking text
`%embed <Text>` Generate an embed with the text

`%say <Text>` Instantly repeat your message
`%change <Text>` Change server-wide message
`%talk` Repeat saved server-wide message

### Random
Next are the random commands. Random images, insults, predictions, you name it.

`%fact` Random interesting fact
`%8ball` Magic 8-Ball

**Classics**
`%flip` or `%coin` Flip a two-sided coin
`%roll` or `%dice` Roll a six-sided die
`%rand <Start> <End>` Random integer

**Images**
`%meme` Random meme
`%pet` Random pet image

**Insults**
`%flame` Insult your mom
`%roast` Insult you
`%insult` Random insult

### Math
If you're super into math and just can't get enough of it every day, well you're in luck. Botbadi has various math speedrun games so you can race your friends (if you have any). The built-in calculator feature comes in very handy when you can't find your normal calculator. Botbadi can compute arithmetic, trigonometry, logarithms, and some other stuff. It's a pretty smart calculator. Including the calculator feature, the bot can generate a graph given ordered pairs. I don't see a use for picking up your graphing calculator again, unless you're graphing an equation.

**The calculator**
`%calc <Problem>`
Compute a math problem. Example without algebra, just arithmetic
```%calc log(sqrt(7)) * abs(-1)```
**The plotter**
`%graph <Ordered pairs>`
Graph some points. Example comma-separated; spacing doesn't matter
```%graph (0 ,2) , ( 3,4), (5, 12 )```
**Games (20 coins/game)**
`%math` Random arithmetic game
`%add` Addition game
`%subt` Subtraction game

`%mult` Multiplication game
`%div` Division game
`%sqrt` Square root game

### And More
This bot also comes with a few multiplayer games to get your Discord servers up and running with guessing games focused on Minecraft items and celebrities. It also comes equipped with memes, jokes, and interesting facts to keep you entertained. It is the all-around bot that will add a little bit of everything to its servers. There were numerous other fun commands and features that weren't described in detail here and it's up to you to discover them!

If you are experiencing any issues, never hesitate to contact the developer:
Email: bossbadi123@gmail.com
Discord: [bossbadi#3371](https://discord.com/users/712323326575378562)
Support server: https://discord.gg/rzDqQqD