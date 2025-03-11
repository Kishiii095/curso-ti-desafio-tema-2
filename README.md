# curso-ti-desafio-tema-2
# Super Trunfo - Comparação de Países

Este programa é um jogo simples de Super Trunfo baseado em países. O usuário insere as características de dois países e escolhe um atributo para comparação. O programa determina qual país vence com base no atributo selecionado.

## Funcionalidades
- Entrada dos dados de dois países pelo usuário.
- Menu interativo com `switch case` para escolher o atributo de comparação.
- Comparação dos atributos e exibição do vencedor.
- Regra especial: para "Densidade Demográfica", o menor valor vence.

## Como Compilar e Executar

1. Salve o código em um arquivo, por exemplo, `super_trunfo.c`.
2. Compile o código usando GCC:
   ```sh
   gcc super_trunfo.c -o super_trunfo
   ```
3. Execute o programa:
   ```sh
   ./super_trunfo
   ```

## Entrada de Dados
O programa solicitará os seguintes dados para cada país:
- Nome (string)
- População (int)
- Área (float)
- PIB (float)
- Pontos turísticos (int)

Em seguida, o usuário deve escolher um atributo para comparação.

## Opções do Menu
```
1 - População
2 - Área
3 - PIB
4 - Pontos Turísticos
5 - Densidade Demográfica
```

## Exemplo de Uso
```
Digite os dados do primeiro país:
Nome: Brasil
População: 213000000
Área: 8515767
PIB: 2.05
Pontos Turísticos: 10

Digite os dados do segundo país:
Nome: Argentina
População: 45000000
Área: 2780400
PIB: 0.64
Pontos Turísticos: 8

Escolha o atributo para comparação:
1 - População
2 - Área
3 - PIB
4 - Pontos Turísticos
5 - Densidade Demográfica
Digite o número da opção desejada: 1

Comparação pelo atributo: População
Brasil: 213000000
Argentina: 45000000
Vencedor: Brasil
```

## Observações
- O programa utiliza `scanf` para entrada de dados e `printf` para exibição de mensagens.
- O `switch case` permite ao usuário escolher o atributo de comparação.
- O `default` exibe uma mensagem caso o usuário escolha uma opção inválida.

Divirta-se jogando Super Trunfo de Países! 🌍✨

