# A [Snap.svg](http://snapsvg.io/) demo

```sh
$ python -m SimpleHTTPServer
```

When the SVG has a doctype, Snap.svg is unable to select elements from a fragment returned by `Snap.load` **after** that fragment has been included.
