# compass_rose
A simple, limited pure-SASS shim to ease getting out of Compass - because a Compass by any other name still smells as sweet

## Double-warning
This library probably isn't right for you.  Or, honestly, for anyone.  This is a small collection of trivial mixins I wrote to get away from Compass as I entered a new project at work.  It's not meant to be comprehensive, and it doesn't gracefully fall back.  I'm not trying to support IE older than 9.

However, the project we were on was moving away from Ruby, and that meant that Compass, which had not been in heavy use, needed to go.

This is my exit path.  If you'd like to contribute to it, please feel free.  :smile:

## Tiny list of mixin exits
Currently I support
  * `=single_transition`
  * `=opacity`
  * `=border_radius`

I am explicitly dropping `=box-shadow` because it's natively supported by the browsers I care about.

## Note
It may be useful to use [ReverseLodestone]() before you get started, to make sure there aren't any severe dependencies.

Polemic :neckbeard:
-------------------

`compass_rose` is MIT licensed, because viral licenses and newspeak language modification are evil.  Free is ***only*** free when it's free for everyone.
