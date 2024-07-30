# PROJETO INTEGRADOR:  MIAUjuda

## Sumário

### 1. INTEGRANTES DO GRUPO: <br>
Eduardo de Oliveira: duduoliveirae11@gmail.com <br>
Luísa Coutinho: luisacpsantos@gmail.com <br>
Raphael Brandão: raphael.brandaopay@gmail.com <br>
Stéphany Lahass: lahassstephany@gmail.com

### 2.MINIMUNDO <br>

O sistema “Miaujuda” é uma aplicação cuja finalidade é facilitar a conexão entre pessoas que desejam adotar animais, colocar cães e gatos para adoção e que queiram auxiliar cachorros e gatos em situação de vulnerabilidade.
Para realizar o cadastro na plataforma, o USUÁRIO fornece email, nome de usuário e senha. Cada usuário está relacionado a somente um ENDEREÇO, embora este possa se relacionar com nenhum ou vários usuários. Além disso, o usuário é capaz de adicionar formas de CONTATO identificadas pelo seu tipo e descrição, sendo cada contato vinculado a apenas um usuário, é necessário haver ao menos uma forma de contato. 
O sistema permite que o usuário faça o anúncio de ANIMAL PARA ADOÇÃO e ANIMAL PERDIDO por meio do fornecimento de dados como nome, descrição e sexo. Cada animal possui uma ESPÉCIE que contém uma descrição (permitindo a identificação do pet como gato ou cachorro). Especificamente para os animais cadastrados para a adoção, se registram o peso, tamanho e raça. No registro de animal perdido é necessário fornecer a última data que o animal foi visto. Esse animal também está relacionado a um e somente um endereço (o último lugar em que foi visto). Um usuário pode fazer o anúncio de múltiplos animais, mas cada animal só pertence a um usuário. 
Em todos os cadastros também é possível fornecer IMAGEM, em que registra-se sua referência. Um usuário está relacionado a apenas uma imagem e a imagem se vincula a nenhum ou um usuário. Já no cadastro de animais podem ser inseridas uma ou várias imagens, essas que estão vinculadas a nenhum ou um animal.

 
 
### Histórias de Usuário

* Como usuário ou visitante, eu quero visualizar animais para adoção e animais perdidos.<br>
* Como usuário ou visitante, eu quero visualizar artigos do blog.<br>
* Como usuário ou visitante, eu visualizar contato com ONGs de animais.<br>
* Como usuário, eu quero cadastrar animais perdidos.<br>
* Como usuário, eu quero cadastrar animais para adoção.<br>
* Como usuário, eu quero gerenciar as informações do perfil de usuário.<br>
* Como usuário, eu quero filtrar minha busca por animais.<br>
* Como usuário,eu quero poder entrar em contato com doadores.<br>
* Como administrador, eu quero gerenciar as informações do blog.<br>
* Como administrador, eu quero fornecer um DashBoard.<br>


#### Casos de Uso
a) Link do arquivo em si <br>
[https://forms.gle/UPcCaedRZAM18tfVA](https://lucid.app/lucidchart/afd5c852-807a-43d4-80e5-2faa42813fe7/edit?viewport_loc=-5228%2C-6267%2C18676%2C20056%2C0_0&invitationId=inv_e817aecf-8088-4f74-bb4f-2f18ff5d844f) <br>
b) Link para o pdf para faciliar a visualização:<br>
https://lucid.app/lucidchart/afd5c852-807a-43d4-80e5-2faa42813fe7/edit?viewport_loc=-5228%2C-6267%2C18676%2C20056%2C0_0&invitationId=inv_e817aecf-8088-4f74-bb4f-2f18ff5d844f

### Diagramas de Atividades

