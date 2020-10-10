####                                                               **Comentários**

São pequenos textos que podem ser inseridos no algoritmo, sem modificá-lo ou causar
qualquer alteração. Eles vão explicar como aquele código funciona e também ajudar o
programador a entender o algoritmo.
**Como criar os comentários?**
// Se usa para comentários de apenas uma linha.
/* Se usa para comentários que contém mais de uma linha. /*

​![image-20201009204451953](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009204451953.png)   

Se você quiser escrever apenas uma linha, por exemplo a linha de número 1, poderia colocar //
no início, e depois inserir seu comentário. Veja abaixo um exemplo:

![image-20201009204646496](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009204646496.png)

#### **Palavras Reservadas (Palavras Chaves)**

São identificadores predefinidos que tem um significado especial para o interpretador do
algoritmo. Também são palavras utilizadas pela própria linguagem ou por bibliotecas de rotina,
por sua vez não podem ser utilizadas pelo programador exceto para a função pela qual foi
desenvolvida.
**Programa			Escreva			Real			Cadeia			Enquanto			Const**
**Funcao	            Leia          	Inteiro	     Lógico	       	 Para				  Inclua**



#### **Operadores**

Elementos que utilizamos em expressões matemáticas, lógicas e relacionais. Geralmente a
maioria deles tem a mesma representação nas linguagens de programação.
São eles:
· Aritméticos
· Relacionais
· Lógicos
Operadores Aritméticos
Símbolos que usamos em operações básicas na matemática.

![image-20201009210440760](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009210440760.png)

Exemplo:

![image-20201009210504545](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009210504545.png)





#### **Operadores Relacionais**

Servem para compara valores. E como resultado, adquirimos um valor lógico Verdadeiro ou
Falso.

![image-20201009210802251](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009210802251.png)

#### **Operadores Lógicos**

Utilizados para comparar valores, eles nos retornam um valor. Eles fazem uma avaliação que
resulta em valores verdadeiros ou falsos.

![image-20201009210834340](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009210834340.png)

#### **Tabela da Verdade**

Dispositivo utilizado no estudo da lógica matemática. Com esta tabela é possível definir um
valor lógico de uma sobreposição, ou seja, saber quando uma sentença é verdadeira ou falsa.
Abaixo veremos duas variáveis P e Q do tipo lógico, que assumem valores de verdadeiro e
falso, em diferentes situações lógicas (E, OU e Negação).

![image-20201009210939646](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009210939646.png)

**Exemplo**
Conforme o que foi aprendido, tente resolver usando seus conhecimentos.

![image-20201009211010620](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009211010620.png)





#### **Introdução a Estruturas de Seleção**

Os comandos de seleção permitem determinar qual ação será tomada com base no resultado
de uma expressão condicional.
Existem três tipos de seleção em um programa:
· Seleção Simples
· Seleção Composta
· Seleção de Múltipla Escolha

#### **Estrutura de Seleção Simples**

Serve para uma comparação simples.
se(condição){
funções/instruções <== Se condição VERDADEIRA
}
Exemplo
Um algoritmo que recebeu 3 possíveis números do ângulo de um triângulo e precisamos saber
que tipo de triângulo é.

![image-20201009211122213](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009211122213.png)





#### **Estrutura de Seleção Composta**

Serve para uma comparação de desvio. Caso tenha um resultado verdadeiro uma decisão é
tomada, se a condição tiver um resultado falso outra instrução é executada.
se(valor1>valor2){
escreva("O valor 1 é o maior") } <== Se condição VERDADEIRA

senao{
escreva("O valor 2 é o maior") } <== Se condição FALSA



**Exemplo**

![image-20201009211240563](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201009211240563.png)

A seleção composta também pode apresentar mais de um teste sequencial.