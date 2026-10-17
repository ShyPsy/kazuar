# Default Layout Reference

> [!TIP]
> The source XML definitions for all default layouts are located in the repository under [`app/src/main/res/xml/`](../app/src/main/res/xml/). You can use these XML files directly as templates for creating custom layouts:
> - **Russian V4**: [`rows_east_slavic_v4.xml`](../app/src/main/res/xml/rows_east_slavic_v4.xml)
> - **Russian V3**: [`rows_east_slavic_v3.xml`](../app/src/main/res/xml/rows_east_slavic_v3.xml)
> - **Russian V2**: [`rows_east_slavic_v2.xml`](../app/src/main/res/xml/rows_east_slavic_v2.xml)
> - **Russian V1**: [`rows_east_slavic.xml`](../app/src/main/res/xml/rows_east_slavic.xml)
> - **English V4**: [`rows_qwerty_v4.xml`](../app/src/main/res/xml/rows_qwerty_v4.xml)
> - **English V3**: [`rows_qwerty_v3.xml`](../app/src/main/res/xml/rows_qwerty_v3.xml)
> - **English V2**: [`rows_qwerty_v2.xml`](../app/src/main/res/xml/rows_qwerty_v2.xml)
> - **English V1**: [`rows_qwerty.xml`](../app/src/main/res/xml/rows_qwerty.xml)
> - **Symbols V4**: [`rows_symbols_v4.xml`](../app/src/main/res/xml/rows_symbols_v4.xml)
> - **Symbols V3**: [`rows_symbols_v3.xml`](../app/src/main/res/xml/rows_symbols_v3.xml)
> - **Edit Mode**: [`rows_editing.xml`](../app/src/main/res/xml/rows_editing.xml)

# V1

Languages:
Russian layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ----- |
| й   | б   | у   | к   | е   | н   | г   | ш   | з   | х     |
| ж   | ы   | в   | а   | п   | р   | о   | л   | д   | bcspc |
| я   | ч   | с   | м   | spc | spc | и   | т   | ь   | ent   |

| !    | "   | №    | ;     | %   | :   | ?   | *   | (   | )   |
| ---- | --- | ---- | ----- | --- | --- | --- | --- | --- | --- |
| :    | "   | ~    |       |     | /   | _   | +   | [   | ]   |
| ;    | '   | `    |       |     | \   | -   | =   | \|  |     |
| undo | cut | copy | paste | spc | spc | <   | >   | ,   |     |

English layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0    |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ---- |
| q   | w   | e   | r   | t   | y   | u   | i   | o   | p    |
| a   | s   | d   | f   | g   | h   | j   | k   | l   | bspc |
| z   | x   | c   | v   | spc | spc | b   | n   | m   | ent  |

| !    | @   | #    | $     | %   | ^   | ?   | *   | (   | )   |
| ---- | --- | ---- | ----- | --- | --- | --- | --- | --- | --- |
| :    | "   | ~    |       |     | /   | _   | +   | [   | ]   |
| ;    | '   | `    |       |     | \   | -   | =   | \|  |     |
| undo | cut | copy | paste | spc | spc | <   | >   | ,   |     |

Double Tap:

| Original text | Auto-replace |
| ------------- | ------------ |
| ЫЫ            | Ю            |
| ЬЬ            | Ъ            |
| ШШ            | Щ            |
| ЙЙ            | Э            |
| ЧЧ            | Ф            |
| ХХ            | Ц            |
| ⎵⎵            | .⎵           |
| --            | —            |

Gestures:

| Gesture                   | Action          |
| ------------------------- | --------------- |
| Left to right             | Editing layout  |
| Right to left             | Switch language |
| Swipe left from Backspace | Delete word     |
| Bottom to top             | Shift           |
| Top to bottom             | Enter           |

# V2

Languages:
Russian layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| й   | ц   | у   | к   | е   | н   | г   | ш   | з   | х   |
| ф   | ы   | в   | а   | п   | р   | о   | л   | д   | ж   |
| я   | ч   | с   | м   | spc | spc | и   | т   | ь   | б   |

| !      | @   | №    | $    | %   | ^    | ?   | *   | (   | )     |
| ------ | --- | ---- | ---- | --- | ---- | --- | --- | --- | ----- |
| ~`     | "   | #    | :    | ;   | redo | _   | +   | [{« | ]}»   |
| selAll | '   | &    | ;    | /   | \|   | \   | -   | =   | bcspc |
| undo   | cut | copy | past | spc | spc  | <   | >   | ,   | .     |

English layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| q   | w   | e   | r   | t   | y   | u   | i   | o   | p   |
| a   | s   | d   | f   | g   | h   | j   | k   | l   | '   |
| z   | x   | c   | v   | spc | spc | b   | n   | m   | /   |

| !      | @   | №    | $    | %   | ^    | ?   | *   | (   | )     |
| ------ | --- | ---- | ---- | --- | ---- | --- | --- | --- | ----- |
| ~`     | "   | #    | :    | ;   | redo | _   | +   | [{« | ]}»   |
| selAll | '   | &    | ;    | /   | \|   | \   | -   | =   | bcspc |
| undo   | cut | copy | past | spc | spc  | <   | >   | ,   | .     |

