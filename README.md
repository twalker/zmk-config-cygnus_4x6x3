# Cygnus 4x6x3 keyboard

This [ZMK](https://zmk.dev/) configuration was copied from [juhakaup/zmk-cygnus-4x6](https://github.com/juhakaup/zmk-cygnus-4x6).

## Default Keymap

### Base layer

|      |     |     |        |        |         | <- L -- R -> |        |        |        |     |     |      |
| ---- | --- | --- | ------ | ------ | ------- | ------------ | ------ | ------ | ------ | --- | --- | ---- |
| ESC  | 1   | 2   | 3      | 4      | 5       |              | 6      | 7      | 8      | 9   | 0   | BKSP |
| TAB  | Q   | W   | E      | R      | T       |              | Y      | U      | I      | O   | P   | ENT  |
| CTRL | A   | S   | D      | F      | G       |              | H      | J      | K      | L   | ;   | '    |
| SHFT | Z   | X   | C      | V      | B       |              | N      | M      | ,      | .   | /   | SHFT |
|      |     |     | L3/ESC | L2/TAB | L1/BKSP |              | L1/SPC | L2/DEL | L3/ENT |     |     |      |

### Lower layer

|       |     |     |        |        |         | <- L -- R -> |        |        |        |     |     |      |
| ----- | --- | --- | ------ | ------ | ------- | ------------ | ------ | ------ | ------ | --- | --- | ---- |
| TAB   | F1  | F2  | F3     | F4     | F5      |              | F6     | F7     | F8     | F9  | F10 | BKSP |
| TAB   | 1   | 2   | 3      | 4      | 5       |              | 6      | 7      | 8      | 9   | 0   | BKSP |
| BTCLR | BT1 | BT2 | BT3    | BT4    | BT5     |              | LFT    | DWN    | UP     | RGT |     |      |
| SHFT  |     |     |        |        |         |              |        |        |        |     |     |      |
|       |     |     | L3/ESC | L2/TAB | L1/BKSP |              | L1/SPC | L2/DEL | L3/ENT |     |     |      |

### Raise layer

|      |     |     |     |     |     | <- L -- R -> |     |     |     |     |     |      |
| ---- | --- | --- | --- | --- | --- | ------------ | --- | --- | --- | --- | --- | ---- |
| TAB  | !   | @   | #   | $   | %   |              | ^   | &   | \*  | (   | )   | BKSP |
| CTRL |     |     |     |     |     |              | -   | =   | [   | ]   | \   | `    |
| SHFT |     |     |     |     |     |              | \_  | +   | {   | }   | \|  | ~    |
|      |     |     | GUI |     | SPC |              | ENT |     | ALT |     |     |      |

### Bluetooth layer

|          |          |          |          |     |            | <- L -- R -> |     |     |     |     |     |     |
| -------- | -------- | -------- | -------- | --- | ---------- | ------------ | --- | --- | --- | --- | --- | --- |
| BT_SEL 0 | BT_SEL 1 | BT_SEL 2 | BT_SEL 3 |     | &bt BT_CLR |              |     |     |     |     |     |     |
| BT_SEL 0 | BT_SEL 1 | BT_SEL 2 | BT_SEL 3 |     | &bt BT_CLR |              |     |     |     |     |     |     |
| ind_bat  | &ind_con |          |          |     |            |              |     |     |     |     |     |     |
|          |          |          |          |     |            |              |     |     |     |     |     |     |
|          |          |          |          |     |            |              |     |     |     |     |     |     |
