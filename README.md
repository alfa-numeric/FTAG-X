# FTAG-X

A modloader for noone_FA's Fatty Text Adventure Game.

FTAG-X works by using Tweego's capability to decompile Twine games to convert FTAG-Twine into Twee3 source code, then programmatically modifying the source code to expose hook points for mods, applying user-supplied .twee files and re-compiling the game. It does NOT include FTAG-Twine, nor any of its source code or assets, to be license-compliant.

After conversation with Russ, it's agreed that FTAG-X is not infringing on his rights, however:

_**DO NOT ASK RUSS (noone_fa) FOR ANY HELP REGARDING FTAG-X OR ANY OTHER MODIFICATION TO FTAG.**_

This is not Russ's port of call, and the way FTAG-X handles FTAG's code makes it unrecognizable to him.

Modifications that utilize FTAG-X MUST NOT violate CC-BY-NC-ND 4.0, with respect to FTAG:

https://creativecommons.org/licenses/by-nc-nd/4.0/

The code for FTAG-X is shared under Creative Commons Attribution-NonCommercial-ShareAlike (CC-NC-SA) 4.0:

https://creativecommons.org/licenses/by-nc-sa/4.0/

The TL;DR of all this is:

- Don't use FTAG-X to make money.
- Don't use FTAG's assets or source code in your FTAG-X mods, as this is in violation of FTAG's license. In excess of caution, this includes code generated by Tweego from FTAG's game file.
- You may duplicate (download, fork, etc.) FTAG-X to develop or redistribute it, as long as its license terms are obeyed.

We hope that FTAG-X makes it possible to create the FTAG mod you desire without needing to violate these terms.

Also, FTAG-X packages Tweego, which is distributed under the BSD 2-Clause license, included in LICENSE.txt in the tweego folder.

## Usage

Using FTAG-X requires downloading a copy of the game from Itch.io. Russ currently doesn't have it set up to do this on its page, so the only way to do this is to log in to Itch's desktop app, add it to your Collection, and install it from the app.
This will be less annoying later, as Russ has told me he plans to provide the game in a downloadable format when it's more stable.

After you've obtained the game, download FTAG-X, and put the ftag folder _in_ the FTAG-X folder.
Put any mods _in separate folders_ in the MODS folder.
When done, your structure should look like this:

```text
FTAG-X/
....ftag/
........icon/
........images/
........index.html
....LOADER/
........etc/
....MODS/
........mods-here/
```

If you're on Linux or macOS, you'll need to replace the contents of LOADER/tweego with ones from [the version of Tweego for your OS.](https://www.motoslave.net/tweego/)