[MIAUJUDA.-.Fluxo.de.processos.BPMN.pdf](https://github.com/user-attachments/files/16433870/MIAUJUDA.-.Fluxo.de.processos.BPMN.pdf)




### 5. PROTÓTIPOS DO SISTEMA<br>

Protótipo mobile desenvolvido com a ferramenta quant-ux
https://app.quant-ux.com/#/test.html?h=a2aa10aTPWSSRCa0Mq4fnVtEvEUgylhMKaJSBnmmYIflxnotNZbEHd3wqUYi&ln=en


#### 5.3 QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM OS SISTEMA WEB/MOBILE PROPOSTOS?
    a) O sistema proposto poderá fornecer quais tipos de relatórios e informaçes? 
    b) Crie uma lista com os 5 principais relatórios que poderão ser obtidos por meio do sistema proposto!
    
> A Empresa DevCom precisa inicialmente dos seguintes relatórios:
* Relatório que informe quais são os gerentes de cada departamento incluindo as seguintes informações: número do departamento,  nome do departamento, e nome do gerente.
* Relatório de empregados por projeto incluindo as seguintes informações: número do projeto, nome do projeto, rg do empregado, nome do empregado e quantidade de horas de trabalho do empregado alocadas ao projeto.
* Relatório de empregados com dependentes incluindo as seguintes informações: rg do empregado, nome do empregado, nome do dependente, tipo de relação, data de nascimento do dependente e sexo do dependente.
* Relatório com a quantidade de empregados por cada departamento incluindo as seguintes informações: nome do departamento, supervisor e quantidade de empregados alocados no departamento.
* Relatório de supervisores e supervisionados incluindo as seguintes informações: nome do supervisor e nome do supervisionado.
 
 ### 6.MODELO CONCEITUAL<br>

![Modelo Conceitual Miaujuda](https://github.com/ProjetoIntegradorPets/MIAUjuda/blob/main/docs/img/conceitual_miaujuda.png?raw=true "Modelo Conceitual")
      
    
#### 7 Descrição dos dados 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

### 8	RASTREABILIDADE DOS ARTEFATOS<br>
        a) Historia de usuários vs protótipo (Histórias de Usuário e em qual tela do protótipo aquela HU está sendo realizada).
        b) Protótipo vs Modelo conceitual (Histórias de Usuário e em quais tabelas aquele dado está sendo registrado).
        (modelos devem obrigatoriamente estar em conformidade de rastreabilidade)

### 9	MODELO LÓGICO<br>
![Modelo Lógico Miaujuda](https://github.com/ProjetoIntegradorPets/MIAUjuda/blob/main/docs/img/logico_miaujuda.jpeg?raw=true "Modelo Lógico")

### 10	MODELO FÍSICO<br>

       
### 11	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
        a) inclusão das instruções de inserção dos dados nas tabelas criadas pelo script de modelo físico
        (Drop para exclusão de tabelas + create definição de para tabelas e estruturas de dados + insert para dados a serem inseridos)
        b) Criar um novo banco de dados para testar a restauracao 
        (em caso de falha na restauração o grupo não pontuará neste quesito)
        c) formato .SQL

#### 12 PRINCIPAIS CONSULTAS DO SISTEMA 
 Inserir as principais consultas (relativas aos 5 principais relatórios) definidas previamente no iten 3.1 deste template.
 <br>
  a) Você deve apresentar as consultas em formato SQL para cad um dos relatórios.
 <br>
  b) Além da consulta deve ser apresentada uma imagem com o resultado obtido para cada consulta.<br>

 ### 13 Gráficos, relatórios, integração com Linguagem de programação e outras solicitações.<br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 13.1	Integração com Linguagem de programação; <br>
 #### 13.2	Desenvolvimento de gráficos/relatórios pertinentes, juntamente com demais <br>
 #### solicitações feitas pelo professor. <br>
 
 ### 14 Slides e Apresentação em vídeo. <br>
     OBS: Observe as instruções relacionadas a cada uma das atividades abaixo.<br>
 #### 14.1 Slides; <br>
 #### 14.2 Apresentação em vídeo <br>

    
##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
    
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

#### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
1. Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.


Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html
<br>


Link para curso de GIT<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")
