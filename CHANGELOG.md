# Changelog

## 1.0.0

**Release date:** TBD

Version 1.0.0 is the first release of `markdown`, which renders CommonMark to HTML with the GitHub extensions for tables, strikethrough, task lists, and autolinks.

- Added `markdown.render`, `markdown.parse`, and `markdown.html`.
  - `markdown.render`: Renders Markdown text to HTML.
  - `markdown.parse`: Parses Markdown text into a syntax tree of nested tables.
  - `markdown.html`: Renders a syntax tree from `markdown.parse` to HTML.
