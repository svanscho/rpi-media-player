# rpi-media-player
This compose file will start various media player services on the raspberry pi:
- [rpi-radio](http://github.com/svanscho/rpi-radio): an internet radio player
- [rpi-spotify](http://github.com/svanscho/rpi-spotify): spotify connect so you can play your spotify songs
- [rpi-shairport](http://github.com/svanscho/rpi-shairport): airplay service so you can play any sound from your mac/iphone

### Prerequisites
- a raspberry pi (tested on RPi3)
- docker (install with `curl -sSL https://get.docker.com | sh`)

### How to install
- `docker-compose up`

### Usage
#### rpi-radio
Visit `http://<rpi-address>` and e.g. add shortcut to your Android home screen. The app will be fullscreen and behave like a normal application.

#### rpi-spotify
- Play a song with spotify on your smartphone or mac
- Click on the spotify connect icon in your spotify player to cast the audio to your raspberry

#### rpi-shairport
- Play a song on your smartphone or mac
- Click on the airplay icon to cast the audio to your raspberry
