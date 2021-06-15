# maior_menor_while
Lista de valores com laço de repetição
print("Exercicio 04- Maior, Menor e Média ")
contador = 1
soma = maior = menor = 0

while contador  <=10:
   print (contador, "ª valor: ")
   valor = float(input())
   soma += valor
   media = soma / contador
   contador += 1
   maior = maior if maior !=0 and maior > valor else valor
   menor = menor if menor !=0 and menor < valor else valor



print(f"A soma dos valores informados  é {soma}")
