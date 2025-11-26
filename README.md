
## This is a fork of Cyneprepou4uk NES Games Disassembly

They are modified by LiQuiDz to work with Mesen HD Patch (NEA Audio - similar to MSU-1)

https://liquidzretrogaming.net/

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------







-------
Forked:

# NES Games Disassembly

Each source code is equal to the original ROM, compilable and editable.

All of them were made with my [BZK 6502 Disassembler](https://github.com/cyneprepou4uk/BZK-6502-Disassembler) scripts.

You can contact me at [RHDN](https://www.romhacking.net/forum/index.php?topic=32220.0) topic.



## How to build a disassembly

### Windows

No special requirements. Just launch `assemble.bat` and wait until it's done.

### Any other OS

Try using `sh assemble.sh` in terminal instead. All credits goes to [gb-2312](https://github.com/gb-2312).

Do not delete or edit `_scripts` and `_install_packages` folders, unless you know how it works.



## Syntax highlighting

Use `syntax_6502.xml` to highlight code in [Notepad++](https://notepad-plus-plus.org/).

Go to Language -> User Defined Language -> Define your language -> Import.



## How to edit a disassembly

Important comments are marked with `bzk` text. Start with deleting garbage to free up some space.

And don't worry about stuff like `C - - - - - 0x00009C 00:C08C: A9 00     LDA #$00`.

`preparations.lua` script will take care of it before compilation. You just write new code as usual, like this `LDA #$00`.

You can manually delete this text with `.\s.\s.\s.\s.\s.\s0x0........:....:\s..\s..\s..\s\s` regex if necessary.
