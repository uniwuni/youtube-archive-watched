# dl-vids
This is a tool you can use to automatically archive your watched YouTube videos every now and then.

# Dependencies
Requires yt-dlp and some sort of cookie export extension for your browser, I use cookies.txt.

# Usage
Declare some archive directory `DIR`. Export the YouTube cookies to a cookie.txt file located in `$DIR`. For a while, I only had to refresh
that file once every few weeks, but now it seems to be required to be regenerated after every run.
To download the last 100 watched videos while avoiding duplicates, run `dl-vids $DIR`. I download in 720p to avoid using too much storage
while still keeping the videos at a watchable quality.

