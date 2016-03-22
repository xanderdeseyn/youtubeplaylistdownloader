#Youtube Playlist Downloader

To install, simply execute `ytdlscript` in a terminal (with sudo)

1. install FFMPEG
2. download youtube-dl and set it up in /usr/local/bin
3. download Mp3Utils and set it up in /opt/mp3utils
4. install `downloadplaylist` script in /usr/local/bin

You can now run with the simple command `downloadplaylist`.

It expects 3 parameters: playlist, start number, end number.

example:

`downloadplaylist https://www.youtube.com/playlist?list=LLNtNg8lQXL7Oo0fMLFq8X-A 1 100`
