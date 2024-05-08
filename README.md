# ***1 - Crie um programa para efetuar a leitura de um número inteiro e apresentar o resultado do quadrado deste número.***
numero1 = int(input("digite um numero"))
leitura = (numero1*2)
print(leitura)





# ***2 -
# Crie duas variáveis para armazenar seu primeiro nome e sobrenome. Em seguida, concatene-as para formar seu nome completo e exiba o resultado.***
nome = input('Digite seu nome')
sobrenome = input('Digite seu sobrenome')
resultado = (nome+' '+sobrenome)
print(resultado)


# ***3 -
# Peça ao usuário para digitar dois números inteiros e armazene-os em variáveis. Realize a concatenação desses números como strings e exiba o resultado.***
numero1 = int(input('Digite um numero'))
numero2 = int(input('Digite outro numero'))
#transformando numeros em tipo texto(strings)
n1 = str(numero1)
n2 = str(numero2)
print(type (n1), type (n2))
print(n1,n2)




# ***4 -
# Crie uma variável para armazenar a palavra "Python". Em seguida, adicione um número inteiro ao final da palavra usando a concatenação e exiba o resultado.***
variavel = 'Python'
numero = 1
concatenacao = (variavel, numero)
print(concatenacao)





# ***5 -
# Declare uma variável contendo uma frase. Em seguida, peça ao usuário para digitar uma palavra e concatene essa palavra no final da frase. Exiba o resultado.***
frase = "A vingança nunca é plena, mata a alma e a envenena"
palavra = input('Digite uma palavra:')
concatene = (frase +' '+palavra)
print(concatene)
