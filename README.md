Translate text to multiple languages simultaneously in an interactive terminal session.

[![asciicast](https://asciinema.org/a/541313.svg)](https://asciinema.org/a/541313)

## Installation

Requires the [Translate Shell](https://github.com/soimort/translate-shell) command-line translator.

### Just about any OS

Install [Translate Shell](https://github.com/soimort/translate-shell) and run the script.

### Android

- Install [Termux](https://termux.dev)
- In Termux, run:
  ```
  pkg install git
  pkg install --no-install-recommends translate-shell
  git clone https://github.com/specious/polyglot.git
  cd polyglot
  ./polyglot
  ```

### iOS

It should in principle be possible to run it with [iSH](https://github.com/ish-app/ish). However, [#1699](https://github.com/ish-app/ish/issues/1699#issuecomment-1332663802) currently prevents the requisite Translate Shell from working in iSH.

It might also be possible to run it with [Blink Shell](https://blink.sh).

## License

[ISC](LICENSE)
