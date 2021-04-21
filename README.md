# split_preonic

This is a place to store something I'm working on, I have used the Let's Split codebase and inserted the Preonic's key maps.
MIDI has been deleted


special thanks to https://github.com/alexisphilip/masplit as I used his code as a base.

Compile the firmware.

```cmd
make split_preonic/rev1:default:avrdude
```

Then flash the right MCU.

```cmd
make split_preonic/rev1:avrdude-split-right
```

Then do the same for left MCU.

```cmd
make split_preonic/rev1:avrdude-split-left
