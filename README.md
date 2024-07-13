<p align="center">
  <img src="https://i.xno.dev/GCi74.png" />
</p>

# About

Billy is a no nonsense audio player that allows you to quickly play an entire directory of MP3 files. Version 1.04k.

# What can it do?

Billy can play WAV, MP3, OGG, and FLAC files. It can usually load entire directories of MP3 files 2 to 8 times faster than winamp or media player. Billy plays music albums without any gaps 
between tracks, so an overlapping applause or beat will continue. The player is 100% controllable by keyboard and its easy finder and special rename functions help you to find and organize your files quickly.

# How to use?

It's practical to have a main music folder where your music files are located. In that folder you can create subfolders containing your artists and/or albums. To load your music files to your playlist, hit `[F4]` and select the folder of your choice.

Press `[Enter]` on a file in your playlist to play. Press `[Space]` to stop. You can drag the files into your preferred order. You can also change the playmode (ie. to shuffle) with `[ctrl + m]`.

Files are displayed as filenames. Most music players visualize music files with embedded tags. It take ages to load these tag-files, therefore Billy doesn't support tags. No need to worry! Hit `[F2]` to rename a file directly from your playlist. In order to view your playlist with its parent (sub)folders (which could be the artist and album name), try hitting `[F8]`.

If you are somewhat experienced with playing your music with Billy, you might want to organize your music collection. Everyone has his own way to do this, but Billy has a unique multiple filename replacer, which can rename entire albums with a single click. Select the multiple files and hit `[F2]`.

It's easy to find a file in your collection. Add all your files to the playlist and type a part of the name of the song or album you are looking for. The easy finder pops up with the found results. Select the file you want to play, and hit `[Enter]`.

# Tips

Pressing `F5` checks the playlist for new/removed files. This can be very useful when you are downloading songs and want to check if they're completed. If so, they will be added to the list (according filedate, so you can find them easily).

Pressing `[ctrl + del]` (crop) while having a playlist with queued items, gives a playlist with only the queued items.

Pressing `[F2]` (File info) on multiple files, launches the multiple filename replacer. Use this to rename entire albums with a click.

Use the `[~]` key (above the tab key) to jump to the currently playing song.

Hit the `[pause]` key on your keyboard (right upper key), to lower the volume with 30%, which can be useful if you receive a telephone conversation and quicly want to lower the volume. The coolest thing: this hotkey always works, even when Billy is minimized and you're working inside another application. Hit `[alt + pause]` to go to the next song, this also works globally.

Hit `[ctrl + space]` if you don't trust your sound. Billy will maximize your windows mixer, unmutes the wave channel and resets panning.

# Frequently Asked Questions

__Can Billy play radio stations or video files?__

Billy is meant to play audio, not video. I am working on a small simple dedicated Billy radio version too, which will be in the Billy package. I used to have the radio and mp3 player in one, but I decide to split them up in two different applications to stay small, dedicated and fast! :)

__Where are the MP3 tags?__

Billy intentionally doesn't show MP3 tags for songs. Read why.

__I've installed Billy and I also have winamp on my system. At first my MP3 files opened in Billy, but after a while winamp is opening them. How do I get Billy to open them again?__

Probably winamp is claiming them back at start-up. Unselect the MP3 association in winamp. Re-check the MP3 association in Billy settings.

__How to get rid of the tiny Billy if I double click a file?__

Go to the Billy settings and change the 'Double click a file in Explorer' option to 'Enqueue in playlist mode'.

__I don't hear anything while playing with Billy__

1. Make sure your Billy volume is at 100%
2. Press [ctrl + space]
3. Install latest DirectX and soundcard drivers.

__How do I change the volume?__

Drag the 100% sign up and down or use the numpad - and + keys.

__I want to install a newer version, what should I do?__

Just install the new one over the old one. Your settings will be kept.

__What are Billy's known minimum system requirements?__

- 133MHz Pentium I or comparable
- 32MB RAM
- 1MB Hard Disk Space
- 16bit Sound Card
- Windows 98
- DirectX 3

If you have an older system, ~~mail me~~ too bad.

__Billy is kind of gay. Where are the skins?__

Billy will stay skinless. You can modify the playlist colors, font type and font size though, see the Tweak section of this documentation.

__What's the difference between opening a folder and a favourite?__

Favourites are static, which means that the playlist is saved exactly like you saved it. Track order is saved. Any unfound files will stay in the list. Opening a folder is dynamic, it just builds a playlist based on the files found and the default sorting setting.

__Winamp and almost every other player have the time of the songs in a column next to the title. Why doesn't Billy have that?__

It would lower the performance of Billy dramatically since every single file in the list has to be read. You can always select a few songs and press `[ctrl + t]`.

__If I choose the 14 LED level meter, my volume indicator disappears. Where did it go?__

Good question :) click on the dB indicator and drag your volume to your desire. Why? If you know a proper way to place the volume in Billy, please mail me, because we couldn't find a good place, and most advanced users who use the 14 led, don't need volume and want pure 100% sound.

__How can I always start Billy with an empty playlist?__

Clear your playlist.txt and make it read-only.

__Does Billy support Surround Sound in 4.1 or 5.1 outputs?__

Yes though not tested yet. The level meters are two channels only.

__Can Billy handle any Winamp visualization plugins?__

No, but maybe in the future.

__The favorites order changes every time I add a new one. How can I stop this and keep my hotkeys?__

Rename your favorites with a number prefix since they are sorted alphabetically. For example:
    
    01 - Radiohead
    02 - Muse
    03 - Placebo

__Any plans for Linux or the Mac?__

The sound engine I use is Bass. Which doesn't support Linux or Mac. Therefore I am stuck to that limitation.

# Credits

|Function|Credit|
|:--|:--|
|Author|Sanne Schaap|
|Artwork, concept and testing|Emiel de Jager|
|Level meters algorithm & calibration|Gert-Jan Wiersema|
|Support & code portions| Laurenz van Gaalen|
|Sound engine and decoder|Bass by Ian Luck (un4seen)|
|Installer|InnoSetup by Jordan Russel|
|Program Compression|StripReloc by Jordan Russel|
|Parts of TCoolTray|Troel Jakobsen|
|Many tips|Peter Below|
|Beta testing|Sammy Dirksz, Henk Schaap, Frouke van Es, Ivo van Boxmeer|

# Contact
> [!IMPORTANT]
This repository acts as a mirror for billy--my favorite open source music player. The developer has stopped development on this media player. It supports most common music filetypes including FLAC. However, if you wish to you can try to contact the developer at:

    Email 2004@sheepproductions.com

This repository will not be updated or maintained. I do not offer support.
