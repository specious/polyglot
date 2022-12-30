Translate text to multiple languages simultaneously in an interactive terminal session.

[![asciicast](https://asciinema.org/a/541313.svg)](https://asciinema.org/a/541313)

## Installation

Requires the [Translate Shell](https://github.com/soimort/translate-shell) command-line translator.

### Just about any OS

Install [Translate Shell](https://github.com/soimort/translate-shell) and run the script.

### Android

- Get [F-Droid](https://f-droid.org)
- From F-Droid, install [Termux](https://f-droid.org/en/packages/com.termux/)
- In Termux, run:
  ```
  pkg install git translate-shell
  git clone git@github.com:specious/polyglot.git
  cd polyglot
  ./polyglot
  ```

### iOS

It should be possible to run it with [iSH](https://github.com/ish-app/ish). However, [#1699](https://github.com/ish-app/ish/issues/1699#issuecomment-1332663802) currently prevents the requisite Translate Shell from working in iSH.

## License

ISC
