# TRABALHO 01 : Título do trabalho
Trabalho desenvolvido durante a disciplina de BD

    O referido projeto poderá ser:
        a) Um novo sistema/projeto 
        b) Uma expansão de sistema/projeto previamente desenvolvido em disciplinas anteriores 
        (ex: Expansão dos módulos do sistema desenvolvidos em BD1 - incremento mínimo de 50% nos 
        requisitos/complexidade)
    
    OBS Importantes: 
        a) Os projetos/sistemas propostos serão validados pelo professor e pela turma
        b) Se possível é interessante que os novos sistemas estejam correlacionados com alguma área 
        previamente estudada pelo aluno
        c) Caso dependa de alguma instituição/parceiro externo, a base de dados e informações pertinentes 
        a esta devem ser obtidas no prazo de até 15 dias apos aprovação da proposta do trabalho 
        (caso contrário, nova proposta deverá ser apresentada a turma implicando logicamente em um prazo 
        mais curto para realização das atividades e conclusão do trabalho)
        
# Sumário

### 1	COMPONENTES<br>
Thalles Vargas Ribeiro Lopes: tvrl07031997@gmail.com<br>
Yago Henrique Zanon Trarbach: yagozt.henrique@gmail.com

### 2	INTRODUÇÃO E MOTIVAÇAO<br>
Este documento contém a especificação do projeto do banco de dados <nome do projeto> e motivação da escolha realizada. <br>
    
O Aplicativo appMuseu que visa auxiliar o ramo de museus tanto para as empresas quanto para os clientes visitantes, disponibilizando as informações dos museus e as obras que nele estão localizadas, mostrar as informações das obras, o que e como os clientes avaliaram um determinado museu e suas obras, incentivando as visitas e a mobilidade.
      
### 3	MINI-MUNDO<br>
O appEventos é um aplicativo voltado para mobilidade e disponibilidade de informações para pessoas e empresas interessadas nas visitas a exposições, as peças que possuem e todas as suas informações. A utilização da aplicação é totalmente feita via aplicativo de celular. 

Na visão do cliente, ao abrir a aplicação pela primeira vez, o usuário terá a opção de fazer cadastro no sistema (podendo cadastrar diretamente sua conta do facebook) ou fazer login diretamente. Caso não seja cadastrado, irá para a página de cadastro onde fornecerá os seus dados, que são seu nome completo, e-mail e data de nascimento. O cliente já cadastrado, ao fazer o login, terá acesso ao seu perfil onde poderá escolher uma foto de perfil, escrever uma bio, verificar as notificações das empresas que ele "segue", procurar os museus mais próximos vendo a rota para chegar e ver a lista com todos as empresas cadastradas no sistema. Cada empresa terá uma avaliação de 0 a 5, descrição do mesmo, fotos da empresa e comentários que também podem ser avaliados, se ele foi útil ou não, sendo assim o usuario poderá ordernar pelos comentários mais bem avaliados ou mais recentes. 

Caso já esteja em uma exposição poderá fazer uma avaliação das peças disponíveis e fazer uma busca de obras para verificar suas informações via uma lista disponível onde mostrará o código e nome de cada obra ou através da utilização de QR Code expondo os dados da obra informada.

Para as empresas  deverão realizar o cadastro no site informando seu CNPJ, nome, localização, se é gratuito a visita ou não, valor para a visita, dias de funcionamento e criar a senha da conta. Após o cadastro da empresa terá a opção de criar eventos, fixos ou temporários onde será feito o cadastro das peças que notificam os seguidores após a criação. Poderá visualizar os comentários e avaliações feitas pelos clientes sobre a empresa, qual obra teve mais visualização e os comentários feito sobre a obra, escrever e editar as informações sobre a empresa e editar as informações de cadastro.

### 4	RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>

![https://github.com/tvrl/Topicos-Trabalho-BD2/blob/master/Prototipo/Museu.pdf](https://github.com/tvrl/Topicos-Trabalho-BD2/blob/master/Prototipo/Museu.pdf)


### 5	MODELO CONCEITUAL<br>
#### 5.1 NOTACAO ENTIDADE RELACIONAMENTO
![Alt text](https://github.com/discipbd2/topicos-trabalho/blob/master/sample_MC.png?raw=true "Modelo Conceitual")
    
     5.2 NOTACAO UML (Caso esteja fazendo a disciplina de Projeto)

#### 5.3 DECISÕES DE PROJETO
    [atributo]: [descrição da decisão]
    
    EXEMPLO:
    a) Campo endereço: em nosso projeto optamos por um campo multivalorado e composto, pois a empresa 
    pode possuir para cada departamento mais de uma localização... 
    b) justifique!

