# CFG Style Testing


``` title="null.cfg" linenums="1"
bind W "+mfwd"
bind S "+mback"
bind A "+mleft"
bind D "+mright"

alias +mfwd "-back; +forward"
alias +mback "-forward; +back"
alias +mleft "-moveright; +moveleft"
alias +mright "-moveleft; +moveright"
alias -mfwd "-forward"
alias -mback "-back"
alias -mleft "-moveleft"
alias -mright "-moveright"
```
