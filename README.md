# Slay the Spire Preferences

I have played some [Slay the Spire](https://store.steampowered.com/app/646570/Slay_the_Spire/) on iPad, but when I recently got it on Steam, naturally it did not have my progress there. I went looking for a way to modify the save files manually. As they are in `JSON` format, it's pretty straightforward, thank god. I did not find a complete or even good resource for them online though, so this is my attempt to assemble the preference files to unlock everything.

In their current state, the save files unlock *a lot*, but not everything, since I had to guess many of the card names/keys.  
~~If somebody wants to contribute, I'm happy to accept! A few cards of the card collection are missing, as well as a decent chunk of seen relics.~~  
(Update: Reddit user [neon-kitten](https://www.reddit.com/user/neon-kitten/) provided me with the files for seen cards and relics! Thanks!)

If you would like to apply this to your copy, take note that I used version `2.2` of the game.

For macOS the files are located in  
`~/Library/Application Support/Steam/SteamApps/common/SlayTheSpire/SlayTheSpire.app/Contents/Resources/preferences`

For Windows the files are in  
`\Steam\steamapps\common\SlayTheSpire\preferences` (I believe)

But you can easily get to them if you do:  
**In Steam:** Library > *Right click on* Slay the Spire > Preferences > Local files > Browse Local Files …

You should probably change your `alias` in [STSPlayer](/STSPlayer#L2) to your actual alias or something custom.

I'm still looking for the correct value to enable Beta card art, so if anybody knows, I'd be thankful.
