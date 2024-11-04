# Operacoes-aritmeicas-python
Exercícios aritméticos em python (validados e corrigidos)
# Exercício 1
Criar variáveis n1 e n2 que receberão inputs do tipo INT do usuário. (não se esqueça de tratar o que está sendo recebido rsrs) 
Exibir o resultado da Adição dessas 2 variáveis. Exibir o resultado da Subtração dessas variáveis. 
Exibir o resultado da Multiplicação dessas variáveis. 
Exibir o resultado da Divisão dessas variáveis. 
Exibir o resultado do Módulo (Resto da divisão) entre essas variáveis. 
Exibir o resultado de uma variável Exponenciando a outra. [ ]

-- Resultado Esperado
    #N1: 7
    #N2: 5
    #12
    #2
    #35
    #1.4
    #2
    #16807

n1 = int(input("Digite o primeiro número(n1) "))

n2 = int(input("Digite o segundo número(n2)  "))

soma = n1 + n2

subtracao = n1-n2

multiplicacao = n1 * n2

divisao = n1 / n2

resto = n1 % n2

potencia = n1 ** n2

print (f"Exibir resultado da Adição: {soma}" )

print (f"Exibir resultado da Subtração: {subtracao}")

print (f"Exibir resultado da multiplicação: {multiplicacao}")

print (f"Exibir resultado da divisão: {divisao}")

print (f"Exibir resultado da Resto da divisão: {resto}")

print (f"Exibir resultado da potência: {potencia}")

----------------------------------------------------------------------------------------------------------------------------------------------------------

# Exercício 2

Faça um programa que o usuário digita um valor inteiro e nós mostramos toda a tabuada daquele número.

numero=int(input("digite um numero inteiro: "))

for i in range(1,11): -- for cria um espécie de laço, onde o número percorre, enquanto "i" pe uma variável temporária; e range (1,11) informa onde começa e onde termina

   resultado = numero * i
   
   print(f"{numero} x {i} = {resultado}")

---------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Exercício 3

Faça um programa no qual o usuário digite a distância percorrida por um carro e a qtd de litros de combustível gasto.

Calcule e mostre para o usuário quantos km/l o seu carro faz.

distancia = int(input("digite a distância percorrida pelo seu carro: "))

combustivel = int(input("digite a quantidade de litros gastos: "))

consumo = distancia / combustivel
print (f"O seu carro fez: {consumo}")
