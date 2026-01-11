# Les Mysteres du X07 LAssembleur du Canon X07

___
## Introduction

L'objectif est de reprendre les codes sources ici.


## Listings


### page 86


``` Basic
10 CLS: PRINT "Chargement...."
20 FOR X=&HC100 to &H1C3E
30 READ A$:POKE X,VAL("&H"+A$)
35 PRINT A$;" ";
40 NEXT X
45 REM
50 DATA CD,9E,CE,1E,15,CD,25,1C
60 DATA 1E,3C,CD,25,1C,1E,0F,CD
70 DATA 25,1C,1E,0A,CD,25,1C,06
80 DATA FF,1E,2B,CD,25,1C,1E,2C
90 DATA CD,25,1C,10,F4,F5,C5,D5
92 DATA OE,F1,CD,C0,C9,3A,6C,02
95 DATA F6,80,D3,F0,ED,59,3E,02
98 DATA D3,F5,D1,C1,F1,C9,00,00
99 DATA 00,00,00,00,00,00,00,00
```

```asm
Code assembleur à mettre
```


___