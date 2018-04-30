# xcrecord

Capture GIFs from the iOS simulator 🎥

# Install

```sh
brew tap klaaspieter/homebrew-formula
brew install xcrecord
```

Note that xcrecord currently does not work with ffmpeg 4.0 ([#2]). Downgrade to 3.4.2 instead:

```sh
brew install https://raw.githubusercontent.com/Homebrew/homebrew-core/18b47ee7e250f4e0447dc6454d9189d1fae0c6a5/Formula/ffmpeg.rb
brew switch 3.4.2
```

[#2]: https://github.com/klaaspieter/xcrecord/issues/2

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
