# Cappyo - Roteiro pedagógico das videoaulas de SQL

**Projeto:** Cappyo - Certificadora de Competência Comum  
**Responsáveis pelos roteiros:** João Vitor de Oliveira Pinho e Pedro Lucas Sales Larini  
**Apoio:** Luiz Felipe Fernandes Ramos  
**Finalidade:** planejamento do conteúdo das videoaulas para apreciação do professor e orientação da produção.

## 1. Apresentação

Este roteiro organiza os conteúdos das videoaulas introdutórias de SQL da Cappyo, um Recurso Educacional Aberto voltado a pessoas sem experiência prévia com bancos de dados. As aulas devem apresentar os conceitos de forma simples e progressiva, preparando o estudante para a trilha de exercícios de cada módulo.

O documento define objetivos de aprendizagem, sequência de assuntos, comandos previstos e exemplos práticos. A apresentação oral será desenvolvida a partir dessas orientações, permitindo que o apresentador explique os conceitos com suas próprias palavras.

## 2. Diretrizes de produção

- **Público-alvo:** iniciantes em banco de dados e SQL.
- **Duração:** de 5 a 7 minutos por videoaula.
- **Ambiente:** PostgreSQL, conforme o planejamento do projeto.
- **Abordagem:** explicação breve dos conceitos, demonstração prática e interpretação dos resultados.
- **Contexto dos exemplos:** uma loja fictícia, com produtos, fornecedores, clientes e pedidos.
- **Acessibilidade:** legendas revisadas, texto legível e explicação oral dos elementos relevantes dos exemplos.
- **Edição:** CapCut.
- **Encerramento:** retomada dos principais conceitos e encaminhamento para os exercícios do módulo.

A organização proposta contempla uma aula introdutória por módulo. Caso o ensaio indique que um conteúdo não pode ser explicado com clareza no tempo previsto, o módulo poderá ser dividido em duas pílulas, preservando a sequência de aprendizagem.

## 3. Organização das aulas

| Aula | Módulo | Foco principal |
| --- | --- | --- |
| 1 | SQL básico | Consultar, filtrar e ordenar dados. |
| 2 | Manipulação de dados | Inserir, atualizar e excluir registros. |
| 3 | WHERE avançado | Construir filtros com diferentes critérios. |
| 4 | Gerenciamento de tabelas | Criar e modificar estruturas de tabelas. |
| 5 | JOIN | Consultar informações relacionadas de duas tabelas. |

## 4. Aula 1 - SQL básico

### Objetivo de aprendizagem

Compreender a organização básica dos dados em tabelas e realizar consultas simples, selecionando colunas, filtrando registros e ordenando resultados.

### Conteúdos e sequência de abordagem

1. Apresentar o conceito de banco de dados e a finalidade da linguagem SQL.
2. Explicar tabela, linha, coluna e identificador de um registro.
3. Demonstrar a consulta de todas as colunas de uma tabela.
4. Demonstrar a seleção de colunas específicas.
5. Introduzir um filtro simples com operadores de comparação.
6. Apresentar a ordenação crescente e decrescente dos resultados.

### Comandos e elementos previstos

`SELECT`, `FROM`, `*`, `WHERE`, `ORDER BY`, `ASC` e `DESC`. Operadores de comparação, como `=`, `<`, `>` e `<=`.

### Exemplo prático sugerido

Consultar o catálogo de produtos de uma loja. Inicialmente, apresentar todos os dados; depois, exibir apenas nome e preço. Em seguida, buscar os produtos que custam até determinado valor e ordenar o resultado pelo preço.

### Pontos de atenção

Diferenciar a escolha de colunas da filtragem de linhas. Explicar que a consulta com `SELECT` não modifica os registros e que a ordenação deve ser indicada quando a sequência dos resultados for relevante.

### Resultado esperado

Ao final da aula, o estudante deverá conseguir montar uma consulta simples e identificar quais dados serão apresentados no resultado.

## 5. Aula 2 - Manipulação de dados

### Objetivo de aprendizagem

Adicionar, alterar e remover registros de uma tabela existente, compreendendo o papel das condições que delimitam essas operações.

### Conteúdos e sequência de abordagem

1. Diferenciar a consulta de dados da modificação dos registros armazenados.
2. Apresentar a inserção de um registro e a correspondência entre colunas e valores.
3. Demonstrar a atualização de um campo de um registro existente.
4. Demonstrar a exclusão de um registro específico.
5. Explicar o uso de condições para delimitar os registros afetados.
6. Conferir os dados antes e depois de cada operação por meio de consultas.

### Comandos e elementos previstos

`INSERT INTO`, `VALUES`, `UPDATE`, `SET`, `DELETE FROM` e `WHERE`. Retomada de `SELECT` para conferir os resultados.

### Exemplo prático sugerido

Cadastrar um novo produto na loja, alterar seu preço e, ao final, remover esse cadastro de demonstração. Consultar o registro em cada etapa para observar o efeito da operação.

### Pontos de atenção

Explicar que `UPDATE` e `DELETE` sem `WHERE` podem atingir todos os registros da tabela. Diferenciar a exclusão de um registro da remoção da estrutura da tabela. Executar as demonstrações em uma base de treinamento.

### Resultado esperado

Ao final da aula, o estudante deverá reconhecer a finalidade de cada comando e conseguir realizar uma operação sobre um registro específico.

## 6. Aula 3 - WHERE avançado

### Objetivo de aprendizagem

Construir filtros mais específicos por meio da combinação de condições, de intervalos de valores, de padrões de texto e da identificação de informações ausentes.

### Conteúdos e sequência de abordagem