#### 5.4 DESCRIÇÃO DOS DADOS 
    [objeto]: [descrição do objeto]
    
    EXEMPLO:
    CLIENTE: Tabela que armazena as informações relativas ao cliente<br>
    CPF: campo que armazena o número de Cadastro de Pessoa Física para cada cliente da empresa.<br>

### 6	MODELO LÓGICO<br>
### 7	MODELO FÍSICO<br>
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
        Detalhamento sobre as informações e processo de obtenção ou geração dos dados.
        Referenciar todas as fontes referentes a:
        a) obtenção dos dados
        b) obtenção de códigos reutilizados
        c) fontes de estudo para desenvolvimento do projeto
        
#### 8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELAS E INSERÇÃO DOS DADOS (ARQUIVO ÚNICO COM):
        a) inclusão das instruções para criação das tabelas e estruturas de amazenamento do BD
        b) inclusão das instruções de inserção dos dados nas referidas tabelas
        c) inclusão das instruções para execução de outros procedimentos necessários

### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
#### 9.1	GERACAO DE DADOS (MÍNIMO DE 1,5 MILHÃO DE REGISTROS PARA PRINCIPAL RELAÇAO)<br>
    Data de Entrega: (Data a ser definida)
<br>
OBS: Incluir para os tópicos 9.2 e 9.3 as instruções SQL + imagens (print da tela) mostrando os resultados.<br>

#### 9.2	SELECT DAS TABELAS COM PRIMEIROS 10 REGISTROS INSERIDOS <br> 
    Data de Entrega: (Data a ser definida)
<br>

#### 9.3	SELECT DAS VISÕES COM PRIMEIROS 10 REGISTROS DA VIEW <br>
        a) Descrição da view sobre que grupos de usuários (operacional/estratégico) <br>
        e necessidade ela contempla.
        b) Descrição das permissões de acesso e usuários correlacionados (após definição <br>
        destas características)
    Data de Entrega: (Data a ser definida)
<br>

#### 9.4	LISTA DE CODIGOS DAS FUNÇÕES, ASSERÇOES E TRIGGERS<br>
        Detalhamento sobre funcionalidade de cada código.
        a) Objetivo
        b) Código do objeto (função/trigger/asserção)
        c) exemplo de dados para aplicação
        d) resultados em forma de tabela/imagem
<br>

#### 9.5	Administração do banco de dados<br>
        Descrição detalhada sobre como serão executadas no banco de dados as <br>
        seguintes atividades.
        a) Segurança e autorização de acesso:
        b) Estimativas de aquisição de recursos para armazenamento e processamento da informação
        c) Planejamento de rotinas de manutenção e monitoramento do banco
        d) Plano com frequencia de análises visando otimização de performance
<br>

#### 9.6	Backup do Banco de Dados<br>
        Detalhamento do backup.
        a) Tempo
        b) Tamanho
        c) Teste de restauração (backup)
        d) Tempo para restauração
        e) Teste de restauração (script sql)
        f) Tempo para restauração (script sql)
<br>

Data de Entrega: (Data a ser definida)
<br>

#### 9.7	APLICAÇAO DE ÍNDICES E TESTES DE PERFORMANCE<br>
    a) Lista de índices, tipos de índices com explicação de porque foram implementados
    b) Performance esperada VS Resultados obtidos
    c) Tabela de resultados comparando velocidades antes e depois da aplicação dos índices.
<br>
    Data de Entrega: (Data a ser definida)
<br>   

#### 9.8	ANÁLISE DOS DADOS COM ORANGE<br>    
    a) aplicação de algoritmos e interpretação dos resultados
<br>
    Data de Entrega: (Data a ser definida)
<br>

### 10	ATUALIZAÇÃO DA DOCUMENTAÇÃO/ SLIDES E ENTREGA FINAL<br>
<br>
    Data de Entrega: (Data a ser definida)
<br>

### 11	DIFICULDADES ENCONTRADAS PELO GRUPO<br>  

### 12  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/
