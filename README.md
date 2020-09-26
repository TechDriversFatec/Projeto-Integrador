# Projeto Integrador - Grupo 06

Projeto Integrador - BD

## Integrantes do grupo:

- Danilo Verginio da Silva
- Eliza Silva Galvão
- Guilherme de Agostin
- Gustavo de Castro Costa Silva
- Marcos Francisco da Silva
- Michel Rubens Ferreira da Silva


**Sprint 0: Definição das regras de negócio e estrutura da aplicação**

**Sprint 1: Tela de login** - Criação do layout no App Inventor e autenticação com Firebase e Google Sheet

**Sprint 2: Tela do passageiro** - Criação do layout no App Inventor e inserção e leitura dos dados do passageiro via Google Sheet

**Sprint 3: Tela do motorista** - Criação do layout no App Inventor e inserção e leitura dos dados do passageiro via Google Sheet

**Sprint 4: Projeto finalizado, com integração dos dados do passageiro e do motorista** - Integração das telas, com o Google Sheet


## Entrega Sprint 0

[![Video Apresentação Sprint 0](https://img.youtube.com/vi/35BdMUFu61Y/0.jpg)](https://www.youtube.com/watch?v=35BdMUFu61Y)

1. Regras de negócio
2. Layouts das telas
3. Tecnologias utilizadas

## 1.	Regras de Negócio Vandroid

Atualmente a expressão “economia de tempo”, está cada vez mais presente no nosso cotidiano, hoje as interações que temos pelas redes de computadores e aparelhos celulares nos permite a conexão e o contato com todos instantaneamente de uma maneira muito simples e rápida. Pensando nisso e nas problemáticas enfrentadas todos os dias por motoristas de vans escolares que fazem transporte de passageiros, focamos nossas atenções para o desenvolvimento de um aplicativo prático, proporcionando um suporte para o motorista otimizar seu tempo e rota. 

### Objetivo

O Vandroid tem como objetivo promover a interação entre o motorista e o passageiro, contando com a facilidade de acesso aos aparelhos celulares, auxiliando o motorista na administração dos seus horários e rotas. Será utilizado o MIT – App Inventor 2 como tecnologia principal no desenvolvimento do aplicativo.

###  Funcionalidade do aplicativo

O Vandroid contará com uma tela simples, sendo necessário fazer login como motorista ou como passageiro, opção que será selecionada na primeira tela da aplicação. 

O app enviará uma notificação para que os usuários cadastrados possam dar o check-in em sua viagem diariamente, o usuário receberá uma notificação o alertando para entrar no aplicativo, efetuar o Login e confirmar se irá ou não com a van escolar no dia, sendo necessário a confirmação de ida e de volta. 

Para início da viagem e para cálculo da rota, o motorista terá que ter a confirmação de todos os passageiros que irão, e a não confirmação por parte do usuário, indicará ao motorista que ele deve tomar outra rota evitando o desperdício de tempo na busca do mesmo. 

### Funcionalidades da tela do passageiro

No caso de novos usuários do transporte, é obrigatório o preenchimento de dados de cadastro como: Nome completo, sexo, idade, CPF, e-mail, telefone, endereço (nome da rua, bairro, número da casa, CEP) e senha. Para passageiros já cadastrados a próxima tela será a de confirmação da viagem, onde o passageiro confirmará sua ida e a sua volta utilizando a van escolar. 

### Funcionalidade da tela do motorista

Mediante as informações e do preenchimento dos dados cadastrais por parte do passageiro, e da confirmação de quais pessoas farão a viagem, o motorista contará com uma relação de alunos que irão na ida e na volta e seus respectivos endereços. Contando com as funcionalidades do aplicativo, será possível traçar a melhor rota maximizando o tempo e tornando o trabalho do motorista mais eficiente.

### Traçando a Melhor Rota

A tela do motorista irá consumir todos os dados preenchidos pelos passageiros, a partir dos dados a aplicação irá mostrar a melhor ordem para o embarque e desembarque dos passageiros, mas também o motorista terá autonomia total sobre o app para ele poder definir a melhor ordem de acordo com sua necessidade e conhecimento.

## 2.	Layouts das telas

**Tela 1. Tela inicial**

Onde será selecionado quem é o usuário e onde um passageiro novo poderá ser redirecionado para se cadastrar.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/200/original/Home_N%C3%A3o_Logado.png?1601145581" alt="Tela 1">
</figure>

Regras para implementar nos campos: 

- Clicou no botão de usuário PASSAGEIRO vai para tela 2

- Clicou no botão de usuário MOTORISTA vai para tela 4


**Tela 2. Check-in de passageiro**

Onde o passageiro irá confirmar sua ida e sua volta.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/190/original/Passageiro_logado_%282%29.png?1601145068" alt="Tela 2">
</figure>

**Tela 3. Cadastro de novo usuário**

Onde o passageiro irá digitar seus dados pessoais.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/198/original/Cad_Passageiro_-_Copia.png?1601145478" alt="Tela 3">
</figure>

Regras para implementar nos campos: 

- O usuário não pode salvar as informações enquanto não preencher todos os campos. 

- A senha tem que ser a mesma nas duas caixas de senha para garantir que foi digitada corretamente.

**Tela 4.  Motorista**

Onde abrirá a relação de passageiros que irão no dia e seus respectivos endereços.

<figure>
  <img src="https://uploaddeimagens.com.br/images/002/896/182/original/Lista_Motorista_%281%29.png?1601144892" alt="Tela 4">
</figure>

## 3.	Tecnologias utilizadas

- GitLab
- Figma






