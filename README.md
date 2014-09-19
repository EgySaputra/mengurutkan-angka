mengurutkan-angka
=================
#include <stdio.h>
#include <conio.h>
//Mengurutan angka dari yang terkecil ke yang terbesar
int main ()
{ int a= 10, b= 2, c= 9, hasil;
if (a>b)
    {   hasil=a;
        a=b;
        b=hasil; }
    if (a>c)
    {   hasil=a;
        a=c;
        c=hasil; }
    if (b>c)
    {   hasil=b;
        b=c;
        c=hasil; }
        printf("\n\nHasil Pengurutan angka menjadi %d %d %d", a, b, c);

}
