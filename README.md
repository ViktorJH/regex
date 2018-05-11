# regex

Æfing í reglulegum segðum, til gamans gert.
Regex Íslandi - Kennitölur og bankanúmer.

# Kennitala

[0-7]\d[01]\d{3}[-]*\d{3}[09]

![kennitala regex](https://github.com/ViktorJH/regex/blob/master/images/kennitala.png)

# Bankanúmer

[0145][0134579]\d{2}

Seðlabanki Íslands, Landsbankinn, Arion banki, Íslandsbanki, Kvika:

(0001)|(0[1357]\d{2})

# Kröfunúmer

((0001)|(0[1357]\d{2}))-?66-?\d{6}

# Dagsetning kröfu

[12]\d{3}-?[01][0-9]-?[0123][1-9]

# Cheat sheet

http://emailregex.com/regular-expressions-cheat-sheet/
http://emailregex.com/regex-visual-tester
