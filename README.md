# 8.-odev

/*kullan�c�dan bir reel say� alan, bu say� pozitif ise ekranda p negatif ise , s�f�r ise s basan program� yaz�n�z. karakterler d�nmeli.*/

#include<stdio.h>
char tip(void);
int main(void)
{
	printf("sayinin tipi: %c", tip());
	return 0;
}
char tip(void)
{
	double c;
	printf("bir reel sayi giriniz.");
	scanf("%lf" , &c);
	if(c<0)
	return('n');
	else if(c>0)
	return('p');
	else
	return('s');
}
