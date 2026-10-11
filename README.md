# Blockfield pack mirror

Release `files` holds the Blockfield modpack's files named by the hash the pack declares for them.
packwiz-installer (Blockfield fork, see Blockfield/blockfield-client `tools/packwiz-installer`) uses it as one of several
download mirrors and verifies every file against the pack's hash; https://blockfield.pro stays the authoritative source.
The client CI adds new files and prunes unused ones; do not upload by hand.

Third-party mods keep their own licenses; this repository only mirrors the published pack.
