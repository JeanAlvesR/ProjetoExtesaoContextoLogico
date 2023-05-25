**1) Verificação de Elegibilidade Financeira para Mudança de Cidade por Causa da Faculdade**

Um estudante está considerando mudar de cidade para frequentar uma universidade, mas ele precisa verificar se possui condições financeiras para arcar com os custos dessa mudança, levando em conta não apenas a renda familiar, mas também os gastos fixos, o aluguel e os gastos esperados de água, energia e alimentação na nova cidade.

Escreva um programa em C que utilize estruturas condicionais para verificar se o estudante é elegível financeiramente para mudar de cidade com base na renda familiar, nos gastos fixos mensais, no aluguel da nova cidade e nos gastos esperados de água, energia e alimentação.

O programa deve seguir as seguintes especificações:

1. Solicite ao usuário a renda familiar mensal (um valor numérico).
2. Solicite ao usuário o valor do aluguel mensal na nova cidade (um valor numérico).
3. Solicite ao usuário o valor dos gastos fixos mensais da família (um valor numérico).
4. Solicite ao usuário o valor esperado de gastos mensais com água na nova cidade (um valor numérico).
5. Solicite ao usuário o valor esperado de gastos mensais com energia na nova cidade (um valor numérico).
6. Solicite ao usuário o valor esperado de gastos mensais com alimentação na nova cidade (um valor numérico).
7. Utilize uma estrutura condicional (`if`) para verificar a elegibilidade financeira do estudante com base nos seguintes critérios:
   - Se a renda familiar mensal menos os gastos fixos mensais menos o aluguel da nova cidade menos os gastos esperados de água, energia e alimentação na nova cidade for maior ou igual a zero, exiba a mensagem "Elegível financeiramente para mudança de cidade".
   - Caso contrário, exiba a mensagem "Não elegível financeiramente para mudança de cidade".
8. Encerre o programa.

**Exemplo de saída:**

```
Digite a renda familiar mensal: 8000
Digite o valor do aluguel mensal na nova cidade: 2500
Digite o valor dos gastos fixos mensais da família: 1500
Digite o valor esperado de gastos mensais com água na nova cidade: 100
Digite o valor esperado de gastos mensais com energia na nova cidade: 200
Digite o valor esperado de gastos mensais com alimentação na nova cidade: 800

Elegível financeiramente para mudança de cidade
```

**Observações:**

- Certifique-se de solicitar corretamente a renda familiar mensal, o valor do aluguel mensal, os gastos fixos mensais, os gastos esperados de água, energia e alimentação ao usuário.
- Utilize uma estrutura condicional (`if`) para avaliar os critérios de elegibilidade financeira do estudante.
- Exiba a mensagem apropriada com base no resultado da verificação condicional.




**2) Verificação de Elegibilidade para Empréstimo**

Um banco financeiro está avaliando a elegibilidade dos clientes para obter um empréstimo. O banco tem critérios específicos que os clientes devem atender para serem elegíveis.

Escreva um programa em C que utilize estruturas condicionais para verificar se um cliente é elegível para obter um empréstimo com base em sua renda e pontuação de crédito.

O programa deve seguir as seguintes especificações:

1. Solicite ao usuário sua renda mensal (um valor numérico).
2. Solicite ao usuário sua pontuação de crédito (um valor numérico inteiro).
3. Utilize uma estrutura condicional (`if`) para verificar a elegibilidade do cliente com base nos seguintes critérios:
   - Se a renda mensal for maior ou igual a 3000 e a pontuação de crédito for maior ou igual a 700, exiba a mensagem "Cliente elegível para empréstimo".
   - Caso contrário, exiba a mensagem "Cliente não elegível para empréstimo".
4. Encerre o programa.

**Exemplo de saída:**

```
Digite sua renda mensal: 4000
Digite sua pontuação de crédito: 720

Cliente elegível para empréstimo
```

**Observações:**

- Certifique-se de solicitar corretamente a renda mensal e a pontuação de crédito ao usuário.
- Utilize uma estrutura condicional (`if`) para avaliar os critérios de elegibilidade do cliente.
- Exiba a mensagem apropriada com base no resultado da verificação condicional.
