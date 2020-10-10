<img src=st.svg>

This is my fork of the [simple terminal](https://st.suckless.org), one of many [suckless](https://suckless.org) software.

## Installing

```sh
make && sudo make install && make clean
```

## Shortcuts

Every shortcut is described in the man page. I try to keep it updated as much as possible.

## Patches

This build of st uses the following patches (in order of when they were applied, from oldest to newest):

+ [boxdraw\_v2](https://st.suckless.org/patches/boxdraw) - Changes the way line, block and braille characters are rendered for gapless alignment.
