### INF0303_2022/2 - Semana 05 - Dia 23/11/2022 - Encontro 05 - Aulas 17a20 - Tarefa Prática

**DEFINIÇÃO**:
1. Definir um conjunto de classes de Equivalência e um conjunto de casos de testes derivados, para testar a seguinte função de avaliação universitária.
2. A função avaliação, recebe como parâmetros os seguintes dados:
   2.1. **nota1** (numérico de ponto flutuante com duas casas decimais);
   2.2. **nota2**  (numérico de ponto flutuante com duas casas decimais);
   2.3. **cargaHoraria** (numérico inteiro, positivo);
   2.4. **faltas** (numérico inteiro, positivo).
3. Antes de efetuar qualquer cálculo, o sistema deverá validar os dados de entrada do usuário. Se algum destes valores for inválido, o sistema deve retornar a mensagem **Valores Inválidos**.
4. A forma de calcular a avaliação é a seguinte:

  4.1. Se a quantidade de faltas for superior a 25% da carga horária, o aluno estará reprovado por falta. Neste caso a função retorna a seguinte mensagem **Reprovado por Falta**;

  4.2. Estando o aluno reprovado por falta, não haverá a necessidade de se avaliar as notas;

  4.3. Se a média entre **nota1** e **nota2** for menor que 3.0, o aluno estará reprovado por média.  Neste caso a função retorna a seguinte mensagem **Reprovado por Média**;

  4.4. Se a média entre **nota1** e **nota2** for >= 3.0 e < 6.0, o aluno estará em recuperação.  Neste caso a função retorna a seguinte mensagem **Recuperação**;

  4.5 Em qualquer outra situação o aluno estará  aprovado. Então a função retornará a mensagem: "Aprovado".
5. O Conjunto de classes de Equivalência deverá ser definido seguindo o seguinte padrão:

|id|descrição|V/I|
|--|--|--|
|CE01|nota1 < 0|I|

Onde:
**CE** = Classe de Equivalência, seguido de um número sequencial;
**Descrição** = define um cenário de teste;
**V/I** = Válida ou Inválida.

5. O Conjunto de casos de testes derivado das classes de Equivalência deve seguir o seguinte padrão:

|CT|Valor de Entrada|Resultado Esperado|Classe Equivalência|
|--|--|--|--|
|CT01|-2|Valor Inválido|CE1|

Onde:
**CT** = Caso de Teste, seguido de um valor sequencial;
**Valor de entrada** é o valor informado para a variável;
**Resultado esperado** é o resultado que se espera da execução da função;
**Classe de Equivalência** é a identificação de qual classe de equivalência está sendo exercitada pelo caso de teste.
