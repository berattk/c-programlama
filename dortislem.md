# c-programlama

#include <stdio.h>
#include <stdlib.h>

double a,b;
int main()
{
    printf("Iki sayi gir: ");
    scanf("%lf%lf", &a, &b);
    printf("Toplam: %2.lf\n", a+b);
    printf("Fark: %2.lf\n", abs(a-b));
    printf("Carpim: %2.lf\n", a*b);
    printf("Bolum: %lf\n", a/b);
    return 0;
}
