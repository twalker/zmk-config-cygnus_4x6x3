# Cygnus 4x6x3 keyboard

This [ZMK](https://zmk.dev/) configuration was copied from [juhakaup/zmk-cygnus-4x6](https://github.com/juhakaup/zmk-cygnus-4x6).

## Default Keymap

### L0: Base

|      |        |       |        |        |         | <- L -- R -> |        |        |        |       |        |      |
| ---- | ------ | ----- | ------ | ------ | ------- | ------------ | ------ | ------ | ------ | ----- | ------ | ---- |
| ESC  | 1      | 2     | 3      | 4      | 5       |              | 6      | 7      | 8      | 9     | 0      | BKSP |
| TAB  | Q      | W     | E      | R      | T       |              | Y      | U      | I      | O     | P      | ENT  |
| CTRL | A/CTRL | S/ALT | D/CMD  | F/SHFT | G       |              | H      | J/SHFT | K/CMD  | L/ALT | ;/CTRL | '    |
| SHFT | Z      | X     | C      | V      | B       |              | N      | M      | ,      | .     | /      | SHFT |
|      |        |       | L3/ESC | L2/TAB | L1/BKSP |              | L1/SPC | L2/DEL | L3/ENT |       |        |      |

### L1: Function

|     |      |     |      |      |      | <- L -- R -> |      |      |      |      |      |     |
| --- | ---- | --- | ---- | ---- | ---- | ------------ | ---- | ---- | ---- | ---- | ---- | --- |
|     | F1   | F2  | F3   | F4   | F5   |              | F6   | F7   | F8   | F9   | F10  | F11 |
|     |      |     |      |      |      |              |      | PGUP | UP   |      | INS  | F12 |
|     | CTRL | ALT | GUI  | SHFT |      |              | HOME | LEFT | DOWN | RIGT | END  |     |
|     | UNDO | CUT | COPY | APP  | PSTE |              | LTAB | PGDN |      |      | RTAB |     |
|     |      |     |      |      |      |              |      |      |      |      |      |     |

### L2: Symbols

|     |     |     |     |     |     | <- L -- R -> |     |     |     |     |     |     |
| --- | --- | --- | --- | --- | --- | ------------ | --- | --- | --- | --- | --- | --- |
|     |     |     |     |     |     |              |     |     |     |     |     |     |
|     | !   | @   | {   | }   | \|  |              | &   | \*  | <   | >   | '   |     |
|     | #   | $   | (   | )   | `   |              | -   | =   | +   | \_  | ;   |     |
|     | %   | ^   | [   | ]   | ~   |              | \   | :   | ,   | .   | /   |     |
|     |     |     |     |     |     |              |     |     |     |     |     |     |

### L3: System

|          |          |          |          |       |        | <- L -- R -> |      |        |          |        |     |     |
| -------- | -------- | -------- | -------- | ----- | ------ | ------------ | ---- | ------ | -------- | ------ | --- | --- |
| BT_SEL 0 | BT_SEL 1 | BT_SEL 2 | BT_SEL 3 |       | BT_CLR |              |      |        |          |        |
|          |          |          |          |       |        |              |      |        | C_VOL_UP |        |     |     |
| ind_bat  | ind_con  |          |          |       |        |              |      | C_PREV | C_PP     | C_NEXT |     |     |
|          |          |          |          |       |        |              |      |        | C_VOL_DN | C_MUTE |     |     |
|          |          |          |          | RESET | BOOT   |              | BOOT | RESET  |          |        |     |     |

* [List of Keycodes](https://zmk.dev/docs/keymaps/list-of-keycodes)
---

### TODO:
- [ ] Add support for zmk studio
- [ ] Verify layout
- [ ] Confirm bluetooth config

---
