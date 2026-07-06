| 🇺🇸 English | 🇯🇵 [日本語](README.ja.md) |
|-|-|

# SaiKanji Tap

A [Homebrew](https://brew.sh) tap for **SaiKanji** — a colorful, stroke-order-aware font based on KanjiVG.

![SaiKanji Preview](https://github.com/am517/SaiKanji/blob/main/saikanji.jpg)

## Available Fonts

This tap provides **one cask per font variant**. Each cask installs the corresponding `.ttf` file from the [SaiKanji GitHub releases](https://github.com/am517/SaiKanji/releases).

You can browse the available fonts with:

```bash
brew search font-saikanji
```

## Installation

### 1. Add the tap

```bash
brew tap am517/tap
```

### 2. Trust the tap (required the first time)

Homebrew treats third-party taps as untrusted for security reasons. Run:

```bash
brew trust am517/tap
```

### 3. Install a font

```bash
brew install --cask font-saikanji-regular-solid
# or any other variant, e.g.
brew install --cask font-saikanji-balanced-gradient-grid
```


### Using a Brewfile

```ruby
tap "am517/tap"

cask "font-saikanji-regular-solid"
cask "font-saikanji-balanced-gradient-grid"
# add whichever variants you want
```

## More Information

- **Project homepage & live demo**: [saikanji.moore.is](https://saikanji.moore.is)
- **Source & releases**: [github.com/am517/SaiKanji](https://github.com/am517/SaiKanji)
- **Font license**: [CC BY-SA 4.0]((https://github.com/am517/SaiKanji/LICENSE.md))

## Documentation

See `brew help`, `man brew`, or the [official Homebrew documentation](https://docs.brew.sh).
