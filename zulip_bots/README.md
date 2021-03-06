# Zulip bots

This directory contains the source code for the `zulip_bots` PyPI package.

The Zulip documentation has guides on [using Zulip's bot system](
https://chat.zulip.org/api/running-bots)
and [writing your own bots](
https://chat.zulip.org/api/writing-bots).

## Directory structure

```shell
zulip_bots  # This directory
├───zulip_bots  # `zulip_bots` package.
│   ├───bots/  # Actively maintained and tested bots.
│   ├───bots_unmaintained/  # Unmaintained, potentially broken bots.
│   ├───lib.py  # Backbone of run.py
│   ├───provision.py  # Creates a development environment.
│   ├───run.py  # Used to run bots.
│   ├───test_lib.py  # Backbone for bot unit tests.
│   ├───test_run.py  # Unit tests for run.py
│   └───zulip_bot_output.py  # Used to test bots in the command line.
├───generate_manifest.py  # Helper-script for packaging.
└───setup.py  # Script for packaging.
```
