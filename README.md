# DualSub Player — Cast receiver

The web page a Chromecast loads when [DualSub Player](https://github.com/fgusztav) casts with its
own receiver application id, instead of Google's default receiver.

It is a single static file, `index.html`, served by GitHub Pages. It draws nothing but the video
and two independently styled subtitle tracks — no overlay on pause — and receives cue data from
the phone over the Cast message channel. The video itself streams from the phone directly to the
TV and never passes through this host.

The canonical source lives in the app repository under `receiver/`; this repo is the deployment.
