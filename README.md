# Homebrew Tap for Jta

Official Homebrew tap for [Jta](https://github.com/hikanner/jta) - AI-powered Agentic JSON Translation tool.

## Installation

```bash
brew tap hikanner/jta
brew install jta
```

## What is Jta?

Jta is an AI-powered JSON translation tool that follows Andrew Ng's agentic reflection approach. It supports multiple AI providers (OpenAI, Anthropic, Gemini) and includes features like:

- 🤖 Agentic reflection mechanism for high-quality translations
- 📚 Terminology management system
- 🔄 Incremental translation support
- 🌍 RTL language support (Arabic, Hebrew, Persian, Urdu)
- 🎯 Key filtering with wildcard patterns
- 🛡️ Format protection (HTML, Markdown, URLs, placeholders)

## Usage

After installation, you can use the `jta` command:

```bash
# Check version
jta --version

# Translate a JSON file
jta translate -s en -t es input.json -o output.json

# Use with terminology
jta translate -s en -t zh input.json --terminology .jta/

# See all options
jta --help
```

## Updating

```bash
brew update
brew upgrade jta
```

## More Information

- **Project Repository**: [hikanner/jta](https://github.com/hikanner/jta)
- **Documentation**: [README](https://github.com/hikanner/jta#readme)
- **Issue Tracker**: [Issues](https://github.com/hikanner/jta/issues)
- **Releases**: [Releases](https://github.com/hikanner/jta/releases)

## About this Tap

This tap is automatically maintained by [GoReleaser](https://goreleaser.com/). When a new version of Jta is released, the formula is automatically updated.
