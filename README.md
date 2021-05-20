# Obsidian Sortable

Sortable is a plugin for [Obsidian](https://obsidian.md) that aims to offer [Wikipedia-like](https://en.wikipedia.org/wiki/Help:Sorting#Example) sortable tables. Right now, the plugin offers ascending / descending sorting based on the data-type of the table header that was clicked.

## Usage
Please note that the development is in (early) alpha stage. If you want to test the plugin, you can download the [latest release](https://github.com/alexandru-dinu/obsidian-sortable/releases), unzip the contents to `/path/to/vault/.obsidian/plugins/obsidian-sortable` and enable it from the settings.

## Key features
- No additional third-party dependencies apart from the ones needed by the [Obsidian API](https://github.com/obsidianmd/obsidian-api).
- No altering of the markdown source code. Sorting is done solely in preview mode by rearranging rows (i.e. `tr` elements).

## Upcoming features
- [Configuration for (special) data types](https://github.com/alexandru-dinu/obsidian-sortable/issues/2).
- [Restore original ordering on third click](https://github.com/alexandru-dinu/obsidian-sortable/issues/4).