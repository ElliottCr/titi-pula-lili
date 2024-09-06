# titi pula lili
ilu titi pula lu tuki tiki.<br>
A font for the tuki tiki language.

![Showcase](https://github.com/user-attachments/assets/15e022b4-3106-42f4-ba9d-81dcf1243e6a)

This font uses the UCSUR's [sitelen pona](https://www.kreativekorp.com/ucsur/charts/sitelen.html) and [titi pula](https://www.kreativekorp.com/ucsur/charts/titi-pula.html) encodings.

There are two versions of the font:
- `titi-pula-lili.otf` is the regular version, which includes the word to symbol conversion.
- `titi-pula-lili-ucsur.otf` only includes USCUR encodings.

# Usage Guide
Download and install the font, make sure your text editor has ligatures enabled and that autocorrect and capslock are both off.<br>

Type words as you would with letters.<br>
<img src="https://github.com/user-attachments/assets/033d4d77-3c8a-4540-8b9b-484bb560b23e" width="400"><br><br>

Cartouches can be created by putting words or capital letters (which aren't converted to titi pula) between square brackets or `F1990 CARTOUCHE START` and `F1991 CARTOUCHE END`. (Unlike toki pona, the start and end of cartouches are invisible in tuki tiki, there are only lines above and below characters.)<br><br>
`ka [i li lu]`<br>
<img src="https://github.com/user-attachments/assets/ea24a13b-bb9f-488b-9efd-288f0b97631d" width="400"><br><br>

You can combine two or more characters together by putting a dash `-`, a `+` or a zero width joiner it between them.<br>
You can get alternate versions of glyphs by putting a digit or `var1` at the end.<br><br>
`tuki-tiki1`<br>
<img src="https://github.com/user-attachments/assets/5ed73e84-1ab7-40e2-b3c8-c881e31af373" width="400"><br><br>

# Compounds, Variations & Extras

There are over ~150 different compound characters for common word phrases.<br>
I might have to make a list of them some point, for now you can see some examples at the bottom of the main image.<br><br>

Currently, these are the only variations:<br>
`a1`, `a2`, `tuki1`, `tuki-tiki1`, `tuki-tiki2`, `kiku-tuki-tiki1`<br><br>

There's punctuation for `·`, `:`, `「` and `」`. (「」 can be typed with `te` and `to`)

See [nasin-nanpa's ligatures guide](https://github.com/ETBCOR/nasin-nanpa/blob/main/README.md#ligatures-guide) for more information.<br><br>

# AHK Script

I've provided an AHK script to type UCSUR titi pula characters.<br>
You can find more information on how the script works from [nasin-nanpa's AHK Scripts Guide](https://github.com/ETBCOR/nasin-nanpa/tree/main/ahk-script).
