# spellcheck

Enable/Disable spellcheck from the command line on macOS.

## Installation

### Using homebrew:

```shell
brew tap meowmeowmeowcat/taps
brew install meowmeowmeowcat/taps/spellcheck
```

### Install manually:

```shell
curl -L https://raw.githubusercontent.com/meowmeowmeowcat/spellcheck/main/spellcheck \
  -o /usr/local/bin/spellcheck && chmod +x /usr/local/bin/spellcheck
```

## Example

If spellcheck is enabled:
```shell
$ spellcheck
Automatic spelling correction disabled.
Automatic Text Completion disabled.
```

If spellcheck is disabled:
```shell
$ spellcheck
Automatic spelling correction enabled.
Automatic Text Completion enabled.
```


## Usage

```
Usage: spellcheck [options]

options:
-s, --settings   Display current settings.
-h, --help       Display this help and exit. 
-v, --version    Display version information and exit.
```