1. Retomar brevemente o filtro simples com `WHERE`.
2. Combinar condições com `AND` e `OR`.
3. Utilizar parênteses para agrupar condições e explicitar a intenção do filtro.
4. Selecionar valores de uma lista com `IN`.
5. Buscar valores em um intervalo com `BETWEEN`.
6. Buscar padrões de texto com `LIKE`, apresentando `%` e `_`.
7. Identificar informações ausentes ou preenchidas com `IS NULL` e `IS NOT NULL`.

### Comandos e elementos previstos

`WHERE`, `AND`, `OR`, `IN`, `BETWEEN`, `LIKE`, `IS NULL` e `IS NOT NULL`.

### Exemplo prático sugerido

Encontrar produtos de determinadas categorias dentro de uma faixa de preço. Complementar a demonstração com uma busca por início do nome e uma consulta de clientes sem email cadastrado.

### Pontos de atenção

Diferenciar `AND` de `OR` e mostrar a importância dos parênteses ao combinar os dois operadores. Explicar que `BETWEEN` inclui os limites do intervalo e que `NULL` representa informação ausente, sendo diferente de zero e de texto vazio.

### Resultado esperado

Ao final da aula, o estudante deverá conseguir transformar uma busca com diferentes critérios em uma condição SQL e interpretar os registros retornados.

## 7. Aula 4 - Gerenciamento de tabelas

### Objetivo de aprendizagem

Compreender a criação e a alteração da estrutura de uma tabela, diferenciando essas operações da manipulação dos registros.

### Conteúdos e sequência de abordagem

1. Diferenciar a estrutura da tabela dos dados armazenados nela.
2. Criar uma tabela, definindo seu nome e suas colunas.
3. Apresentar tipos básicos do PostgreSQL: `INTEGER`, `TEXT` e `NUMERIC`.
4. Explicar a função da chave primária com `PRIMARY KEY`.
5. Apresentar a restrição `NOT NULL`.
6. Acrescentar uma coluna a uma tabela existente.
7. Apresentar a remoção de uma tabela e compará-la à exclusão de registros.

### Comandos e elementos previstos

`CREATE TABLE`, `PRIMARY KEY`, `NOT NULL`, `ALTER TABLE ... ADD COLUMN` e `DROP TABLE`. Retomada de `INSERT INTO` e `SELECT` para demonstrar o uso da estrutura criada.

### Exemplo prático sugerido

Criar uma tabela de fornecedores com identificador, nome e cidade. Inserir um fornecedor e acrescentar uma coluna de telefone, observando a mudança da estrutura. Demonstrar a remoção da tabela apenas no ambiente de treinamento.

### Pontos de atenção

Explicar que criar uma tabela não insere registros. Diferenciar `DELETE`, que remove linhas, de `DROP TABLE`, que remove a tabela e seus dados. Esclarecer que `NOT NULL` impede a ausência de valor, mas não impede, por si só, um texto vazio.

### Resultado esperado

Ao final da aula, o estudante deverá compreender uma definição simples de tabela e distinguir alterações na estrutura de alterações nos registros.

## 8. Aula 5 - JOIN

### Objetivo de aprendizagem

Consultar informações relacionadas que estão distribuídas em duas tabelas, compreendendo a condição de ligação e a diferença entre `INNER JOIN` e `LEFT JOIN`.

### Conteúdos e sequência de abordagem

1. Apresentar o uso de tabelas separadas para clientes e pedidos.
2. Explicar a relação entre o identificador do cliente e sua referência na tabela de pedidos.
3. Identificar a origem das colunas com a forma `tabela.coluna`.
4. Definir a condição de ligação entre as tabelas usando `ON`.
5. Consultar as correspondências com `INNER JOIN`.
6. Preservar os registros da tabela à esquerda com `LEFT JOIN`, mesmo sem correspondência.
7. Interpretar a repetição de um cliente que possui vários pedidos e a presença de `NULL` quando não há pedido correspondente.

### Comandos e elementos previstos

`SELECT`, `FROM`, `INNER JOIN`, `LEFT JOIN` e `ON`. Uso de `AS` e `ORDER BY` como apoio à apresentação dos resultados.

### Exemplo prático sugerido

Combinar clientes e pedidos para mostrar o nome de quem realizou cada compra. Comparar o resultado de `INNER JOIN` com o de `LEFT JOIN`, incluindo um cliente que ainda não realizou pedidos.

### Pontos de atenção

Diferenciar o identificador do pedido da referência ao cliente. Explicar que a repetição do nome no resultado pode decorrer da existência de vários pedidos e não significa duplicação do cadastro. Mostrar que a junção produz um resultado de consulta sem fundir permanentemente as tabelas.

### Resultado esperado

Ao final da aula, o estudante deverá identificar as colunas que relacionam duas tabelas e escolher entre os dois tipos de junção apresentados de acordo com a consulta desejada.

## 9. Critérios de revisão antes da produção

- Verificar a correspondência entre os conteúdos das aulas e os exercícios de cada módulo.
- Conferir a sintaxe e os resultados dos exemplos no PostgreSQL utilizado pela plataforma.
- Manter os nomes de tabelas, colunas e dados consistentes entre as demonstrações.
- Ensaiar as aulas para adequar o conteúdo à duração prevista, preservando a clareza da explicação.
- Revisar as legendas, especialmente os termos SQL e os valores apresentados.
- Confirmar que cada aula prepara o estudante para realizar a trilha prática correspondente.

## 10. Documento de referência

**Cappyo - Certificadora de Competência Comum.** Planejamento do projeto, arquivo `Cappyo.pdf`, 4 páginas, sem data indicada.

A organização das aulas detalha os cinco módulos previstos no planejamento. Os comandos, a sequência de abordagem e os exemplos práticos apresentados neste roteiro constituem uma proposta pedagógica para apreciação do professor e revisão da equipe.
