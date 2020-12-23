# A Lithuanian (Programmers) keyboard

Switching between US and Lithuanian keyboards is pain. Especially when you need to type numbers and symbols.

The default layout is US; the Lithuanian characters are available by holding down the right Alt (AltGr) key.

Thanks to @gintas initial [project](https://github.com/gintas/LitAltGr). However according to [RC](https://www.registrucentras.lt/litwin/keyboard.html) the layout created by @gintas is rather "Lithuanian (Baltic)" but not "Lithuanian (Programmers)".
Source: https://www.registrucentras.lt/litwin/keyboard.html

I've added "Lithuanian (Programmers)" layout, so now it's a mix between "Lithuanian (Baltic)" and "Lithuanian (Programmers)". Lithuanian characters are available on numbers row, but you can also use letter A(+AltGr) to type "Ą" for example.

I've also separated out layouts for US and LT languages. You can use single layout for both languages in Windows, or you might not even need Lithuanian language anymore, but in that case language proofing tools would only work for English. As most applications would not detect your typing language by input text, but they rely on Windows language you still gonna need to switch to LT in order for proofing tools to work in most cases. The good thing is that layout is the same for both languages so you don't need to swith language for typing. Only for proofing tools when you need it.


The Euro sign is also available (AltGr+Shift+").

The keyboard file was generated using Microsoft Keyboard Layout Creator 1.4.

Installation
============
* Run ltprog/setup.exe
* Run usltprog/setup.exe
* Language settings -> English -> Options -> Remove US (QUERTY) *"Lithuanian (AltGr)" should already be there*
* Language settings -> Lithuanian -> Options -> Remove Lithuanian (QUERTY) *"Lithuanian (AltGr)" should already be there*
* Restart PC
