# Transcoding

This is a transcoder for panoramic images. It could convert images in Equirectangular projection to Cube Maps.

```sh
$cmake .
$make
$./transcoding input.jpg
```

Layout of output Cube map:

| Left | | Right | |  Up  |

| Down | | Front | | Back |



