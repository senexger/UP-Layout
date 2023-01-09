# UP - Keyboardlayout

Extension of the US keyboard layout with some extra layers, like neo. The idea is, that you have the benefits of the layer system from neo without learning a new mapping. But better then de neo qwerty, because the important keys like:
- ;
- :
- ""
- ''
- \#
are way more accessable. Keys like ä,ö,ü,ß can be achieved with layer 4 (originally navigation, but same as us intl)

## Roadmap

- Fix Navigation Layer/Umlaute
	- Understand pseudo layer
- 

## Location

/usr/share/X11/xkb/symbols

## Name

UP stands for Unix-Pool. A Computerpool in the university where I used to work as an admin. But its also "up" than every other layout - at least for me :)

## Wayland Support

Weil mein WM [[Sway]] ist, muss es so designed sein, dass ich es ohne Probleme auch unter Wayland benutzten kann. 

### Recourcen

https://cedaei.com/posts/vim-like-layer-for-xorg-wayland/

## Layout

* [ ] TODO Layout auf dem 'Papier' vervollständigen!
	- [ ] Layer 3 Vimstyle
	- [ ] Layer 4 Coding
	- [ ] Fix: Hide Menubar
- [x] change hotkeys of almost all applications? No
- [ ] Browser vimium extension
- [ ] move up down, should be handled by the keyboard
- [ ] tab left, right
- [ ] move tabs
- [ ] close tabs
- [ ] forward, backward
- [ ] Map left/right click on keyboard, sure?

### Level 3 \<CAP\>

Simplifies navigation. The assignment has been kept very much to the familiar configuration of vim, so that little new learning is required and you do not necessarily have to rely on an editor.

### Level 4 \<lsgt\>

Simplifies access to important keys for programming. Here are the brackets at the central positions. This layout is very much oriented towards hipster layouts like Neo.

┌─────┐
│ 2 4 │   2 = Shift       4 = Level 5 (coding)
│ 1 3 │   1 = Normal      3 = Level 3 (navigation)
└─────┘
#### Insert Mode: Layer 1 + 2
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│ ~   │ ! ' │ @ " │ # ˝ │ $ ¸ │ % ˇ │ ^ ^ │ & ˘ │ * ˙ │ ( ̣  │ ) ° │ _ ¯ │ + ˛ ┃   Back  ┃
│     │ 1 ¹ │ 2 ² │ 3 ³ │ 4 « │ 5 € │ 6 ¢ │ 7 − │ 8 × │ 9 ÷ │ 0 » │ - – │ = — ┃  space  ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃ Q ä │ W   │ E   │ R   │ T   │ Y ü │ U   │ I   │ O   │ P ö │ {   │ }   ┃ Enter ┃
┃Tab    ┃ q   │ w   │ e   │ r   │ t   │ y   │ u   │ i   │ o   │ p   │ [   │ ]   ┃       ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃%<CAPS%>┃ A   │ S ß │ D   │ F   │ G   │ H   │ J ( │ K ) │ L   │ :   │ "   │ |   ┃      ┃
┃Mod 3   ┃ a   │ s   │ d   │ f   │ g   │ h ← │ j ↓ │ k → │ l → │ ;   │ '   │ \   ┃      ┃
┣━━━━━━━┳┻━━━━┱┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┲┷━━━━━┻━━━━━━┫
┃       ┃     ┃ Z   │ X   │ C   │ V   │ B   │ N   │ M   │ <   │ >   │ ? ¿ ┃             ┃
┃Shift  ┃Mod 4┃ z   │ x   │ c   │ v   │ b   │ n   │ m   │ ,   │ .   │ / ⁄ ┃   Shift     ┃
┣━━━━━━━╋━━━━━┻━┳━━━┷━━━┱─┴─────┴─────┴─────┴─────┴─────┴───┲━┷━━━━━╈━━━━━┻━┳━━━━┳━━━━━━┫
┃       ┃       ┃       ┃                                   ┃       ┃       ┃    ┃      ┃
┃Ctrl   ┃ super ┃  Alt  ┃              Space                ┃ Mod 4 ┃ Menu  ┃ Fn ┃ Ctrl ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━┻━━━━━━┛

#### Navigation mode: Nav + alt
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │vim  │     │     │copy │undo │     │     │     │     │     ┃       ┃
┃       ┃     │     │e    │     │     │     │     │     │     │     │     │     ┃       ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃        ┃     │     │     │     │pos1 │   ← │   ↓ │   ↑ │   → │end  │     │     ┃      ┃
┣━━━━━━━┳┻━━━━┱┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┲┷━━━━━┻━━━━━━┫
┃       ┃     ┃     │     │     │     │vim  │     │     │     │     │     ┃             ┃
┃       ┃     ┃     │entf │     │     │b    │     │     │     │     │     ┃             ┃
┣━━━━━━━╋━━━━━┻━┳━━━┷━━━┱─┴─────┴─────┴─────┴─────┴─────┴───┲━┷━━━━━╈━━━━━┻━┳━━━━┳━━━━━━┫
┃       ┃       ┃       ┃                                   ┃       ┃       ┃    ┃      ┃
┃       ┃       ┃       ┃                                   ┃       ┃       ┃    ┃      ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━┻━━━━━━┛

#### Window Manage: Super
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
│     │     │     │     │     │     │     │     │     │     │     │     │     ┃         ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┃       ┃     │     │     │     │     │     │     │     │     │     │     │     ┃       ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃        ┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┃        ┃     │     │     │     │     │     │     │     │     │     │     │     ┃      ┃
┣━━━━━━━┳┻━━━━┱┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┲┷━━━━━┻━━━━━━┫
┃       ┃     ┃     │     │     │     │     │     │     │     │     │     ┃             ┃
┃       ┃     ┃     │     │     │     │     │     │     │     │     │     ┃             ┃
┣━━━━━━━╋━━━━━┻━┳━━━┷━━━┱─┴─────┴─────┴─────┴─────┴─────┴───┲━┷━━━━━╈━━━━━┻━┳━━━━┳━━━━━━┫
┃       ┃       ┃       ┃                                   ┃       ┃       ┃    ┃      ┃
┃       ┃ super ┃       ┃                                   ┃       ┃       ┃    ┃      ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━┻━━━━━━┛