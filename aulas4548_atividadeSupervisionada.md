### INF0303_2022/2 - Semana 12 - Dia 25/01/2023 - Encontro 12 - Aulas 45a48 - Atividade Supervisionada

1. Considere o projeto "avaliacao_escolar" disponibilizado em aulas anteriores no SIGAA.
2. Considere os slides disponibilizados para a aula do dia 18/01/2023.
3. Pede-se:

  3.1 Elaborar o GFC do código do método avalia(), implementado na classe Avaliacao.java
  3.2 Identificar os casos de teste necessários para a cobertura do critério todos os caminhos, conforme descrito nos slides. Os casos de testes devem conter os valores da variáveis e indicar qual caminho está cobrindo. O caminho deve ser descrito através da sequencia de nós, por onde o fluxo passa.
  3.2 Calcular a complexidade ciclomática do código do método avalia, conforme fórmula constante dos slides citados.


INSTRUÇÕES:
1. Esta tarefa é individual;
2. Deve ser feita neste mesmo arquivo. Adicione aqui a imagem do GFC.
2. O prazo para entrega é as 23h59min do dia 25/01/2023.

RESPOSTAS
3.1.

![GFC_Avaliação_Escolar](https://user-images.githubusercontent.com/40575125/214726929-33a39af3-ade3-4c07-9b6f-3e02cc25cac7.png)

3.2.

CAMINHO 1: AL : nota1 = -10.00
CAMINHO 2: ABL : nota1 = 11.00
CAMINHO 3: ABCL : nota1 = 2.00, nota2 = -10.00
CAMINHO 4: ABCDL : nota1 = 2.00, nota2 = 11.00
CAMINHO 5: ABCDEL : nota1 = 2.00, nota2 = 9.00, falta = -8.00
CAMINHO 6: ABCDEFL : nota1 = 2.00, nota2 = 9.00, falta = 200.00, carga = 64.00
CAMINHO 7: ABCDEFGL : nota1 = 2.00, nota2 = 9.00, falta = 0, carga = 0
CAMINHO 8: ABCDEFGHIJKL : nota1 = 2.00, nota2 = 9.00, falta = 8.00, carga = 100.00
CAMINHO 9: ABCDEFGHIJKMN : nota1 = 2.00, nota2 = 9.00, falta = 24.00, carga = 64.00
CAMINHO 10: ABCDEFGHIJKMOP : nota1 = 2.00, nota2 = 3.00, falta = 0.00, carga = 64.00
CAMINHO 11: ABCDEFGHIJKMOQRS : nota1 = 6.00, nota2 = 3.00, falta = 0.00, carga = 64.00
CAMINHO 12: ABCDEFGHIJKMOQRT : nota1 = 6.00, nota2 = 9.00, falta = 0.00, carga = 64.00

3.3.

C = ARCOS - NÓS + 2
C = 30 - 20 + 2 = 12
