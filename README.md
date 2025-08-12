# Calculadora de Média Escolar

## Descrição
Este programa em Python solicita ao usuário o nome do aluno e três notas. Em seguida, calcula a média aritmética dessas notas e exibe o resultado com o nome do aluno.

## Como usar
1. Execute o programa.
2. Digite o nome do aluno quando solicitado.
3. Digite a primeira, segunda e terceira nota, uma por vez.
4. Veja a média das notas exibida junto com o nome do aluno.

## Código

```python
nome = input ("digite o nome do seu amg ")
nota1 = float(input("Digite a primeira nota "))
nota2 = float(input("Digite a segunda nota "))
nota3 = float(input("Digite a terceira nota "))

media = (nota1 + nota2 + nota3) /3 
print(f"O nome do aluno é : {nome} e a media é: {media: .1f}")
