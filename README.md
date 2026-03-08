# Polyglot 🗣️ — Interactive Multi-Language Terminal Translator

Translate text to **multiple languages simultaneously** via an interactive bash prompt. Powered by [translate-shell](https://github.com/soimort/translate-shell). Zero deps beyond that. Works on **Linux, macOS, Windows, Termux (Android)** — iOS via iSH/Blink Shell.

**Perfect for:**

- Comparing translations side-by-side (e.g. Romance, Germanic, Slavic languages)
- People studying or working with multiple languages
- Language learners spotting nuances
- Polyglots & travelers (Termux/SSH-friendly)
- Quick CLI lookups, no browser needed

## Quick demo

[![asciicast](https://asciinema.org/a/541313.svg)](https://asciinema.org/a/541313)

## Commands

```
/c {fr,de,bg,...} - clear languages (set them from scratch)
/a fr{,de,bg,...} - add language(s)
/d fr{,de,bg,...} - remove language(s)
/f pl             - set source language
/l                - show supported languages
/?                - print help
/q                - quit
```

## Installation

### Any Unix-like (Linux/macOS)

1. Install [translate-shell](https://github.com/soimort/translate-shell) (e.g., `brew install translate-shell`)
2. `git clone https://github.com/specious/polyglot.git && cd polyglot && ./polyglot`

### Arch Linux

Get the [polyglot-translate-git](https://aur.archlinux.org/packages/polyglot-translate-git) AUR package.

### Android (Termux)

```
pkg add git translate-shell
git clone https://github.com/specious/polyglot.git
cd polyglot
./polyglot
```

### iOS

- Try [iSH Shell](https://ish.app) (note: translate-shell issue [#1699](https://github.com/ish-app/ish/issues/1699#issuecomment-1332663802))
- Or [Blink Shell](https://blink.sh) for Mosh/SSH

## Why you'll love it

- **Zero config**
- **Custom lang sets** (e.g., `/c es,pt,it,fr` for Romance)
- **Portable** — same bash script everywhere
- **Fast** interactive loop fetches all translations in parallel

Typing `/l` shows list of supported languages.

## Related

Built for fans of [translate-shell](https://github.com/soimort/translate-shell). Star if useful!

## License

This project is licensed under ISC, a minimal permissive license functionally equivalent to MIT.
