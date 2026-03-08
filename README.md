1. Análise inicial da aplicação
Objetivo da aplicação

A aplicação tem como objetivo permitir o cadastro e a visualização de cursos.
Ela possui um módulo simples onde o usuário pode registrar informações de um curso e posteriormente visualizar os cursos cadastrados em uma lista.

Esse tipo de aplicação simula um sistema básico de gerenciamento de cursos, permitindo validar funcionalidades comuns como:

cadastro de registros

persistência de dados

listagem de informações cadastradas

Principais fluxos da aplicação

Durante a exploração da aplicação foram identificados dois fluxos principais:

1️⃣ Cadastro de cursos

Fluxo responsável por registrar novos cursos no sistema.

Passos do fluxo:

Acessar a página Cadastrar curso

Preencher os campos do formulário

Clicar no botão Cadastrar

O sistema registra o curso

Esse fluxo é responsável por criar novos registros no sistema.

2️⃣ Listagem de cursos

Fluxo responsável por exibir os cursos cadastrados.

Passos do fluxo:

Acessar a página Listar cursos

O sistema exibe todos os cursos cadastrados anteriormente.

Esse fluxo permite consultar as informações cadastradas.

Pontos críticos para testes

Durante a análise da aplicação, alguns pontos foram considerados mais críticos para validação.

1️⃣ Validação dos campos do cadastro

É importante verificar se o sistema:

impede envio de campos vazios

valida corretamente os dados inseridos

exibe mensagens de erro adequadas

Esse ponto é crítico pois dados inválidos podem comprometer a integridade das informações cadastradas.

2️⃣ Persistência dos dados

Após cadastrar um curso, ele deve:

aparecer corretamente na lista de cursos

manter os dados corretos

Esse teste garante que os dados estão sendo armazenados corretamente.

3️⃣ Comportamento do sistema em cenários inesperados

Foram considerados cenários como:

envio de formulário incompleto

dados inválidos

múltiplos cadastros

Esse tipo de teste ajuda a identificar possíveis falhas no comportamento da aplicação.

Estratégia de criação dos testes

Para a criação dos testes foram considerados os seguintes tipos de cenário:

Cenários positivos

Validam se o sistema funciona corretamente em condições normais.

Exemplo:

cadastro de curso com dados válidos

Cenários negativos

Validam o comportamento do sistema diante de erros do usuário.

Exemplo:

envio de formulário com campos vazios

inserção de dados inválidos

Validação de campos

Testes voltados para verificar:

campos obrigatórios

limites de caracteres

formato dos dados

Comportamentos inesperados

Testes voltados para verificar possíveis falhas, como:

duplicidade de cadastro

falhas de validação

inconsistências na listagem de dados

Cenários e casos de teste

Os cenários e casos de teste foram documentados em uma planilha no Google Sheets.

Link da planilha:

(INSERIR LINK AQUI)

Evidências da execução dos testes

Durante a execução dos testes foram capturadas evidências contendo:

prints de tela

registros da execução dos testes

Link das evidências:

(INSERIR LINK DO DRIVE)

Bugs identificados

Durante a execução dos testes foram identificados alguns comportamentos que podem ser considerados falhas.

Os bugs encontrados foram documentados contendo:

título do bug

passos para reprodução

resultado atual

resultado esperado

severidade

Repositório do desafio

Link do repositório:

https://github.com/Pablo9293/DESAFIO-QA-BEEDOO-2026# DESAFIO-QA-BEEDOO-2026
