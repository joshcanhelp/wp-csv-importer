# WP CSV Importer

This repo is a "fork" of the repo plugin [CSV Importer](https://wordpress.org/plugins/csv-importer/). I am not affiliated with that plugin in any way but I use it frequently and wanted to add a few features, namely:

- A post-import hook to run additional processing like importing images, adding meta fields, etc
- A character-encoding option to stop the import from breaking on certain characters
- Better error handling