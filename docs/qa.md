# Questions and Answers
## How to listen to internet radio from the command line?

In file: `.bashrc`

    alias radio.wfmu="mpv http://mp3stream.wfmu.org"
    alias radio.oe1="mpv mms://apasf.apa.at/oe1_live_worldwide"
    alias radio.fm4="mpv http://mp3stream1.apasf.apa.at:8000/"
    alias radio.o94="mpv http://orange-01.live.sil.at:8000"
    alias radio.88vier="mpv http://ice.rosebud-media.de:8000/88vier"
    alias radio.dradio="mpv http://dradio-ogg-dlf-l.akacast.akamaistream.net/7/629/135496/v1/gnl.akacast.akamaistream.net/dradio_ogg_dlf_l"
    alias radio.funkhauseuropa="mpv http://fhe-ogg.akacast.akamaistream.net/7/933/199785/v1/gnl.akacast.akamaistream.net/fhe-ogg"
    alias radio.fluxfm="mpv http://fluxfm.hoerradar.de/fluxfm-berlin"
    alias tv.arte="(firefox http://www.arte.tv/guide/de/live > /dev/null 2>&1) &"

check if mpv (the successor of mplayer) is installed, if not, replace
mpv with mplayer, that's most certainly available.
