# open-inventor README

This extension provides basic syntax highlighting and edititing support for Open Inventor scene graph files.

## Features

- Syntax highlighting of node and field names vs. string and numeric constants
- Basic folding (collapsing and extending of node content and sub trees of the scene graph)

## Extension Settings

This extension does not have any settings.

## Known Issues

- Syntax highlighting is restricted to a basic syntactic analysis using a Textmate grammar
  - It does not distinguish between node and field names
  - It cannot distinguish between node/field names and constant enum values
- Folding only works correctly when a line contains only a single curly bracket or a single pair of curly brackets

## Release Notes

### 1.0.0

Initial release
