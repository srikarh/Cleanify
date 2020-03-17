# Cleanify
 Attempt at keyword recognition and transcription of audio using PocketSphinx and REPET.

[![Build Status](http://img.shields.io/travis/badges/badgerbadgerbadger.svg?style=flat-square)](https://travis-ci.org/badges/badgerbadgerbadger) [![Dependency Status](http://img.shields.io/gemnasium/badges/badgerbadgerbadger.svg?style=flat-square)](https://gemnasium.com/badges/badgerbadgerbadger) [![Coverage Status](http://img.shields.io/coveralls/badges/badgerbadgerbadger.svg?style=flat-square)](https://coveralls.io/r/badges/badgerbadgerbadger) [![Code Climate](http://img.shields.io/codeclimate/github/badges/badgerbadgerbadger.svg?style=flat-square)](https://codeclimate.com/github/badges/badgerbadgerbadger) [![Github Issues](http://githubbadges.herokuapp.com/badges/badgerbadgerbadger/issues.svg?style=flat-square)](https://github.com/badges/badgerbadgerbadger/issues) [![Pending Pull-Requests](http://githubbadges.herokuapp.com/badges/badgerbadgerbadger/pulls.svg?style=flat-square)](https://github.com/badges/badgerbadgerbadger/pulls) [![Gem Version](http://img.shields.io/gem/v/badgerbadgerbadger.svg?style=flat-square)](https://rubygems.org/gems/badgerbadgerbadger) [![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org) [![Badges](http://img.shields.io/:badges-9/9-ff6799.svg?style=flat-square)](https://github.com/badges/badgerbadgerbadger)

### Setup

> Install required packages using pip

```shell
$ pip install numpy
$ pip install matplotlib
$ pip install librosa
$ pip install soundfile
$ pip install mutagen
$ pip install mp3_tagger
$ pip install azapi
$ pip install speech_recognition
$ pip install pydub
$ pip install pocketsphinx
```

> Now install ffmpeg from here: https://www.ffmpeg.org/download.html

> cd into the folder and run:

```shell
$ python vocal_seperation.py
```

---
### Usage
> Run vocal_seperation.py with src set to an ".mp3" file and it will produce an audio spectogram of the foreground and background audio. The foreground audio is then passed into pocketsphinx as an attempt for speech to text; however, the the current state of this method does not produce very accurate results. In addition, an API call will retrieve the actual lyrics of the song to a ".txt" file. This process is very basic and unreliable currently, but will be improved in the future.

---

## Acknowledgements
This is based on the "REPET-SIM" method of Rafii and Pardo, 2012
and REPET algorithm by Brian McFee

© Copyright 2013--2019, librosa development team
