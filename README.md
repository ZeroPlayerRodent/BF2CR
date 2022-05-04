# BF2CR
Brainfuck to Crystal compiler! (Written in [Uzumaki](https://esolangs.org/wiki/Uzumaki).)

# Usage
Paste your brainfuck code (with no newlines) into the terminal, and insert a "!" at the beginning. After hitting enter, the compiler/transpiler will shit out a nasty glob of hellishly unoptimized Crystal code.

Example:

```!.+[.+]```

Will produce...

```t=Array.new 3000,0;p=0;print t[p].chr;t[p]+=1;while t[p]%256!=0;print t[p].chr;t[p]+=1;end;```

Nasty...
