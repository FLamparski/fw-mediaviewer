##&lt;paper-video&gt;

`paper-video` is a material design styled video player. It contains a video placed in the top and
controls in the bottom. User can fully customize the controllers and the events.

[Live Example](http://spacee.xyz/paper-video/demo.html)

##Installing with Bower

To install the component with the Bower, just run: 

`bower install --save paper-video`


Example:

```html
<link href="path/to/paper-video/paper-video.html" rel="import">

<paper-video class="custom" controls src="demo.mp4"></paper-video>
```

### Styling

The following custom properties and mixins are available for styling:

| Custom property | Description | Default |
| --- | --- | --- |
| `--paper-video-controls-background` | The background color of controllers | `white` |
| `--paper-video-controls-color` | The text and icons color of controllers | `#595959` |
| `--paper-video-slider-color` | The timeline and volume sliders color | `#3367D6` |

###&lt;paper-video&gt; - Properties

The following properties are available:

| Property Name | Description | Default |
| --- | --- | --- |
| `controls` | Enable/Disable the controls | `false` |
| `autoplay` | Playing the video when it's loaded | `false` |
| `loop` | Playing the video again if it's ended | `false` |
| `preload` | Loading the video, when the page loads | `false` |
| `muted` | Sets video to muted mode | `false` |
| `video-volume` | Sets video volume | `100` |
