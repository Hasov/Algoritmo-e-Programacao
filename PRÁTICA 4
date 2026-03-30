/*Ateliê de Costura (Cálculo de soma, subtração, multiplicação e divisão)
Briefing: (L = R - C)
Cliente encomenda um vestido de 8 metros, 1 tecido custa 40 reais e 1 vestido custa 
100 reais por metro
margem de lucro estimada pela estilista: 40% a mais do valor do custo;*/

#include <stdio.h>
#include <conio.h>
int main()
{
  float metros = 8;
  float tecido_preço = 40;
  float vestido_tamanho_preço = 100; 
  
  float lucro, receita, custo, margem_lucro;
  
  receita = metros * vestido_tamanho_preço + tecido_preço;
  custo = metros * tecido_preço + vestido_tamanho_preço;
  lucro = receita - custo;
  margem_lucro = custo * 0.4 + custo;
  
  
  printf("Lucro: R$%.2f\n", lucro);
  printf("Receita: R$%.2f\n", receita);
  printf("Custo: R$%.2f\n", custo);
   printf("Lucro Almejado: R$%.2f\n", margem_lucro);
  
  if (lucro != custo && margem_lucro > custo) {
      printf("A estilista conseguiu cobrir os custos", margem_lucro);
  } else {
      //printf("\x1b[91mEste texto é vermelho brilhante!\x1b[0m\n");
      printf("\x1b[91mA estilista não conseguiu cobrir os custos\x1b[0m\n", margem_lucro);
  }
}
