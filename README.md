# UP-Layout for Keyboards

Extension of the US keyboard layout with some extra layers, like neo. The idea is, that you have the benefits of the layer system from neo without learning a new mapping.

### Level 3 <CAPS>
Simplifies navigation. The assignment has been kept very much to the familiar configuration of vim, so that little new learning is required and you do not necessarily have to rely on an editor.

### Level 4 <lsgt?!>
Simplifies access to important keys for programming. Here are the brackets at the central positions. This layout is very much oriented towards hipster layouts like Neo.

## Enable the layout

setxkbmap up neo

 ┌─────┐
 │ 2 4 │   2 = Shift       4 = Level 5 (symbols)
 │ 1 3 │   1 = Normal      3 = Level 3 (navigation)
 └─────┘  
┌─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┬─────┲━━━━━━━━━┓
│ ~ ~ │ ! ' │ @ " │ # ˝ │ $ ¸ │ % ˇ │ ^ ^ │ & ˘ │ * ˙ │ (  ̣ │ ) ° │ _ ¯ │ + ˛ ┃ ⌫ Back  ┃
│ ` ` │ 1 ¹ │ 2 ² │ 3 ³ │ 4 « │ 5 € │ 6 ¢ │ 7 − │ 8 × │ 9 ÷ │ 0 » │ - – │ = — ┃  space  ┃
┢━━━━━┷━┱───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┴─┬───┺━┳━━━━━━━┫
┃       ┃ Q ä │ W   │ E   │ R   │ T   │ Y ü │ U   │ I   │ O   │ P ö │ {   │ }   ┃ Enter ┃
┃Tab ↹  ┃ q   │ w   │ e   │ r   │ t   │ y   │ u   │ i   │ o   │ p   │ [   │ ]   ┃   ⏎   ┃
┣━━━━━━━┻┱────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┴┬────┺┓      ┃
┃<CAPS>  ┃ A   │ S ß │ D   │ F   │ G   │ H   │ J   │ K   │ L   │ :   │ "   │ |   ┃      ┃
┃Mod 3   ┃ a   │ s   │ d   │ f   │ g   │ h ← │ j ↓ │ k → │ l → │ ;   │ '   │ \   ┃      ┃
┣━━━━━━━┳┻━━━━┱┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┬┴────┲┷━━━━━┻━━━━━━┫
┃       ┃     ┃ Z   │ X   │ C   │ V   │ B   │ N   │ M   │ <   │ >   │ ? ¿ ┃             ┃
┃Shift ⇧┃Mod 4┃ z   │ x   │ c   │ v   │ b   │ n   │ m   │ ,   │ .   │ / ⁄ ┃   Shift ⇧   ┃
┣━━━━━━━┻━━━━━┻━┳━━━┷━━━┱─┴─────┴─────┴─────┴─────┴─────┴───┲━┷━━━━━╈━━━━━┻━┳━━━━┳━━━━━━┫
┃       ┃       ┃       ┃ ␣                               ⍽ ┃       ┃       ┃    ┃      ┃
┃Ctrl   ┃ super ┃  Alt  ┃ ␣           Space               ⍽ ┃ Mod 4 ┃ Menu  ┃ Fn ┃ Ctrl ┃
┗━━━━━━━┻━━━━━━━┻━━━━━━━┹───────────────────────────────────┺━━━━━━━┻━━━━━━━┻━━━━┻━━━━━━┛
