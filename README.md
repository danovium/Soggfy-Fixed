

# Soggfy-Fixed
This is my fork of Soggfy that separates contributing artists via a comma instead of anything else.
Additionally, this repo contains a few changes to be able to be built on GitHub Actions.

# Why?
When saving a song with multiple Artists, Soggfy would divide them differently based on what you were using.

In my case, I'm using iTunes and syncing my Library to my iPhone. The Artists are divided via a /.
Scrobbing on either Device lead to inaccurate last.fm info. As contributing Artists were counted as one instead of two. (ex. Drake/Future instead of Drake, Future).

That was obviously pretty annoying, so I spent about 2 hours editing the path-template so it will always divide them via a comma.

Now, of course, this means that other apps/devices may handle this differently, if you haven't had this issue on regular Soggfy, then you probably don't need this.

# Note
Every metadata OTHER than genres are included. This is because Soggfy would have to contact Spotify's API directly through your own app on the Developer Portal, which increases the chances of being banned. 

Something like getting info from last.fm or some other database could maybe be added in the future, but as of right now there are no plans to do so.

# Linux? macOS?
I honestly don't plan to port to either of those. As the creator said, it relies too much on the Windows API to be ported.

However, given that it acts like a Spicetify plugin of sorts, it isn't impossible.

Maybe sometime in the future I'll take a look at it, as of right now, this is Windows only. (Wine will not work)

## Alternatives
- [OnTheSpot](https://github.com/justin025/onthespot) - supports Linux, macOS and Windows. has a nice GUI
- [Zotify (DraftKinner Repo)](https://github.com/DraftKinner/zotify) - Zotify fork maintained by DraftKinner, Python script to download songs via a Terminal
- [Spotizer](https://lavaforge.org/spotizerr) - Download manager, meant for Media Servers, supports downloading from Deezer for FLACs
- [DAB Music Player](https://dab.yeet.su/) - Music Downloads, recommended for Mobile Users
- [Soulseek](https://www.slsknet.org/news/) - P2P platform for downloading music

  
Remember to support indie artists by buying their merch or simply donating, Spotify's payout isn't fair (0.0005$ per stream) but YOUR 5$ donation could equal to listening to their music over 1000 times. 


# Before Installing
Make sure that Real-time protection in Windows Security is turned off. Soggfy will still work even if you have it on, but the custom theme (and other stuff like blocking updates) won't work. 

Additionally, search will also be broken if it isn't disabled.

If you're wondering why, its simply due to how Soggfy modifies the appearance of Spotify itself. 

# Disclaimer
As with the original repo, this program should not be used to download music you don't physically or digitally own.

It is meant to showcase how music can be ripped from Spotify, without downloading them directly.

This fork also has the same risks of getting your account banned as the original one. Use an alt account or keep backups of your playlists.

