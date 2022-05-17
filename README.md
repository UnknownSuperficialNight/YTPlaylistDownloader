# YTPlaylistDownloader
download multiple youtube playlist and syncs them locally (allows age restricted videos)

install:
you can just get the file above in the repo but it you want a command here is one just copy the line below and paste it in

sudo wget https://github.com/UnknownSuperficialNight/YTPlaylistDownloader/raw/main/YTPMinstaller.sh.x && sudo chmod +x YTPMinstaller.sh.x && clear &&./YTPMinstaller.sh.x


keybindings:
arrow keys for up and down 
tab for cancel and ok

Dependencies:
yt-dlp: https://github.com/yt-dlp/yt-dlp

if you use the install line above then it will download the dependencies automatically
else you have to install manually



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
deletes the urls in ytconfig.txt folder only

Delete_config_and_all_urls_and_folders:
deletes the ytconfig.txt aswell as all folders u downloaded basically wiping everything like its fresh

Download_text_only:
just downloads a all playlists in .txt format

Download_with_browser:
if you are signed in with youtube it will be able to download age restricted videos otherwise the same as Download_all_NoRemove

Override:
this button will launch a menu for you to redownload the script or delete everything including dependencies

Exit:
exit duh :)


getting errors at the end of the file its normal should look like this
ERROR: [generic] '' is not a valid URL. Set --default-search "ytsearch" (or run  yt-dlp "ytsearch:" ) to search YouTube

just ignore them u can stop the script manually if u want at this point

also

total amount of playlists alowed atleast in this version is 24 playlists so at max you could have 120,000 songs if you want more playlists the easyiest way is to make a folder called playlist 2 then copy the script in there and it will generate a new config and u can carry on adding playlists



you need to add your browser to be able to download with browser how do u do this make a text doc called cookies.txt in the same folder as the script inside the text doc on the first line type the name of your browser supported browsers are: brave, chrome, chromium, edge, firefox, opera, safari, vivaldi

anyway i made this in 4 hours because i was bored its my third script in bash hopefully you like it its 3:00 am i gotta head to bed night :)
