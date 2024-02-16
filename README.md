# mdict-cli

#### 🧊 Dead Simple Interface written in Bash
### ⭐ Definition / Synonym / Antonyms / Usage
#### 🍉 Zero-dependency

Get Started
-----------

```bash
# Clone the repo
git clone git@github.com:metaory/mdict-cli.git

# Navigate to repo
cd mdict-cli

# Give execution permissions
chmod +x mdict

# Link it somewhere in your PATH
ln -sfv mdict /usr/bin/mdict

# Use it anywhere

# Usage help
mdict --help
```
```md
mdict - dead simple CLI for Definition / Synonym / Antonyms / Usage

Usage
=====
 $ mdict <COMMAND> [OPTIONS]

COMMANDS
========
 mdict def <WORD> | word definitions
 mdict syn <WORD> | word synonyms
 mdict ant <WORD> | word antonyms
 mdict use <WORD> | word usage examples
 mdict <WORD>     | all the above for word

OPTIONS
=======
  -V, --verbose         be more verbose
  -q, --quiet, --silent inhibit the usual output
  -h, --help            display this help and exit
  -v, --version         display version and exit
```

---

## License

[MIT](LICENSE)
