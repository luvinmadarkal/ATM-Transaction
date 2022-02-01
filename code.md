#include<stdio.h>
int main ()
{float x.v;
char ch;
printf ("Enter initial amount\n");
scanf ("%f", &x);
printf ("Enter\ncfor credit\Enter\nd for
debit\nb for balance\n");
scanf ("\n%c", &ch);
switch (ch)
{ case ‘c':
printf ("Enter credit amount\n");
scanf("%F",&v);
x=x+v;
printf ("New Amount=%f",x);
break;
case'd';
printf ("Enter debit amount\n");
scanf ("%f, &v);
If (x>=v) { x=x-v; printf(“New Amount =%f”,x); } else
{ 
printf ("Insufficient amount in your account");
}
break;
printf ("Amount in your account=%f",x);
break;
case'b';
printf ("Amount in your account=%f",x);
break;
default:
printf ("Choose correct option for operation”);
}
}
