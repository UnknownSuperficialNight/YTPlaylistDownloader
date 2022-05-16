# YTPlaylistDownloader
download multiple youtube playlist and syncs them locally (allows age restricted videos)

keybindings:
arrow keys for up and down 
tab for cancel and ok

Dependencies:
yt-dlp: https://github.com/yt-dlp/yt-dlp

Usage:
when you first execute the script you must type in your format/codec 

supported file types are

aac,flac, mp3, m4a, opus, vorbis, wav, alac

next is the format dialog

the syntax is this

url
name

so copy and paste the url in then copy or type the name then repeat for any future playlists all of those are saved in the ytconfig.txt

menu options explained:

Download_all_NoRemove:
downloads playlist but if u add more songs to the playlist in the future it will only download the new songs leaving the old ones exactly where they were
saving space and download time

Download_all:
download playlist but if playlists exist already it will delete them and remake all songs within

Delete_config_and_all_urls:
deletes the ytconfig.txt folder only

Delete_config_and_all_urls_and_folders:
deletes the ytconfig.txt aswell as all folders u downloaded basically wiping everything like its fresh

Download_text_only:
just downloads a all playlists in .txt format

Download_with_browser:
if you are signed in with youtube it will be able to download age restricted videos otherwise the same as Download_all_NoRemove

Exit:
exit duh :)

you need to add your browser to be able to download with browser how do u do this make a text doc called cookies.txt in the same folder as the script inside the text doc on the first line type the name of your browser supported browsers are: brave, chrome, chromium, edge, firefox, opera, safari, vivaldi

anyway i made this in 4 hours because i was bored its my third script in bash hopefully you like it its 3:00 am i gotta head to bed night :)
