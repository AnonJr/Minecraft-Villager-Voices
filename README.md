# Custom Villager Sounds
I wanted to get into building Data and Resource Packs for Minecraft, this is the first entry with a simple sound change on the villagers. Looking at the [Wiki page](https://minecraft.gamepedia.com/Villager), there are a few sounds to put together:

Sound Event | Sound Used | Subtitle | Subtitle ID | My Take
----- | -------- | ------------- | --------------- | -------
`entity.villager.ambient` | idle1.ogg | Villager mumbles | `subtitles.entity.villager.ambient` | "Hello"
`entity.villager.ambient` | idle2.ogg | Villager mumbles | `subtitles.entity.villager.ambient` | "How *you* doin?"
`entity.villager.ambient` | idle3.ogg | Villager mumbles | `subtitles.entity.villager.ambient` | "Hi"
`entity.villager.celebrate` | ???.ogg | Villager cheers | `subtitles.entity.villager.celebrate` | "?"
`entity.villager.celebrate` | ???.ogg | Villager cheers | `subtitles.entity.villager.celebrate` | "?"
`entity.villager.celebrate` | ???.ogg | Villager cheers | `subtitles.entity.villager.celebrate` | "?"
`entity.villager.death` | death.ogg | Villager dies | `subtitles.entity.villager.death` | "Avenge me"
`entity.villager.hurt` | hit1.ogg | Villager hurts | `subtitles.entity.villager.hurt` | "Owww"
`entity.villager.hurt` | hit2.ogg | Villager hurts | `subtitles.entity.villager.hurt` | "That's not a tickle"
`entity.villager.hurt` | hit3.ogg | Villager hurts | `subtitles.entity.villager.hurt` | "ooff"
`entity.villager.hurt` | hit4.ogg | Villager hurts | `subtitles.entity.villager.hurt` | "Engggghhhh"
`entity.villager.no` | no1.ogg | Villager disagrees | `subtitles.entity.villager.no` | "Oh no&hellip;"
`entity.villager.no` | no2.ogg | Villager disagrees | `subtitles.entity.villager.no` | "Nah"
`entity.villager.no` | no3.ogg | Villager disagrees | `subtitles.entity.villager.no` | "That's a no"
`entity.villager.trade` | haggle1.ogg | Villager trades | `subtitles.entity.villager.trading` | "Sure"
`entity.villager.trade` | haggle2.ogg | Villager trades | `subtitles.entity.villager.trading` | "I'll take it"
`entity.villager.trade` | haggle3.ogg | Villager trades | `subtitles.entity.villager.trading` | "Looks good to me"
`entity.villager.yes` | yes1.ogg | Villager agrees | `subtitles.entity.villager.yes` | "Oh yeah&hellip;"
`entity.villager.yes` | yes2.ogg | Villager agrees | `subtitles.entity.villager.yes` | "Yeah"
`entity.villager.yes` | yes3.ogg | Villager agrees | `subtitles.entity.villager.yes` | "That's a yes"

*???.ogg - It really looks like "Celebrate" uses the same sound files as "Yes", but the playable files on the wiki page have an accept#.ogg for the playable files. Not going to mess with it too much until I get the rest of the sounds set.

All files are 44.1kHz mono, recorded in [Audacity](https://www.audacityteam.org/). I added a little bass and echo in [VoiceMeeter](https://www.vb-audio.com/Voicemeeter/banana.htm) while doing the recording, and used a pitch shift plug-in to further alter the voice so it sounds less "me". The full Audacity project is in the `.resources` folder.

# Install
You should be able to get the latest release and add the `.zip` file like you would any other resource pack.