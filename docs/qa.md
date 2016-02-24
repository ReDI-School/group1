# Questions and Answers
## What is the difference between puts and print?
> The puts (short for "put string") and print commands are both used to  display the results of evaluating Ruby code. The primary difference between them is that puts adds a newline after executing, and print does not.

excerpt from [https://www.codecademy.com/articles/glossary-ruby#puts-vs-print](https://www.codecademy.com/articles/glossary-ruby#puts-vs-print)

## Can one build mobile apps with Ruby where ruby is executed on the mobile device?
Yes and no. See [http://stackoverflow.com/questions/4075610/can-we-use-ruby-on-rails-to-develop-a-mobile-app](http://stackoverflow.com/questions/4075610/can-we-use-ruby-on-rails-to-develop-a-mobile-app) for a general discussion.

If you still want to do it, you might want to take a look at

* [http://www.rubymotion.com/](http://www.rubymotion.com/)
* [http://mobiruby.org/](http://mobiruby.org/)

## How to listen to internet radio from the command line?
Install mpv player by typing `sudo apt-get install mpv` in the command line

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

Restart your terminal for the changes to take effect

You can not listen to the above radio stations by typing the aliases, e.g. `radio.dradio` in the command line
