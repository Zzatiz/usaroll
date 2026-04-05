<img src="assets/banner.svg" alt="usaroll Banner" width="100%"/>

# usaroll

An interactive HTML/JavaScript page that renders a US map in ASCII art and linkifies state abbreviations to Google search queries — a quick payroll and state reference tool.

## Overview

`usaroll` displays a styled ASCII-art map of the United States in a terminal-inspired interface (black background, green text). Every two-letter state abbreviation in the art is automatically hyperlinked to a Google search for that state, making it a fast reference for US state lookups.

## Contents

| File | Description |
|------|-------------|
| `testsite.txt` | HTML source for the US map reference page |

## Features

- ASCII art continental US map rendered line-by-line with animation
- Auto-linkification of two-letter state abbreviations (e.g. `NY`, `CA`, `TX`)
- Configurable link color
- Zero dependencies — pure HTML + vanilla JavaScript

## Usage

1. Rename or copy `testsite.txt` to `index.html`
2. Open in any modern browser
3. Watch the map render line by line and click any state abbreviation for an instant search