"[{«" three characters on one button, hold to select one of the three.
" ]}»" three characters on one button, hold to select one of the three.
"\|" is simply "|"

Double Tap:

| Original text | Auto-replace |
| ------------- | ------------ |
| ЫЫ            | Ю            |
| ЬЬ            | Ъ            |
| ШШ            | Щ            |
| ЙЙ            | Э            |
| ⎵⎵            | .⎵           |
| --            | —            |

Gestures:

| Gesture       | Action          |
| ------------- | --------------- |
| Left to right | Editing layout  |
| Right to left | Switch language |
| Bottom to top | Shift           |
| Top to bottom | Enter           |

# V3

Languages:
Russian layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ----- |
| й   | ц   | у   | к   | е   | н   | г   | ш   | з   | х     |
| ж   | ы   | в   | а   | п   | р   | о   | л   | д   | bcspc |
| я   | ч   | с   | м   | spc | spc | и   | т   | ь   | б     |

| !      | @²  | №³   | $    | %°  | ^    | ?   | *•× | (   | )        |
| ------ | --- | ---- | ---- | --- | ---- | --- | --- | --- | -------- |
| ~`     | "   | #    | :    | ё\| | redo | &   | +±  | [{« | ]}»      |
| selAll | '   |      | ;    | /÷  | ,    | .   | -—_ | =≈≠ | del word |
| undo   | cut | copy | past | spc | spc  | <   | >   |     |          |

English layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ----- |
| q   | w   | e   | r   | t   | y   | u   | i   | o   | p     |
| a   | s   | d   | f   | g   | h   | j   | k   | l   | bcspc |
| z   | x   | c   | v   | spc | spc | b   | n   | m   | /     |

| !      | @²  | №³   | $    | %°  | ^    | ?   | *•× | (   | )        |
| ------ | --- | ---- | ---- | --- | ---- | --- | --- | --- | -------- |
| ~`     | "   | #    | :    | \|  | redo | &   | +±  | [{« | ]}»      |
| selAll | '   |      | ;    | /÷  | ,    | .   | -—_ | =≈≠ | del word |
| undo   | cut | copy | past | spc | spc  | <   | >   |     |          |

"[{«" three characters on one button, hold to select one of the three.
" ]}»" three characters on one button, hold to select one of the three.

Double Tap:

| Original text | Auto-replace |
| ------------- | ------------ |
| ЫЫ            | Ю            |
| ЬЬ            | Ъ            |
| ШШ            | Щ            |
| ЙЙ            | Э            |
| ЧЧ            | Ф            |
| ⎵⎵            | .⎵           |
| --            | —            |

# V4

Languages:
Russian layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ----- |
| й   | б   | у   | к   | е   | н   | г   | ш   | з   | х     |
| ж   | ы   | в   | а   | п   | р   | о   | л   | д   | bcspc |
| я   | ч   | с   | м   | spc | spc | spc | и   | т   | ь     |

English layout:

| 1   | 2   | 3   | 4   | 5   | 6   | 7   | 8   | 9   | 0     |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | ----- |
| q   | w   | e   | r   | t   | y   | u   | i   | o   | p     |
| a   | s   | d   | f   | g   | h   | j   | k   | l   | bcspc |
| z   | x   | c   | v   | spc | spc | spc | b   | n   | m     |

Double Tap:

| Original text | Auto-replace |
| ------------- | ------------ |
| ЫЫ            | Ю            |
| ЬЬ            | Ъ            |
| ШШ            | Щ            |
| ЙЙ            | Э            |
| ЧЧ            | Ф            |
| ХХ            | Ц            |
| ⎵⎵            | .⎵           |
| --            | —            |

# Edit

| del | home  | up     | end   | backspc        |
| --- | ----- | ------ | ----- | -------------- |
| Tab | right | select | left  | backspace word |
| Cut | copy  | down   | paste | select all     |
| ABC | undo  | spc    | redo  | enter          |

Source: [`rows_editing.xml`](../app/src/main/res/xml/rows_editing.xml). Can be customized via custom XML (`layer="editing"` in root tag) and loaded via settings.

# User Layers (usr0, usr1, usr2)

Kazuar supports up to 3 customizable user layers (`usr0`, `usr1`, `usr2`), empty by default:
- **usr0**: Triggered via `!code/key_switch_to_usr0` (code `-343`)
- **usr1**: Triggered via `!code/key_switch_to_usr1` (code `-344`)
- **usr2**: Triggered via `!code/key_switch_to_usr2` (code `-345`)

### Layer Switching & Toggle Behavior:
- **Toggle**: Pressing the switch key (e.g. `!code/key_switch_to_edit` or `!code/key_switch_to_usr0`) switches to that layer. Pressing the same switch key again returns to the previous alphabet layout.
- **Direct Switch**: Pressing another layer's switch key (e.g. going from `usr0` to `usr1` or to `edit`) switches directly to that target layer.
- **Return to Alphabet**: Pressing `!code/key_switch_to_abc` (code `-346`) or standard symbol switch (`?123`) from any editing or user layer immediately returns to the alphabet layout.
- **Empty Fallback**: If a user layer is empty / not loaded, it opens [`kbd_user_empty.xml`](../app/src/main/res/xml/kbd_user_empty.xml) containing an "ABC" key to safely return to the alphabet layout.
