%{
#include<stdio.h>
%}

%%
[A-Z]+[ \t\n] {printf("%s is a capital letter", yytext);}
. ;
%%
int main()
{
printf("\n Enter the input string:");	
yylex();
}

int yywrap()
{
return 1;
}
output:
C:\Users\manee\OneDrive\Desktop\compiler design>set path=C:\Users\manee\OneDrive\Desktop\compiler design\GnuWin32\bin

C:\Users\manee\OneDrive\Desktop\compiler design>flex capital.l.txt

C:\Users\manee\OneDrive\Desktop\compiler design>set path=C:\Users\manee\OneDrive\Desktop\compiler design\MinGW\bin

C:\Users\manee\OneDrive\Desktop\compiler design>gcc lex.yy.c

C:\Users\manee\OneDrive\Desktop\compiler design> a sample.c

 Enter the input string:CAPITAL Of INDIA is Delhi
CAPITAL  is a capital letterINDIA  is a capital letter
