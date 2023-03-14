#include <stdio.h>
#include <math.h>
int main()
{
    float priceA, cash, cost;
    int itemA_Ammount;
    printf ("introduzca el precio de A:\n");
    fflush (stdin);
    scanf ("%f", &priceA);
    printf ("introduzca la cantidad:\n"); 
    fflush (stdin);
    scanf ("%d", &itemA_Ammount);
    cost=priceA*itemA_Ammount;
    printf ("debe pagar %0.2f cup.\n", cost);
    printf ("ingrese el dinero que pagara:\n");
    fflush (stdin);
    scanf ("%f", & cash);
    printf ("el vuelto es: %0.2f", cash-cost);
    return 0;
}
