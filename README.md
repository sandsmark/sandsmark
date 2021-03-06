<p align=center>
<img align="center" src="https://raw.githubusercontent.com/sandsmark/sandsmark/master/sandsmark/martin.gif">
</p>

Organized list of my projects
==========================
Most of the repos that might be interesting. Not everything works or is finished.

  1. [Games](#games)
  2. [Game related](#game-related)
  3. [Graphical utilities](#graphical-utilities)
  4. [Command line utilities](#command-line-utilities)
  5. [Machine Learning™-ish](#machine-learning-ish)
  6. [Desktop environment or whatever, stuff that makes my laptop work](#desktop-environment-or-whatever-stuff-that-makes-my-laptop-work)
  7. [Multimedia-related](#multimedia-related)
  7. [Ancient stuff](#ancient-stuff)
  8. [Graphics related](#graphics)
  9. [Libraries](#libraries)
 10. [Demoscene-ish](#demoscene-ish)
 11. [Internet](#internet)
 12. [Chrome extensions](#chrome-extensions)
 13. [KDE 1 and KDE 2](#kde-1-and-kde-2)
 14. [Other](#other)
 15. [Minor stuff](#minor-stuff)


Games
-----
 - [freeaoe](https://github.com/sandsmark/freeaoe), age of empires II reimplementation
 - [Schiffbruch](https://github.com/sandsmark/Schiffbruch/), game I played when I was young. Cleaned up to build and run on Linux, translated most code from german.
 - [tg18ai](https://github.com/sandsmark/tg18ai), planned to use it for holding the AI competition at TG18, but Windows doesn't work.
 - [ghostly](https://github.com/sandsmark/aicompo-tg17), compo case for the AI competition at TG17 ("inverse" Pacman™®).
 - [Turn On Me](https://github.com/sandsmark/aicompo-tg16), compo case for the AI competition at TG16
 - [The Kartering](https://github.com/sandsmark/kart), compo case for the AI competition at TG15, written with [larsivsi](https://github.com/larsivsi) while really sober.
 - [dropdabass](https://github.com/sandsmark/dropdabass), compo case for the AI competition at TG14
 - [droidbattles](https://github.com/sandsmark/droidbattles), programming game.
 - [recrossable](https://github.com/sandsmark/recrossable), crossword game with handwriting recognition and automatic crossword generation. Originally written for my reMarkable™® tablet.
 - [progress-quest](https://github.com/sandsmark/progress-quest), c++/qt version of progress quest.
 - [Awesome War Game](https://github.com/sandsmark/awg), our first year object oriented programming project.
 - [KTamaga](https://github.com/sandsmark/ktamaga), a Tamagotchi emulator. For KDE 1.
 - [Amnesia: A Machine For Pigs](https://github.com/sandsmark/AmnesiaAMachineForPigs), a survival horror game. Porting it to modern versions of stuff like angelscript.
 - [falltergeist](https://github.com/sandsmark/falltergeist), opensource crossplatform Fallout 2™ game engine writen in C++ and SDL. Cleaning up.
 - [kwest](https://github.com/sandsmark/kwest), interpreter for text adventures, half-way ported to Qt5
 - [Goblin Camp Stone Soup](https://github.com/sandsmark/goblin_camp), Dwarf Fortress clone, revisited. Cleaning it up.
 - [Age of The Ring](https://github.com/sandsmark/AoE_Project2), some school project I found. Played around with it and fixed it up a bit.

Game related
-----
 - [Advanced Genie Editor](https://github.com/sandsmark/AGE), editor for the data files in age of empires etc. Uses genieutils, like freeaoe.
 - [genieutils](https://github.com/sandsmark/genieutils), used for freeaoe. Upstream thought I had changed too much, and after that I have done some heavy refactoring and cleanup. Upstream is semi-inactive.
 - [BORG](https://github.com/sandsmark/borg), automated bot launcher used for the AI competition at The Gathering (keeps tracks of scores and stuff, because I didn't want to do that manually on stage).
 - [ghostlybot](https://github.com/sandsmark/ghostlybot), simple test bot for testing the AI competition case at TG17. IIRC it uses Q-learning in some form.
 - [borderlands3-save-editor](https://github.com/sandsmark/borderlands3-save-editor), got stuck on some game-breaking bugs. I have finished the game now, so probbly won't update it any further.
 - [masseffectandromeda-save-editor](https://github.com/sandsmark/masseffectandromeda-save-editor), very, very early WIP, doesn't work at all.
 - [rengine](https://github.com/sandsmark/rengine), header(s)-only C++ scenegraph rendering graphical library thing. Used for tg18ai, so I had to add some stuff and fix some stuff.
 - [OALWrapper](https://github.com/sandsmark/OALWrapper), for Amnesia. Cleaning it up to fix build on Linux.

Graphical utilities
-------------------
 - [sphero-and-mousr-qt-controller](https://github.com/sandsmark/sphero-and-mousr-qt-controller), utility to control the robots my cat play with (mousr and sphero).
 - [qt-scp-reader](https://github.com/sandsmark/qt-scp-reader), an offline reader for the [SCP wiki](http://scp-wiki.wikidot.com/). Works with the data in the SCP mirrors below.
 - [qbyteview](https://github.com/sandsmark/qbyteview), simple tool to visualize a binary (displays entropy with a fancy method I don't remember the name of).
 - [epubreader](https://github.com/sandsmark/epubreader), simple epub reader using qt.
 - [sandsmark-screenshot](https://github.com/sandsmark/sandsmark-screenshot), very simple screenshot utility, replacement for `import png:- | xclip -selection clipboard -t image/png` because xclip broke and it was easier to write this than trying to understand the xclip code.
 - [homefilesharing](https://github.com/sandsmark/homefilesharing), simple (encrypted, authenticated) sharing of files (because who the fuck wants to set up samba just to copy files with a GUI) and remote mouse control (because wtf why is Synergy so complicated).
 - [paqerduty](https://github.com/sandsmark/paqerduty), tray application that notifies you when you're on call and an event happens.
 - [martin-todo](https://github.com/sandsmark/martin-todo), five minute hack because there's no nice simple todo applications that aren't horribly overcomplicated or sucky.
 - [martin-toldyouso](https://github.com/sandsmark/martin-toldyouso), so I can keep track of every time I told people so.
 - [slaq](https://github.com/sandsmark/slaq), slack sucks.
 - [notifu](https://github.com/sandsmark/notifu), someone on IRC wanted a tool that loaded and displayed an URL in a popup for notifications.
 - [turbo-button](https://github.com/sandsmark/turbo-button), simple tray application toggling between battery saving and performance CPU stuff.
 - [qt-rfb-client](https://github.com/sandsmark/qt-rfb-client), RFB/VNC client using Qt, ported to run on my reMarkable™.
 - [pebble](https://github.com/sandsmark/pebble), breadboard layout web app. Test it at https://sandsmark.github.io/pebble/

Command line utilities
----------------------
 - [bincalc](https://github.com/sandsmark/bincalc), simple command line calculator for easily working with bits, convert hex values to float, etc.. Useful when reverse engineering.
 - [dmsdos](https://github.com/sandsmark/dmsdos), linux utilities to handle dos/win95 doublespace/drivespace/stacker.
 - [yzis](https://github.com/sandsmark/yzis), vi implementation.
 - [compouploader](https://github.com/sandsmark/compouploader), automatically downloads results and entries from Unicorn (the competition org system), so they can be uploaded to scene.org.
 - [dcd-extractor](https://github.com/sandsmark/dcd-extractor), a very simple tool to extract the Device Configuration Data from a uboot binary with an IMX header
 - [github-mirror](https://github.com/sandsmark/github-mirror), a simple script to automatically mirror all your github repos
 - [quasselpwdumper](https://github.com/sandsmark/quasselpwdumper), dumps your quassel password from your config file. forgot my password at some point so I wrote this.
 - [quassel-sqlite-merge](https://github.com/sandsmark/quassel-sqlite-merge), script to merge in an old quassel sqlite database into a postgresql database.
 - [unfuckify](https://github.com/sandsmark/unfuckify), makes c++ code using `auto` readable, i. e. unfucks it. I think this is what the kids call "opinionated".
 - [Vector-cmdline-tools](https://github.com/sandsmark/Vector-cmdline-tools), tools to work with the Anki Vector robot. Porting to Qt Bluetooth to make it work on Linux (and maybe Windows).
 - [Steamless](https://github.com/sandsmark/Steamless), SteamStub remover, command line version.

Machine Learning™-ish
------------------
 - [jantu](https://github.com/sandsmark/jantu), artifical consciousness framework + Starcraft Broodwar™® = master thesis.
 - [master thesis](https://github.com/sandsmark/jantu), latex source for my master thesis.
 - [replicode](https://github.com/sandsmark/replicode), constructivist AI language and runtime
 - [repliqode](https://github.com/sandsmark/repliqode), GUI interface for replicode stuff.
 - [replicodekateplugin](https://github.com/sandsmark/replicodekateplugin), simple plugin for Kate to launch the replicode executive directly from it. also syntax highlighting for the replicode language.
 - [Kaldi](https://github.com/sandsmark/kaldi), a fork to train a norwegian speech recognition model.
 - [link-grammar-norwegian](https://github.com/sandsmark/link-grammar-norwegian), started on support for norwegian in link-grammar. too embarrassed of the actual link-grammar stuff to commit it.
 - [ann](https://github.com/sandsmark/ann), for some reason I started on implementing a library for neural nets at a hotel to fall asleep. counting sheeps didn't work.
 - [decision-tree-learning](https://github.com/sandsmark/decision-tree-learning), Implementation of decision-tree learning algorithms in C++ for the course TDT4171 Artificial Intelligence Methods.
 - [forward-backward-inference](https://github.com/sandsmark/forward-backward-inference), implementation of the forward-backward algorithm for the course TDT4171 Artificial Intelligence Methods.
 - [poker-ai](https://github.com/sandsmark/poker-ai), a poker ai written for the course IT3105
 - [caffe](https://github.com/sandsmark/caffe), fork of Caffe for some vapoursynth I think. Forked to fix compatibility with latest cudnn.
 - [vision](https://github.com/sandsmark/vision/tree/martin/images-r-cool), pytorch vision module. Just fixing the libjpeg and libpng usage.
 - [MLDemos](https://github.com/sandsmark/mldemos), visualization tool for random ML algorithms.
 - [narxsim](https://github.com/sandsmark/narxsim), cleaned up some person's master thesis about [NARX](https://en.wikipedia.org/wiki/Nonlinear_autoregressive_exogenous_model)

Desktop environment or whatever, stuff that makes my laptop work
---------------------------------
 - [status](https://github.com/sandsmark/status), a thing for i3-bar. All the alternatives sucked.
 - [sandsmark-notificationd](https://github.com/sandsmark/sandsmark-notificationd), all other notification daemons suck.
 - [dbus-screensaver-inhibit-dummy](https://github.com/sandsmark/dbus-screensaver-inhibit-dummy), dumb hack to keep steam from keeping my machine unlocked and awake forever.
 - [sandsmark-integration](https://github.com/sandsmark/sandsmark-integration), custom QPA for myself, based on frameworks-integration (now gone).
 - [pastenotifier](https://github.com/sandsmark/pastenotifier), pops up a tiny window when the clipboard changes. So you know what you paste before you paste the wrong thing in the wrong window.
 - [polkit-dumb-agent](https://github.com/sandsmark/polkit-dumb-agent), a polkit agent in 145 lines of code, because polkit is dumb and none of the other agents worked.
 - [qiwd](https://github.com/sandsmark/qiwd), GUI interface to iwd (because `wpa_supplicant` is old news).
 - [Select Default Application](https://github.com/sandsmark/selectdefaultapplication), because I don't want notepad to be my default text editor, or Firefox to be my default image viewer.
 - [discotiles](https://github.com/sandsmark/discotiles), simple screensaver effect using QML.
 - [reddit-notifier](https://github.com/sandsmark/reddit-notifier), a KDE plasmoid that shows reddit notifications from the RSS feed of notifications from your reddit account
 - [kfilemon](https://github.com/sandsmark/kfilemon), a simple `LD_PRELOAD`able library to hijack moves to avoid having to use inotify.
 - [xdg-autostart-launcher](https://github.com/sandsmark/xdg-autostart-launcher), automatically launches all applications in the XDG autostart folders.
 - [patoggler](https://github.com/sandsmark/patoggler), simple thing to toggle mute in pulseaudio.

Multimedia-related
------------------
 - [linux-vr-player-or-something](https://github.com/sandsmark/linux-vr-player-or-something), very simple VR video player using libmpv and openhmd. Because apparently everyone thought this was impossible to do or something?
 - [pavucontrol-qt](https://github.com/sandsmark/pavucontrol-qt), major cleanup from upstream and a ton of bugfixes, cleanups and refactoring. Upstream didn't want my changes.
 - [VapourSynth Editor](https://github.com/sandsmark/vapoursynth-editor), editor for vapoursynth scripts. Forked it because upstream seemed dead, and I wanted some features that probably wouldn't get merged in the first place (like full-fletched vim-mode).
 - [sigp](https://github.com/sandsmark/sigp), simple audio visualizer thing for Samfundets Interne Grand Prix 2010.
 - [vapoursynth-movit](https://github.com/sandsmark/vapoursynth-movit), Vapoursynth plugin exposing Movit. Written blindly (aka. plain vim without plugins, and without testing that it builds). Probably doesn't work.
 - [qoniometer](https://github.com/sandsmark/qoniometer), audio visualizer. Because frequency analysis visualization is boring.
 - [qpitch](https://github.com/sandsmark/qpitch), instrument tuner.
 - [guitar-effects](https://github.com/sandsmark/guitar-effects), various realtime, low-latency guitar effects. Loopback thing using pulseaudio.
 - [Butterflow](https://github.com/sandsmark/butterflow), ported to opencv 4 and python 3.
 - [vlc-chromecast-subtitles](https://github.com/sandsmark/vlc-chromecast-subtitles), VLC with the patches for proper subtitle support for Chromecast™®.
 - [inputstream.adaptive](https://github.com/sandsmark/inputstream.adaptive), started refactoring so wvdecrypter could work without Kodi, ended up just trying to fix compatibility with newest version of Widevine.

Ancient stuff
-------------

 - [spokify](https://github.com/sandsmark/Spokify), unofficial spotify™® client. added support for scrobbling (to last.fm), visualizer, the magic starred playlist, and some other stuff I don't remember.
 - [amarok-soundcloud](https://github.com/sandsmark/amarok-soundcloud), soundcloud support for amarok. I think it worked at some point.
 - [vlc-kio](https://github.com/sandsmark/vlc-kio), vlc plugin to use the KDE file io protocol thing framework. don't think I ever finished it.
 - [simpleplayer](https://github.com/sandsmark/simpleplayer), simple audio player for testing phonon from when I maintained phonon.
 - [lastfmscraper](https://github.com/sandsmark/lastfmscraper), screen-scraping tool for dumping when you played stuff from last.fm
 - [akode](https://github.com/sandsmark/akode), start of a backend for Phonon using ffmpeg etc. directly.
 - [vapor](https://github.com/sandsmark/vapor), desktop client for rawk the cloud web music server thing.
 - [impd](https://github.com/sandsmark/impd), custom MPD server implementation.

Graphics
------------------
 - [diffimg](https://github.com/sandsmark/diffimg), graphical UI to inspect differences between two images.
 - [phototonic](https://github.com/oferkv/phototonic), Image Viewer and organizer.
 - [extra-imageformats-qt](https://github.com/sandsmark/extra-imageformats-qt), collection of random extra image format plugins for Qt (bpg, fuif and pgf).
 - [piQtureGLide](https://github.com/sandsmark/piQtureGLide), OpenGL picture viewer thing ported to Qt 5.
 - [heifthumbnailer](https://github.com/sandsmark/heifthumbnailer), KIO HEIF thumbnailer.

Libraries
---------
 - [qhiveplot](https://github.com/sandsmark/qhiveplot), an implementation of hive plots in qt, ended up using it in repliqode
 - [libqsnap](https://github.com/sandsmark/libqsnap), old implementation of the old snapchat API, used for the jolla snapchat™® client Bluefish. Written while drunk on a plane.
 - [winuname](https://github.com/sandsmark/winuname), BSD-licensed implementation of uname I wrote to replace something for something sometime. don't really remember much.
 - [qt-rappor-client](https://github.com/sandsmark/qt-rappor-client), modernized and cleaned up the reference C++ implementation of [RAPPOR](https://static.googleusercontent.com/media/research.google.com/no//pubs/archive/42852.pdf).
 - [pcrio](https://github.com/sandsmark/pcrio), PE file resource editor for genieutils/freeaoe.
 - [QSsh](https://github.com/sandsmark/QSsh), Qt-based library implementing the ssh and sftp protocols.
 - [libqdlibface](https://github.com/sandsmark/libqdlibface), library for doing face recognition. not really tested, but gave up trying to clean up libkface so started on this.
 - [zstr](https://github.com/sandsmark/zstr), header-only C++ library wrapping zlib with iostreams, used for genieutils/freeaoe.
 - [tacopie](https://github.com/sandsmark/tacopie), C++ TCP Library. Upstream is dead.
 - [qtcreator-breakpad](https://github.com/sandsmark/qtcreator-breakpad), breakpad integration extracted from qtcreator.
 - [taglib](https://github.com/sandsmark/taglib), taglib with matroska/ebml support.

Demoscene-ish
---------
 - [cubescubed](https://github.com/sandsmark/cubescubed), compofiller for the 4k competition at TG12.
 - [oyarsa](https://github.com/sandsmark/oyarsa), writing a kernel woo. the solskogen branch contains an entry at solskogen.
 - [invitro](https://github.com/sandsmark/invitro), 4k on Linux at solskogen at 2015 (2015 bytes).
 - [smallhtml](https://github.com/sandsmark/smallhtml), collection of some of the smallhtml compocases I made for TG.
 - [fuckdos](https://github.com/sandsmark/fuckdos), start on a demo of sorts with a trick I found out later wasn't as original as I thought.
 - [textonacube](https://github.com/sandsmark/textonacube), entry in the fast demo compo at TG10 (we actually won money for this).
 - [legendary](https://github.com/sandsmark/legendary), a demo engine that never really got anywhere. but got used for a couple of projects and made some money.

Internet
--------
 - [wdotcrawl](https://github.com/sandsmark/wdotcrawl), wikidot crawler. Rewrote it to mirror the SCP wiki.
 - [imagetracker](https://github.com/sandsmark/imagetracker), simple tracking pixel for emails written in like 2005.
 - [nugatti](https://github.com/sandsmark/nugatti), start of a gnutella implementation written in 2011-2012-ish. never really finished anything besides the most basic parts of the protocol. started because I wanted to figure out how the bootstrapping worked.
 - [kubotu](https://github.com/sandsmark/kubotu), the IRC bot in the #kubuntu IRC channel on freenode for a while.
 - [rawk](https://github.com/sandsmark/Rawk), cloud web music server thing. something like subsonic to have a web-based music player with your own music collection.
 - [sophia](https://github.com/sandsmark/sophia), [mg](https://github.com/martingms) and I started working on a new-school BBS system using ssh while drunk.
 - [quassel-proxy](https://github.com/sandsmark/quassel-proxy), a proxy between the quassel protocol and json from when I wanted a web-based quassel client.
 - [quazzer](https://github.com/sandsmark/quazzer), start of a fuzzer for the quassel protocol.
 - [lolcats](https://github.com/sandsmark/lolcats), displayed a random lolcat from my collection. don't judge me.
 - [cloudsync](https://github.com/sandsmark/cloudsync), replacement for dropbox/ubuntu one/owncloud. don't think it ever worked properly.
 - [quassel-web](https://github.com/sandsmark/quassel-web), started on a web interface for quassel. wanted to have quassel in the steam overlay, and for some reason this seemed like the easiest solution. never finished.
 - [hjemmeside](https://github.com/sandsmark/hjemmeside), one of my old homepages from when I started to learn django.
 - [cbot](https://github.com/sandsmark/cbot), IRC bot for NTNU gangstaz.
 - [DESMAN](https://github.com/sandsmark/desman), distributed peer-to-peer decentralized ~~blockchain~~ service monitoring written for the student society in trondheim in 2008, never actually used. codename "lollercoaster".
 - [notes](https://github.com/sandsmark/notes), web-based note-taking app written in c++.

Chrome extensions
--------
 - [millenials-to-snake-people](https://github.com/sandsmark/millennials-to-snake-people), Chromium extension that does what it says, with toggle button (because I don't want it on all sites).
 - [Imagus](https://github.com/sandsmark/chrome-extension-imagus), Chromium extension to show images on hover, github mirror with unminified code to compare with code in the official Chrome Store. Just because I don't trust stuff in the store.
 - [chrome-extension-tick](https://github.com/sandsmark/chrome-extension-tick), two simple chrome extensions that just tick or untick every checkbox.
 - [autochecker](https://github.com/sandsmark/autochecker), google chrome extension to help automatically check the right boxes when filling out forms.
 - [anti-anti-devtools](https://github.com/sandsmark/anti-anti-devtools), started out as a chromium extension to defeat the tricks people use to detect devtools. Ended up defeating fingerprinting (and crashing some fingerprint-library-backends).
 - [bypass-paywalls-chrome](https://github.com/sandsmark/bypass-paywalls-chrome), Bypass Paywalls web browser extension for Chrome and Firefox, with a fix for some crashing. But upstream doesn't seem to allow me to open a PR.
 - [url-rewriter](https://github.com/sandsmark/url-rewriter), rewrites URLs on the fly.
 - [chrome-no-cohort](https://github.com/sandsmark/chrome-no-cohort), Disables the new google fingerprinting things.
 - [archive.is-chrome-extension](https://github.com/sandsmark/archive.is-chrome-extension), open links via archive.is when you right click them.
 - [browser-painter](https://github.com/sandsmark/browser-painter), draw on web pages.

KDE 1 and KDE 2
---------------

Also see https://invent.kde.org/historical for the basic stuff.

 - [qt1](https://github.com/sandsmark/qt1), copy of Qt1 for usage with KDE1 (with some minor issued fixed, like scrollwheel support in some apps).
 - [qt2](https://github.com/sandsmark/qt2), copy of Qt 2 ported to modern system, with some fixes.
 - [KDE 2 kdelibs](https://github.com/sandsmark/kdelibs), KDE 2 version of kdelibs, fixed up to mostly build on a modern system.
 - [kde1-kuickshow](https://github.com/sandsmark/kde1-kuickshow), KDE 1 version of Kuickshow. And ported away from imlib, because that API is horrible.
 - [kde1-kshow](https://github.com/sandsmark/kde1-kshow), KDE 1 version of kshow. Because you always need more image viewers.
 - [kvoicecontrol](https://github.com/sandsmark/kvoicecontrol), tool that gives you voice control over your unix commands. For KDE 1.
 - [kde1-amor](https://github.com/sandsmark/kde1-amor), backport of Amusing Misuse of Resources for KDE 1 or something.
 - [kde1-kpackage](https://github.com/sandsmark/kde1-kpackage), KDE 1 version of KPackage with libalpm/pacman/archlinux backend/support.
 - [kde1-kteatime](https://github.com/sandsmark/kde1-kteatime), the original (pre-KDE 2 port) version of kteatime.
 - [kcmlaptop](https://github.com/sandsmark/kcmlaptop), laptop support (mostly power management) for KDE1.
 - [kdewizard](https://github.com/sandsmark/kdewizard), kdewizard for KDE1 (I missed Kandalf when running KDE1).
 - [kde2-kdebase](https://github.com/sandsmark/kde2-kdebase), KDE 2 version of kdebase, fixed up to mostly build on a modern system.
 - [kde2-kio-sftp-kde3](https://github.com/sandsmark/kde2-kio-sftp), backport of kio-sftp from KDE 3, wrapping the `ssh` executable. Doesn't work well, use the one below.
 - [kde2-kio-sftp-kde4](https://github.com/sandsmark/kde2-kio-sftp-kde4), backport of kio-sftp from KDE 4, using libssh.
 - [kde2-kmorph](https://github.com/sandsmark/kde1-kmorph), KDE 2 application to morph between two images. Ported and improved performance a bit, don't really know how it is supposed to be used.
 - [KWoodhammer](https://github.com/sandsmark/kwoodhammer), All-in-one shell for all kinds of data encryption. KDE 1 version.

Other
-----
 - [SCP wiki dump](https://github.com/sandsmark/scp-wiki/), full mirror of the scp wiki with the entire history. ~20 million words, fun for training Machine Learning Things™
 - [dotfiles](https://github.com/sandsmark/dotfiles), since everyone like to post these kind of things. And it makes it easy to keep the config in sync across machines.
 - [sequrerender-child](https://github.com/sandsmark/sequrerender-child) and [sequrerender-host](https://github.com/sandsmark/sequrerender-host), testing out-of-process rendering with shared memory and seccomp and stuff.
 - [libfisk](https://github.com/sandsmark/libfisk), `LD_PRELOAD` hack to hide the fact that someone has been fisked. fisking is a long tradition at the Student Society in Trondheim where you do stuff like putting `echo sleep 1 >> ~/.bashrc` into people's `.bashrc` when they forget to lock their session.
 - [bluefish](https://github.com/sandsmark/bluefish), (old) snapchat client for the jolla. snapchat has drastically altered their API, so hasn't worked for a while (since I stopped using my jolla).
 - [glog-squash](https://github.com/sandsmark/glog-squash), `LD_PRELOAD` hack to disable endless amount of spam to the console when launching glib applications.


Unusable old stuff
---------
Probably not useful
 - [spacetrader](https://github.com/sandsmark/spacetrader), start of a port of the space trader game for palmos. never got far.

Minor stuff
------------------------------------
Things I have spent less than five minutes on.

Mostly things I didn't write with a couple of commits (e. g. because I wanted to test something and it didn't build or was missing something trivial.)

 - [qmarkdowntextedit](https://github.com/sandsmark/qmarkdowntextedit), proper standalone version. preserved my fork because upstream later reverted my changes that made it a useful standalone application.
 - [sddm](https://github.com/sandsmark/sddm), started working on wayland support for sddm in 2013. never finished.
 - [kgtk](https://github.com/sandsmark/kgtk), ugly `LD_PRELOAD` hack to make GTK applications use Qt/KDE dialogs. Works sometimes.
 - [krename](https://github.com/sandsmark/krename), rename utility. ported to qt5.
 - [esp-idf](https://github.com/sandsmark/esp-idf), fork to get the latest version with the necessary patches for ODROID-GO.
 - [synkron](https://github.com/sandsmark/synkron), ported to Qt5.
 - [klatexformula](https://github.com/sandsmark/klatexformula), ported to qt5.
 - [kfontview-standalone](https://github.com/sandsmark/kfontview-standalone), displays contents of font files.
 - [kuiserver-standalone](https://github.com/sandsmark/kuiserver-standalone), standalone fork of kuiserver, so I don't need to pull in the entire plasma workspace just because I use a lot of KDE stuff.
 - [kcm-lookandfeel-standalone](https://github.com/sandsmark/kcm-lookandfeel-standalone), to avoid having to install the whole Plasma desktop.
 - [kjackal](https://github.com/sandsmark/kjackal), rootkit scanner. ported to newer kernels.
 - [kde-cli-tools-standalone](https://github.com/sandsmark/kde-cli-tools-standalone), to avoid having to install the whole Plasma desktop just for kcmshell.
 - [qt-polkitagent](https://github.com/sandsmark/qt-polkitagent), couldn't get any polkit crap to work. So had to fix the build of this to test it, but surprise, it didn't work.
 - [signsrch](https://github.com/sandsmark/signsrch), just a mirror, but with history.
 - [clickteam-unpack](https://github.com/sandsmark/clickteam-unpack), fixed compatibility with some installer (forgot which).
 - [irstlm](https://github.com/sandsmark/irstlm), had to fix this to get Kaldi to work Properly™.
 - [opensift](https://github.com/sandsmark/opensift), upstream is dead. Now with modern opencv support.
 - [konsolelauncher](https://github.com/sandsmark/konsolelauncher), testing quick and dirty hack to speed up launching of konsole.
 - [opensift](https://github.com/sandsmark/opensift), Open-Source SIFT Library. Fixing opencv compatibility and stuff.
 - [kdeconnect-minimal](https://github.com/sandsmark/kdeconnect-minimal), kdeconnect without so many big required dependencies.
 - [okular-backend-mupdf](https://github.com/sandsmark/okular-backend-mupdf), PDF backend for Okular using MuPDF. Cleaning it up.
 - [Ghidra](https://github.com/sandsmark/ghidra), adding some hardening flags to Ghidra build.
 - [ini-editor](https://github.com/sandsmark/ini-editor), I think this was to create a more generic config interface for the Xine backend for phonon.


![lol](https://raw.githubusercontent.com/sandsmark/sandsmark/master/sandsmark/dog.jpg)


