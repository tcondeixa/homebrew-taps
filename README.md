# Homebrew Taps

This repository contains Homebrew formulae and casks for various tools.

## Adding the Tap

To add this tap to your Homebrew installation:

```bash
brew tap tcondeixa/taps
```

## Available Casks

### gomanager

A Go version manager tool.

**Install:**
```bash
brew install --cask gomanager
```

**Features:**
- Binary installation with shell completions (Bash, Zsh, Fish)
- Supports both Intel and ARM64 macOS architectures

## Usage

After adding the tap, you can install any available cask using:

```bash
brew install --cask <formula-name>
```

To see all available formulae in this tap:

```bash
brew search tcondeixa/taps
```

## Updating

To update the tap and get the latest versions:

```bash
brew update
brew upgrade --cask <formula-name>
```

## Updating Casks

To update a specific cask to the latest version:

```bash
brew upgrade --cask gomanager
```

To update all casks from this tap:

```bash
brew upgrade --cask
```

To check for outdated casks:

```bash
brew outdated --cask
```