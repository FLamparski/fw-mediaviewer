# fw-mediaviewer

[Docs & Demos](http://www.filipwieland.com/fw-mediaviewer/)

An easy-to-use media viewer component for Polymer. It supports viewing
individual media as well as collections, with navigation between media items.
It is responsive and aims to be extensible.

At the moment, it can deal with images and videos by default.

fw-mediaviewer implements a subset of `iron-selector`'s interface, and
uses `IronOverlayBehavior`.

## A simple image gallery

    <fw-mediaviewer id="viewer"></fw-mediaviewer>
    <script>
    this.$.viewer.items = [
      {type: 'image', src: 'https://source.unsplash.com/random?t=1'},
      {type: 'image', src: 'https://source.unsplash.com/random?t=2'},
      {type: 'image', src: 'https://source.unsplash.com/random?t=3'}
    ]
    this.$.viewer.open()
    </script>

That's it.

Please also check out the demos to see a bit more of
what this component can do.
