# Jay's ErgoDox Configuration #

### Features ###

- Based on Programmer Dvorak
    + Programmer Dvorak alphas
    + Single-tap number row for brackets, and other symbols
    + Double-tap number row for numbers
- Mouse keys
- Dynamic Hotkeys
- Layers for Sublime Text and Bohemian Sketch
- Plover layer


### Building ###

#### Ergodox Infinity ####

LEFT HAND:

```bash
make ergodox_infinity:jayliu50
```

Tap the reset button (reverse side) with a toothpick.

```
make ergodox_infinity:jayliu50:dfu-util
```



Repeat, but now with RIGHT HAND:
```bash
make ergodox_infinity:jayliu50 MASTER=right
```

Tap the reset button (reverse side) with a toothpick.

```bash
make ergodox_infinity:jayliu50:dfu-util MASTER=right
```

