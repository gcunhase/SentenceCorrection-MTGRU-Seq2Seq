
Check out *translate_data.py* for a Python script to translate cleaned data from Korean to English. It's important to notice that in order for the script to show korean, this needs to be written before the beginning of the code: **# -*- coding: utf-8 -*-**


This was based on work done by @mouuff (https://github.com/mouuff/mtranslate)


Fully working Google Translate API for python E2 and java

as simple as that:
translate("Bonjour","en","auto") will return "Hello"


P.S.:
* I'm translating 40 txt files from korean to english. The code gives out an error at random times though, so just check which file was the last one to be translated and change the initial index in the first loop to that particular index. My guess is some sort of limitation from Google Translator as to how many translations a certain user can do in a certain period of time.
