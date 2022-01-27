# NotFlix - Stream Movies & TV Shows

## Dependencies
* peerflix - stream torrents
* mpv - video player

## How to install?
First install the dependencies.

Peerflix
```bash
~ $ sudo npm install -g peerflix
```

mpv - Video Player
```bash
~ $ sudo apt install mpv
```

Then copy & paste notflix file inside `.local/bin/` directory.
```bash
~/Download/notflix $ cp notflix ~/.local/bin/
```

Change directory to `.local/bin/`.
```bash
~/Download/notflix $ cd ~/.local/bin/
```

Now make the `notflix` file an executable.
```bash
~/.local/bin $ chmod +x notflix
```

## How to use?
Always use double quotes.
```bash
~ $ notflix "movie name"
```