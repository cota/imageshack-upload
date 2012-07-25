imageshack-upload
=================

**git**:          [https://github.com/cota/imageshack-upload](https://github.com/cota/imageshack-upload)
**License**:      GPLv2 or later

Synopsis
--------
imageshack-upload is a simple bash script to upload image files to imageshack.

Requirements
------------
curl, awk, sed, bash.

Usage
-----
Issue

	$ imageshack-upload --help

to get information on usage and a list of available options.

Installation
------------
The script uses the ImageShack API, so a developer key is required. It should be
specified in the `IMAGESHACK_DEVELOPER_KEY` environment variable.

The script is standalone; simply install it anywhere in your $PATH.
