## streamlink 0.0.2 (10-12-2016)

The second ever release of Streamlink!

In this release we've not only set the stepping stone for the further development of Streamlink (documentation site updated, CI builds working) but we're already fixing bugs and implementing features past the initial fork of livestreamer.

The main features of this release are:
  - New windows build available and generated via pyinstaller
  - Multiple provider bug fixes (twitch, picarto, itvplayer, crunchyroll, periscope, douyutv)
  - Updated and reformed documentation which also includes our site [https://streamlink.github.io](https://streamlink.github.io)

As always, below is a `git shortlog` of all changes from the previous release of Streamlink (0.0.1) to now (0.0.2).

```
Brainzyy <Brainzyy@users.noreply.github.com> (1):
      add stream.me to the docs

Charlie Drage <charlie@charliedrage.com> (9):
      Add script to generate authors list / update authors
      Add release script
      Get setup.py ready for a release.
      Revert "Latest fix to plugin from livestreamer"
      0.0.1 Release
      Update the README with installation notes
      Update copyright author
      Update plugin description on README
      It's now 2016

Forrest <gravyboat@users.noreply.github.com> (1):
      Add a coverage file (#54)

Forrest Alvarez <forrest.alvarez@gmail.com> (4):
      Modify release for streamlink
      Remove faraday from travis run
      Remove tox
      Add the code coverage badge

Latent Logic <lat.logic@gmail.com> (1):
      Picarto plugin: multistream workaround (fixes #50)

Maschmi <Maschmi@users.noreply.github.com> (1):
      added travis build status badge fixes #74 (#76)

Randy Taylor <tehgecKozzz@gmail.com> (1):
      Fix typo in issues docs and improve wording (#61)

Simon Bernier St-Pierre <sbernierstpierre@gmail.com> (8):
      add script to build & copy the docs
      move makedocs.sh to script/
      Automated docs updates via travis-ci
      prevent the build from hanging
      fix automated commit message
      add streamboat to the docs
      disable docs on pull requests
      twitch.tv: add option to disable hosting

Simon Bernier St-Pierre <sbstp@users.noreply.github.com> (2):
      Don't delete everything if docs build fail (#62)
      Create install script for pynsist (#27)

beardypig <beardypig@users.noreply.github.com> (3):
      TVPlayer plugin supports the latest version of the website
      crunchyroll: decide if to parse the stream links as HLS variant playlist or plain old HLS stream (fixes #70)
      itvplayer: updated the productionId extraction method

boda2004 <boda2004@gmail.com> (1):
      fixed periscope live streaming and allowed url re (#79)

ethanhlc <sakithree@gmail.com> (1):
      fixed instances of chrippa/streamlink to streamlink/streamlink

scottbernstein <scott_bernstein@hotmail.com> (1):
      Latest fix to plugin from livestreamer

steven7851 <steven7851@msn.com> (1):
      Update plugin.douyutv
```

## streamlink 0.0.1 (09-23-2016)

The first release of Streamlink!

This is the first release from the initial fork of Livestreamer. We aim to have a concise, fast review process and progress in terms of development and future releases.

Below is a `git shortlog` of all commits since the last change within Livestream (hash ab80dbd6560f6f9835865b2fc9f9c6015aee5658). This will serve as a base-point as we continue development of "Streamlink".

New releases will include a list of changes as we add new features / code refactors to the existing code-base.

```
Agustin Carrasco <asermax@gmail.com> (2):
      plugins.crunchyroll: added support for locale selection
      plugins.crunchyroll: use locale parameter on the header's user-agent as well

Alan Love <alan@cattes.us> (3):
      added support for livecoding.tv
      removed printing
      updated plugin matrix

Alexander <AleXoundOS@users.noreply.github.com> (1):
      channel info url change in afreeca plugin

Andreas Streichardt <andreas.streichardt@gmail.com> (1):
      Add Sportschau

Anton <anton9121@gmail.com> (2):
      goodgame ddos validation
      add stream_id with words

Benedikt Gollatz <ben@differentialschokolade.org> (1):
      Add support for ORF TVthek livestreams and VOD segments

Benoit Dien <benoit.dien@gmail.com> (1):
      Meerkat plugin

Brainzyy <Brainzyy@users.noreply.github.com> (1):
      fix azubu.tv plugin

Charlie Drage <charlie@charliedrage.com> (9):
      Update the README
      Fix travis
      Rename instances of "livestreamer" to "streamlink"
      Fix travis
      Add script to generate authors list / update authors
      Get setup.py ready for a release.
      Add release script
      Revert "Latest fix to plugin from livestreamer"
      0.0.0 Release

Charmander <~@charmander.me> (1):
      plugins.picarto: Update for API and URL change

Chris-Werner Reimer <creimer@betaworx.eu> (1):
      fix vaughnlive plugin #897

Christopher Rosell <chrippa@tanuki.se> (7):
      plugins.twitch: Handle subdomains with dash in them, e.g. en-gb.
      cli: Close output on exit.
      Show a brief usage when no option is specified.
      cli: Fix typo.
      travis: Use new artifacts tool.
      docs: Fix readthedocs build.
      travis: Build installer exe aswell.

Daniel Meißner <daniel@3st.be> (2):
      plugin: added media_ccc_de api and protocol changes
      docs/plugin_matrix: removed needless characters

Dominik Sokal <dominiksokal@gmail.com> (1):
      plugins.afreeca: fix stream

Ed Holohan <edmund@holohan.us> (1):
      Quick hack to handle Picarto changes

Emil Stahl <emil@emilstahl.dk> (1):
      Add support for viafree.dk

Erik G <aposymbiosis@gmail.com> (7):
      Added plugin for Dplay.
      Added plugin for Dplay and removed sbsdiscovery plugin.
      Add HLS support, adjust API schema, no SSL verify
      Add pvswf parameter to HDS stream parser
      Fix Video ID matching, add .no & .dk support, add error handling
      Match new URL, add HDS support, handle incorrect geolocation
      Add API support

Fat Deer <fatdeer@foxmail.com> (1):
      Update pandatv.py

Forrest Alvarez <forrest.alvarez@gmail.com> (3):
      Add some python releases
      Add coveralls to after_success
      Remove artifacts

Guillaume Depardon <guillaume.depardon@outlook.com> (1):
      Now catching socket errors on send

Javier Cantero <jcantero@escomposlinux.org> (1):
      Add new parameter to Twitch usher URL

Jeremy Symon <jtsymon@gmail.com> (2):
      Sort list of streams by quality
      Avoid sorting streams twice

Jon Bergli Heier <snakebite@jvnv.net> (2):
      plugins.nrk: Updated for webpage changes.
      plugins.nrk: Fixed _id_re regex not matching series URLs.

Kari Hänninen <lonefox@kapsi.fi> (7):
      Use client ID for twitch.tv API calls
      Revert "update INFO_URL for VaughnLive"
      Remove spurious print statement that made the plugin incompatible with python 3.
      livecoding.tv: fix breakage ("TypeError: cannot use a string pattern on a bytes-like object")
      sportschau: Fix breakage ("TypeError: a bytes-like object is required, not 'str'"). Also remove debug output.
      Update the plugin matrix
      Bump version to 1.14.0-rc1

Marcus Soll <Superschlumpf@web.de> (2):
      Added plugin for blip.tv VOD
      Updated blip.tv plugin

Mateusz Starzak <mstarzak@gmail.com> (1):
      Update periscope.py

Michael Copland <mjbcopland@gmail.com> (1):
      Fixed weighting of Twitch stream names

Michael Hoang <enzime@users.noreply.github.com> (1):
      Add OPENREC.tv plugin and chmod 2 files

Michiel <msvos@liacs.nl> (1):
      Support for Tour de France stream

Paul LaMendola <paulguy119@gmail.com> (2):
      Maybe fixed ustream validation failure.
      More strict test for weird stream.

Pavlos Touboulidis <pav@pav.gr> (2):
      Add antenna.gr plugin
      Update plugin matrix for antenna

Robin Schroer <sulami@peerwire.org> (1):
      azubutv: set video_player to None if stream is offline

Seth Creech <sethaaroncreech@gmail.com> (1):
      Added logic to support host mode

Simon Bernier St-Pierre <sbernierstpierre@gmail.com> (5):
      update the streamup.com plugin
      support virtualenv
      update references to livestreamer
      add stream.me plugin
      add streamboat plugin

Summon528 <cody880528@hotmail.com> (1):
      add support to afreecatv.com.tw

Swirt <swirt.ac@gmail.com> (2):
      Picarto plugin: update RTMPStream-settings
      Picarto plugin: update RTMPStream-settings

Tang <sugar1987cn@gmail.com> (1):
      New provider: live.bilibili.com

Warnar Boekkooi <warnar@boekkooi.net> (1):
      NPO token fix

WeinerRinkler <drachenlord@8chan.co> (2):
      First version
      Error fixed when streamer offline or invalid

blxd <blxd@users.noreply.github.com> (5):
      fixed tvcatchup.com plugin, the website layout changed and the method to find the stream URLs needed to be updated.
      tvcatchup now returns a variant playlist
      tvplayer.com only works with a browser user agent
      not all channels return hlsvariant playlists
      add user agent header to the tvcatchup plugin

chvrn <chev@protonmail.com> (4):
      added expressen plugin
      added expressen plugin
      update() => assign with subscript
      added entry for expressen

e00E <vakevk+git@gmail.com> (1):
      Fix Twitch plugin not working because bandwith was parsed as an int when it is really a float

fat deer <fatdeer@foxmail.com> (1):
      Add Panda.tv Plugin.

fcicq <fcicq@fcicq.net> (1):
      add afreecatv.jp support

hannespetur <hannespetur@gmail.com> (8):
      plugin for Ruv - the Icelandic national television - was added
      removed print statements and started to use quality key as audio if the url extensions is mp3
      the plugin added to the plugin matrix
      removed unused import
      alphabetical order is hard
      removed redundant assignments of best/worst quality
      HLS support added for the Ruv plugin
      Ruv plugin: returning generators instead of a dict

int3l <int3l@users.noreply.github.com> (1):
      Refactoring and update for the VOD support

intact <intact.devel@gmail.com> (21):
      plugins.artetv: Update json regex
      Updated douyutv.com plugin
      Added plugin for streamup.com
      plugins.streamupcom: Check live status
      plugins.streamupcom: Update for API change
      plugins.streamupcom: Update for API change
      plugins.dailymotion: Add HLS streams support
      plugins.npo: Fix Python 3 compatibility
      plugins.livestream: Prefer standard SWF players
      plugins.tga: Support more streams
      plugins.tga: Fix offline streams
      plugins.vaughnlive: Fix INFO_URL
      Added plugin for vidio.com
      plugins.vaughnlive: Update for API change
      plugins.vaughnlive: Fix app for some ingest servers
      plugins.vaughnlive: Remove debug print
      plugins.vaughnlive: Lowercase channel name
      plugins.vaughnlive: Update for API change
      plugins.vaughnlive: Update for API change
      plugins.livestream: Tolerate missing swf player URL
      plugins.livestream: Fix player URL

jkieberk <jkieberking@gmail.com> (1):
      Change Fedora Package Manager from Yum  to Dnf

kviktor <kviktor@cloud.bme.hu> (2):
      plugins: mediaklikk.hu stream and video support
      update mediaklikk plugin

livescope <livescope@users.noreply.github.com> (1):
      Add VOD/replay support for periscope.tv

liz1rgin <waiphereme@gmail.com> (2):
      Fix goodgame find Streame
      Update goodgame.py

maop <me@marcoalfonso.net> (1):
      Add Beam.pro plugin.

mindhalt <mindhalt@gmail.com> (1):
      Update redirect URI after successful twitch auth

neutric <ah0703@googlemail.com> (1):
      Update issues.rst

nitpicker <daniel@localhost> (2):
      I doesn't sign the term of services, so I doesnt violate!
      update INFO_URL for VaughnLive

oyvindln <mail@example.com> (1):
      Allow https urls for nrk.no.

ph0o <ph0o@users.noreply.github.com> (1):
      Create servustv.py

pulviscriptor <pulviscriptor@gmail.com> (1):
      GoodGame URL parse fix

scottbernstein <scott_bernstein@hotmail.com> (1):
      Latest fix to plugin from livestreamer

steven7851 <steven7851@msn.com> (16):
      plugins.douyutv: Use new api.
      update douyu
      fix cdn..
      fix for Python 3.x..
      use mobile api for reducing code
      fix for non number channel
      add middle and low quality
      fix quality
      fix room id regex
      make did by UUID module
      fix channel on event
      more retries for redirection
      remove useless lib
      try to support event page
      use https protocol
      Update plugin.douyutv

trocknet <trocknet@github> (1):
      plugins.afreeca: Fix HLS stream.

whizzoo <grenardus@gmail.com> (2):
      Add RTLXL plugin
      Add RTLXL plugin

wolftankk <wolftankk@gmail.com> (3):
      get azubu live status from api
      use new api get stream info
      fix video_player error
```
