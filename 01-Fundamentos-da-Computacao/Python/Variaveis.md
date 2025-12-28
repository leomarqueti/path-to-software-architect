# 📦 Aula 01: O Conceito de Variáveis

A primeira coisa que vamos aprender são as **Variáveis**.

O computador tem **memória de peixe**. Ele esquece tudo muito rápido. Por isso, precisamos usar variáveis para "tatuar" na memória dele as informações que iremos usar depois.

> 💡 **Analogia:** Pense na variável como uma **caixa** onde conseguimos guardar alguma coisa e colar uma etiqueta com um nome nela.

Vamos guardar o meu nome: **Léo**.

## Visualizando o Processo

```mermaid
sequenceDiagram
    participant Eu as Programador
    participant Caixa as Variável (Memória)
    
    Note over Eu, Caixa: O processo de Atribuição
    Eu->>Caixa: Envio o valor "Léo"
    Caixa-->>Caixa: Guardo na etiqueta 'nome'
Como escrever em Python?
Em Python, a sintaxe é direta. Primeiro escrevemos o nome da etiqueta (o nome da variável), no nosso caso:

nome

Depois, usamos o caractere de igual (=), que em programação NÃO significa comparação, mas sim ATRIBUIÇÃO (ou "recebe").

Então, nossa variável nome vai receber (=) o valor "Léo".

O Código:
Python

nome = "Léo"
Viu só como é fácil? Além de nomes (texto), podemos guardar números, booleanos (Verdadeiro/Falso) e muito mais.

⚠️ Detalhe Importante: As Aspas
Perceba que eu coloquei meu nome entre aspas: "Léo".

Esse é o método que usamos para o Python entender que estamos enviando um Texto (String) para ele. As aspas dizem para o computador: "Ei, isso aqui é um bloco de texto, não tente calcular nada, apenas guarde as letras."

📝 Resumo da Aula
Nessa aula, aprendemos como passar uma informação para a memória do computador.

🚀 Próxima Aula: Vamos aprender como fazer o computador "falar" com a gente usando o comando print e faremos nossa primeira interação real!


---

