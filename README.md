# Exercicio25

#include <stdlib.h>
#include <stdio.h>

int main (void)
{
  system ("color 0b");

  char frase1[50],frase2[50];
  int i;

  printf("Digite uma frase ");
  gets(frase1);

  for (i=0; i<=49; i++)
  {
      frase2[i]=frase1[i];
  }

  printf("%s",frase2);
return 0;
}

