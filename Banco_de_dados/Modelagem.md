####                                                    ***Modelagem de Dados***

**Mini Mundo:** Organizar relações entre objetos (entidades);

**Modelagem de dados:** Maiores especificações estruturadas;

*Aplicativo para criação do Mini Mundo e Modelagem de Dados: **Br Modelo***

*(A representação gráfica é muito importante para associar os dados)*



***Tipos de Modelo:***

*-Conceitual;*

*-Lógico;*

*-Físico.*



**Conceitos fundamentais ao realizar uma modelagem**

Entidade: Objeto ou ente do mundo real que possui identidade própria;

Conjunto de entidades: Grupo de entidades com valores diferentes;

Atributos: Propriedades específicas;

Atributo Chave/Determinante: Propriedade única por entidade.



**Tipos de Atributos**

​			**Descritivo**							 **Nominativo**								**Referenciais**

*Características Potenciais* 		       *Identificam o objeto* 				         *Interliga*



**Tipos de Entidades**

​     **Forte**    								   	    **Fraca** 										         **Associativa**

*Independente*                                   *Dependente*                                                *Associa*



**Modelo Conceitual:** *Modelo Entidade de Relacionamento.*

**Relacionamento um-para-muitos**

![rel](https://github.com/Pedrogvd/Projeto_StartLatam/blob/main/Imagens_BD/rel1.PNG)

**Relacionamento um-para-um**

![image-20201010175330038](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010175330038.png)

**Relacionamento muitos-para-muitos**

![image-20201010175354600](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010175354600.png)

**Relacionamento total** (Quando uma entidade não pode deixar de se relacionar com a outra obrigatoriamente)

![image-20201010175429494](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010175429494.png)

**Relacionamento com Atributos**

![image-20201010175530078](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010175530078.png)

**Auto-Relacionamento**

![image-20201010175605094](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010175605094.png)

**Relacionamento Triplo**

![image-20201010175626697](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010175626697.png)

**Cardinalidade**

![image-20201010175658822](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010175658822.png)

**Especialização** (caracteriza propriedades específicas para cada “perfil”)

​                  ![image-20201010181858115](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010181858115.png)

**Entidade Associativa** (Resulta da associação entre entidades)

![image-20201010182531908](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010182531908.png)





####                                                      **Modelo Lógico**

**Modelo Lógico:** *Descrição de estruturas que gera uma representação*  *gráfica dos dados de uma maneira lógica.*

**Características:** *Derivado do Conceitual;*    

*Entidade associativa (entidades viram tabelas);*            

*Designa Chave Primária e estrangeira(s);*       

*Atributos viram campos da tabela.*

![image-20201010183207832](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010183207832.png)



####                                                        **Modelo Físico**

**Modelo Físico:** *Abstração de um banco de dados visto pelo usuário* SGBD.

**Característica:** *Detalhado os componentes da estrutura do banco.*

![image-20201010183323254](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010183323254.png)

Trazendo um exemplo prático de inserção em um banco de dados:
        CREATE DATABASE ESCOLA;

CREATE TABLE aluno( 

matricula INTEGER NOT NULL, 

nome VARCHAR(40), 

sexo VARCHAR(1) );

**Obs: SGBD e comandos SQL serão vistos durante o** **processo.** 

#### **Ferramentas**

**DBDesigner:** *Excelente opção para quem utiliza qualquer banco de dados principalmente MySQL, Oracle, MSSQL e PostgreSQL. Pode estabelecer modelagem e relação.*

**MySQL:** *MySQL Workbench, modelagem ou criação e manipulação direta do SQL.*

![image-20201010183526137](C:\Users\Administrador\AppData\Roaming\Typora\typora-user-images\image-20201010183526137.png)

**Truque de Mestre:** *Modele bem todas as tabelas, campos, chaves (estrangeiras e primárias), a cardinalidade, e etc, pois caso faça de forma errada, seu SQL não será gerado como o esperado. (By: Professor Guibson Santana)*

**SGBD:** *Sistemas de Gestão de Base de Dados* (DBMS), trata-se de um sistema para gerenciar uma base de dados ou banco de dados.

**Diferença dos SGBDs**: *Conjunto de requisitos e funcionalidades oferecidos: Segurança, integridade, controle de concorrência e recuperação/tolerância a falhas.*

##### **Ferramentas**

**MySQL:** *Banco de dados dos mais utilizados e populares;*    Open source (Código aberto, adaptável).

**Xampp:** *Um dos pacotes com os principais servidores de código aberto;*       *Contém MySQL, PHP e Perl.*

**Acessando Xampp**

Inicie os serviços que desejar para utilizar o servidor local;*Para entrarmos no SGBD do Xampp e administrar os BDs, insira em seu navegador:* **http://localhost/phpmyadmin**.



#### **Criando um Banco de Dados no Xampp**

**SQL:** *Podemos criar pelo modo gráfico (através do botão NEW → no campo banco de dados, devemos colocar no nome do banco e depois clicar em criar) ou por linha de comando (MENU SQL → comando create database nome_do_banco; → executar)*

**Cláusulas em SQL**

**SHOW DATABASES;** *(Visualizar os bancos criados)*

**DROP DATABASE** NomeDoBanco**;** *(Deletar um banco criado)*

**DROP TABLE** *NomeDoBanco.NomeTabela; (Deletar uma tabela)*

**ALTER TABLE** *NomeDoBanco.NomeTabela* 

**RENAME TO** *NomeDoBanco.NomeTabelaRenomeado;(Alterar nome da tabela)*

**ALTER TABLE** *NomeDoBanco.NomeTabela* 

**ADD** *característica3 tipo;(Adicionar um campo)*

**ALTER TABLE** *NomeDoBanco.NomeTabela* 

**DROP COLUMN** *característica3; (Deletar campo)*

**SHOW TABLES;** (Visualizar todas as tabelas)

**Obs:** *No contexto de cláusulas SQL e referências SGBD, campo e colunas são sinônimos.*



#### **Tabelas**

**CREATE TABLE** NomeDoBanco.NomeTabela**(**    

   caracteristica1 tipo **PRIMARY KEY,**     

 caracteristica2 tipo **NOT NULL,**  

​    caracteristica3 tipo **NOT NULL**);

 (Criar tabela)

**Obs:** As informações que **não** estão em negrito vão depender dos dados que o programador irá inserir.

**Outro exemplo**

**CREATE TABLE** NomeDoBanco.NomeTabela **(** 

característica1(Tabela1) tipo,

característica2(Tabela2) tipo, 

**FOREIGN KEY**(característica1) **REFERENCES** Tabela1 (característica1),

 **FOREIGN KEY**(característica2) **REFERENCES** Tabela2 (característica2));

(Criar tabela que relaciona outras)

**Obs:** Os dados “**(Tabela1)**” e “**(Tabela2)**” são para referenciar os itens “característica”, mostrando que cada um veio de uma tabela diferente.

Autor: Eduardo Riego
