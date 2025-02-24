# tangent

My config files regarding my keyboard layout. I use Pine, by ClemenPine:

```
q l c m k  ' f u o y
n r s t w  p h e a i /
j x z g v  b d ; , .
```

I decided not to anglemod it even when using rowstag keyboards because I wanted keys to be in the same place no matter what I was typing on. I found this arrangement acceptable.

When using a regular keyboard, the only extra layer I have is nav on caps. The caps key itself behaves as nav when pressed and esc when tapped. See:

```
f1    f2  f3    f4   f5      f6 f7   f8   f9    f10  f11 f12
_     _   S-tab tab  volup   _  home up   end   _    _
super alt shift ctrl voldown _  left down right bksp del
C-z   C-x C-c   C-v  mute    _  _    _    _     caps
```

Super, Alt, Shift, and Ctrl are one-shot. I thought at first that having one-shot keys on a layer accessed through tap-hold would be awkward, but haven't had problems with it in practice.

## Windows

See `kanata.kbd`. When playing videogames, I just use QWERTY.

If, like me, typing in Spanish is common for you and you hate dead keys, you'll want to check out `engint.klc`, the MSKLC source file for my keyboard layout under Windows. I adapted it from the English International layout that ships with the operating system, but removed all traces of dead keys. Type apostrophes, quotation marks, and tildes without interruption.

A note: the MSKLC source file is for a regular old QWERTY layout. Kanata is the program responsible for shuffling keys around.
