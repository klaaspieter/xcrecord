# xcrecord

Capture GIFs from the iOS simulator 🎥

# Install

```sh
brew tap klaaspieter/homebrew-formula
brew install xcrecord
```

# Usage

```sh
xcrecord [OPTION] file

OPTIONS

-v --version
  Prints the version number

-s --scale --no-scale
  Scale (resize) the GIF using ffmpeg. Accepts the same options ffmpeg does. The default is “-1:480”.
  See https://trac.ffmpeg.org/wiki/Scaling%20(resizing)%20with%20ffmpeg for more information.

```
