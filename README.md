# Sheol's build of ST (Simple Terminal)

## Patches

- [Ligatures](https://st.suckless.org/patches/ligatures/) adds proper drawing of ligatures.
- [Bold is not bright](https://st.suckless.org/patches/bold-is-not-bright/) bold text is rendered with a bold font in the bright variant of the current color.
- [Blinking cursor](https://st.suckless.org/patches/blinking_cursor/) allows the use of a blinking cursor.
- [Scrollback](https://st.suckless.org/patches/scrollback/) allow to scroll back through terminal output using Shift+{PageUp, PageDown}.

## Installation for newbs

```
git clone https://github.com/demosheol/st
cd st
sudo make clean install
```
