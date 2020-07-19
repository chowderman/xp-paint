# ![Paint Logo](docs/logo.png) XP Paint

[Try out XP Paint here!](https://chowderman.github.io/xp-paint.html)

![XP Paint](docs/example.png)

_**Note: This is a fan project based on my nostalgia for the amazing Windows XP OS, but is in no way affiliated with Microsoft**_

XP Paint is a web-based version of MS Paint for Windows XP. It is a fork of JS Paint, with the following differences:
 * It is self contained in a single .html file (~1 MB in size).
 * It is fully usable offline.
 * It removes many excess features from JS Paint that are not in the actual Windows XP MS Paint (besides a few features, such as rendering GIFs and increased history).
 * It is much lighter than JS Paint (since it only includes the essential features).
 * It is Windows XP styled instead of Windows 95 styled.


# Usage

To use XP Paint, either click [this link](https://chowderman.github.io/xp-paint.html) to use it on the web, or simply [download a copy](https://github.com/chowderman/xp-paint/releases/download/v1.0.0/xp-paint.html) from this repo. The file `xp-paint.html` contains the entire XP Paint program, including all images and scripts needed to use XP Paint. The only other thing you'll need is a web browser to open the html file in!


# Building XP Paint from source

XP Paint requires the following prerequisites:
 * [monolith](https://github.com/Y2Z/monolith) to be installed and on the path. 
 * NodeJS v10+

Commands to build XP Paint:

```
git clone
cd xp-paint
node build.js
```

# Credits

Credits to [Isaiah Odhner](https://isaiahodhner.ml/) and contributors for creating the original JS Paint from which this is forked.


# Contributing

Since this is a fork of JS Paint originally, there may be excess code and files within the repo that are no longer used in XP Paint. Any pull requests that can remove or optimize the size of the repo and the size of the single html file output are much appreciated. Hopefully we can get the single html file to below 1 MB in size!
