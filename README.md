# Age-in-Days

#include<stdio.h>
int main()
{
    int day,year,month,dia;
    scanf("%d",&day);
    year=day/365;
    month=(day-(year*365))/30;
    dia=day-((year*365)+(month*30));

    printf("%d ano(s)\n",year);
    printf("%d mes(es)\n",month);
    printf("%d dia(s)\n",dia);
    return 0;
}
