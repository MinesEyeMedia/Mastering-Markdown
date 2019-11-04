# Images
Images in markdown are pretty much exactly the same as links, with some slight differences. The format for linking an image is like this:
```
![]()
```

It essentially translates out to this: the ! identifies the link as an image. The ```[ ]``` is the ALT-TEXT for the imagine and the ```( )``` is for the actual image URI.

As an alternate option, on imagine just as on regular links, we can add a 'title' by putting the text of the title in double quotes (```" "```) and then we make sure those are still within the URI ```( )``` bracket wrap. See below for actual practical use:

***

## Basic image linking with alt-text.

![A tranquil mossy mountainous landscape with a curvy road running through it.](https://picsum.photos/id/1018/500/300)

***
## Basic image linking with alt-text and title tag.

![A train sorting-yard at sunset.](https://picsum.photos/id/1026/500/300 "The Santa Monica, California sorting yard at sunset.")

***
## Image linking using a token placeholder.

![A tent almost completely covered in snow amongst very large snow-capped mountain ranges.][tent-snow]

[tent-snow]: https://picsum.photos/id/1036/500/300

***
## Image linking nesting (thumbnails, etc.)

[![An massive waterfall deep in lush boreal forest somewhere in Scandinavia.](https://picsum.photos/id/1039/280/150 "A beautiful waterfall deep in the Scandinavian countryside.")](https://picsum.photos/id/1039/6945/4635)