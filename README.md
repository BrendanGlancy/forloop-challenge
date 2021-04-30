This repo is spelled wrong ops

The goal of the fore loop challenge is to add fore loops to clang

for (int i = 0; i < 10; i++) {
    printf("%d\n", i)
}

0-9 output

fore (int i = 0; i < 10; i++) {
     printf("%d\n", i)
}

0
4 
8

Step 1:
Build clang

if we try to run a fore loop in clang
we get this error:
    test.c:4:5: error: implicit declaration of function 'fore' is invalid in C99 [-Werror,-Wimplicit-function-declaration]
    fore (int i = 0; i < 10; i++) {
    ^
test.c:4:11: error: expected expression
    fore (int i = 0; i < 10; i++) {
          ^
2 errors generated.

Think were trying to make a function
