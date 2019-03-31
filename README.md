# switch-libpython-example
Basic example/test for using libpython from a nintendo switch homebrew application

# Setup

## Install switch-libpython

```sh
git clone https://github.com/nx-python/switch-libpython
cd switch-libpython
makepkg -si
```

Then, copy `/opt/devkitpro/portlibs/switch/lib/python3.8/` to `/lib/python3.8/` on your Switch SD card.

## Build switch-libpython-example

```sh
git clone https://github.com/nx-python/switch-libpython-example
cd switch-libpython-example
make
```

Then run `switch-libpython-example.nro` on your Switch!
