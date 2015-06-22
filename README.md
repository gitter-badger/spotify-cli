spotify-cli
===========

[![Join the chat at https://gitter.im/smithamax/spotify-cli](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/smithamax/spotify-cli?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This package currently uses applescript so it will only work on osx.

Maybe once node-libspotify matures we'll use that.

Install
-------

```bash
$ npm install -g spotify-cli
```

Usage
-----

Commands avalible are `play`, `pause`, `next`, `previous`, `status`.

All pretty self explanitory. The only one with args at the moment is play.

Use it as a resume.

```bash
$ spotify play
INFO: Together - Logistics
```

Or to play a spotify uri.

```bash
$ spotify play spotify:track:1E2tRwT1GIHk1a8oYQMfjC
INFO: Teenage Crime - Radio Edit - Adrian Lux
```
