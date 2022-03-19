<h1 align="center">stream-cli</h1>
<p align="center">A  tool which search magnet links and stream it with peerflix.The idea came while watching <a href='https://github.com/Bugswriter/notflix'>notflix</a> and the latter I found very buggy so I made mine based on the piratebay much more complete and functional.
</p>

### How does this work?
<img src='./stream-cli.gif'>
This is a shell script. It scape 1337x and get the magnet link.
After this it use [peerflix](https://github.com/mafintosh/peerflix) to stream the video from magnet link.
For scraping script use simple gnu utils like sed, awk, paste, cut.

## Requirements

* [peerflix](https://github.com/mafintosh/peerflix) - A tool to stream torrent. `sudo npm install peerflix -g`

## Installation

### cURL
cURL **stream-cli** to your **$PATH** and give execute permissions.

```sh
$ sudo curl -sL "https://raw.githubusercontent.com/meteor314/stream-cli/master/stream-cli" -o /usr/local/bin/stream-cli

$ sudo chmod +x /usr/local/bin/stream-cli
```
- To update, just do `curl` again, no need to `chmod` anymore.
- To uninstall, simply remove `stream-cli` from your **$PATH**, for example `sudo rm -f /usr/local/bin/stream-cli.

## License
This project is licensed under [GPL-3.0](https://raw.githubusercontent.com/Illumina/licenses/master/gpl-3.0.txt).

<i>This README.md is based on notflix but I add some extrea features.<i>

