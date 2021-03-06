CKEditor 4 – The best browser-based WYSIWYG editor
==================================================

## Development Code

This repository contains the development version of CKEditor.

**Attention:** The code in this repository should be used locally, for development purposes only.
We don’t recommend distributing it on remote websites because the user experience will be very limited.
For that purpose, you should build it (see bellow) or use an official release instead,
available in the [CKEditor website](http://ckeditor.com).

### Code Installation

There is no special installation procedure to install the development code.
Simply clone it on any local directory and you’re set.

### Samples

The `samples/` folder contains a good set of examples that can be used
to test your installation as well as being a precious resource for learning
some aspects of the CKEditor JavaScript API and its integration on web pages.

### Code Structure

The development code contains the following main elements:

  - Main coding folders:
    - `core/`: the core API of CKEditor. Alone, it does nothing, but
    it provides the entire JavaScript API that makes the magic happen.
    - `plugins/`: contains most of the plugins maintained by the CKEditor core team.
    - `skin/`: contains the official default skin of CKEditor.
    - `dev/`: contains “developer tools”.

### Building a Release

A release optimized version of the development code can be easily created locally.
The `dev/builder/builder.sh` script can be used for that purpose:

	> ./dev/builder/builder.sh

A “release ready” version of you development code working copy will be built in the new `dev/builder/release/` folder.
Internet connection is necessary to run the builder, for its first time at least.

### License

Licensed under the GPL, LGPL and MPL licenses, at your choice.

For full details about license, please check the LICENSE.md file.
