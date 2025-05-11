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
