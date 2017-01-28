# vidsnarf

Helper script to easily snarf streaming web video in m3u8
playlists.  Pass a link to the m3u8 on the command-line and out.mkv will
fall out the other side.

Depends on gstreamer and several plugins, as well as mkvtoolnix.  All of
these packages are available via homebrew

* gst-libav
* gst-plugins-bad
* gst-plugins-base
* gst-plugins-good
* gst-plugins-ugly
* gstreamer
* mkvtoolnix

# TODO

* input validation, error checking, defensive programming, and all the other good practices presently ignored
* Figure out the actual minimum set of gstreamer plugins needed so this script doesn't require them ALL to be installed.


