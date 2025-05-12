# Olá! Bem-vindo(a) ao meu portfólio.
## Meu nome é Vinicius Jorge e atualmente estudo Ciência da Computação no CEUB.
## Eu não tenho muitos projetos salvos, pois ainda estou no começo do curso mas, aqui estão alguns exemplos.


# Exercício sobre listas de compras:
l1 = ['abacaxi', 'banana', 'uva']
l2 = []

print("Lista 1:", l1)
print("Lista 2:", l2)

e = input("Qual elemento você deseja transferir da Lista 1 para a Lista 2? ").lower()

if e in l1:
    l1.remove(e) 
    l2.append(e)
    print("Elemento transferido com sucesso.")
else:
    print("Elemento não encontrado na Lista 1.")

print("Lista 2 agora:", l2)
print("Lista 1 agora:", l1)

## link do código: https://colab.research.google.com/drive/1DqWcKf24s9JJrtmICLQl3PZitiYQ2FQ_?usp=sharing

# Exercício sobre advinhar números:
import random
na = random.randint (1,10)

contador = 0
while True:
  e = int(input("Escolha um número de 1 a 10: "))
  contador += 1 
  if e == na:
    break
    
print(f"O número que foi advinhado era {na}, e você precisou {contador} tentativa(s)!")

## link do código: https://colab.research.google.com/drive/1yIvxApjAtuXOqrC102OzfhXoIstBSqAR?usp=sharing

# Equação do 2°Grau EXCEL
https://1drv.ms/x/c/2ecff07048667e91/EboQD8SAz05BimSLbuBnD5YBNrSFJw-wbtbMauumUdF01Q?e=o4dSgV
