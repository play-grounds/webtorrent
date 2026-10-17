# webtorrent

A playground page that fetches an assumeUTXO snapshot in the browser over WebTorrent, hashes it as the bytes arrive, and compares the sha256 with the one on the [assumeUTXO record](https://assumeutxo.com/).

Live: https://play-grounds.github.io/webtorrent/

First cut is wired to one file, the txbt4 fork-point snapshot at height 150307. The torrent facts live in a JSON-LD island on the page using [Torrent Schema](https://torrent-schema.github.io/) terms.
