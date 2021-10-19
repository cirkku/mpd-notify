# mpd-notify
Provides song covers to notify based on currently playing track in mpd.

## Usage
1. clone the script with `git clone https://github.com/cirkku/mpd-notify` optionally adding the output path as an argument to the end.
2. chmod +x the script to make sure its executable.
3. set the script to execute on song change, for example in ncmpcpp config with the option: `execute_on_song_change="/path/to/script/`, or you can use other software such as [mpd_trigger](https://github.com/Determinant/mpd_trigger) to send the notification even without your music player running in the background.

## Example (yes, my font is bad, no, I wont fix it)
<p align="center">
  <img src="example.png">
</p>
