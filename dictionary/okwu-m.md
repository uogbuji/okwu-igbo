
# m

Technical note:

A problem using acute and grave accents as tonal markers in Igbo orthography is that M̀/m̀ seems to have sketchy support in text entry systems. These are not in the Unicode Latin Extended Additional Block block. No such problem with Ḿ/ḿ, oddly.

Breakdown of combining characters required, from Python interactive prompt:

>>> s = 'M̀'; print('|'.join([ hex(ord(c)) for c in s ]))
0x4d|0x300
>>> s = 'm̀'; print('|'.join([ hex(ord(c)) for c in s ]))
0x6d|0x300
>>> s = 'M̀'; print('|'.join([ http://unicodedata.name (c) for c in s ]))
LATIN CAPITAL LETTER M|COMBINING GRAVE ACCENT
>>> s = 'm̀'; print('|'.join([ http://unicodedata.name (c) for c in s ]))
LATIN SMALL LETTER M|COMBINING GRAVE ACCENT

## ḿbà

n. town, city, country, foreign lands, abroad

* cite: [Wiki-IP]

## ḿmírí

n. water


