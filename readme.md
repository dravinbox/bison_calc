------------------运行----------------------
bison rpcalc.y
gcc -o rpcalc -lm rpcalc.tab.c
./rpcalc
4 9 +



------------------运行----------------------
bison calc.y
gcc -o calc -lm calc.tab.c
./calc
8*(1+3)
　　　　  32
