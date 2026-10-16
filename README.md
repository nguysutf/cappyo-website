# Cappyo

**Recurso Educacional Aberto para o ensino de SQL**

O **Cappyo** é um Recurso Educacional Aberto (REA) desenvolvido como projeto acadêmico da unidade curricular **Certificadora da Competência Comum**, da Universidade Tecnológica Federal do Paraná (UTFPR), campus Cornélio Procópio.

O projeto tem como objetivo tornar o aprendizado de **SQL (Structured Query Language)** mais acessível, interativo e envolvente, combinando materiais didáticos, exercícios práticos e elementos de gamificação.

Inspirado em plataformas de aprendizagem gamificada, como o Duolingo, o Cappyo propõe uma experiência progressiva, na qual estudantes desenvolvem conhecimentos sobre bancos de dados e SQL por meio de explicações, exemplos e desafios.

> **Estado do projeto:** em desenvolvimento. A landing page está implementada, enquanto os materiais didáticos e as funcionalidades da aplicação estão sendo desenvolvidos progressivamente.

## Acesso ao projeto

- **Website:** https://nguysutf.github.io/cappyo-website/
- **Documentação inicial:** https://nguysutf.github.io/cappyo-website/docs/
- **Repositório do website:** https://github.com/nguysutf/cappyo-website
- **Repositório da aplicação:** https://github.com/nguysutf/cappyo

## Objetivos

O Cappyo busca proporcionar uma experiência introdutória de aprendizagem de SQL, permitindo que pessoas sem experiência prévia em bancos de dados desenvolvam conhecimentos teóricos e práticos de maneira gradual.

Seus principais objetivos são:

- Apresentar os fundamentos de bancos de dados relacionais e da linguagem SQL.
- Disponibilizar materiais didáticos com linguagem simples e exemplos contextualizados.
- Organizar os conteúdos em uma trilha progressiva de aprendizagem.
- Desenvolver exercícios interativos para aplicação dos conhecimentos.
- Utilizar elementos de gamificação para incentivar o aprendizado contínuo.
- Disponibilizar publicamente os materiais educacionais produzidos pelo projeto.

### Público-alvo

O projeto é direcionado principalmente a estudantes iniciantes em tecnologia, programação e bancos de dados, além de pessoas interessadas em aprender SQL de forma autônoma.

## Organização do Cappyo

O projeto está dividido em dois ambientes complementares.

### Cappyo Website

O **Cappyo Website** é responsável pela apresentação pública do projeto e pela organização de sua documentação.

Está prevista a disponibilização de materiais teóricos, exemplos explicativos e videoaulas nesse ambiente, permitindo que estudantes consultem os conteúdos antes e durante as atividades práticas.

Atualmente, o website conta com uma landing page responsiva e uma página contendo a proposta acadêmica inicial do projeto.

### Cappyo App

O **Cappyo App** corresponde à aplicação educacional interativa, destinada à prática dos conhecimentos apresentados nos materiais didáticos.

Entre as funcionalidades previstas estão:

- Exercícios de múltipla escolha e preenchimento de comandos SQL.
- Organização e interpretação de consultas.
- Escrita e execução de comandos SQL.
- Feedback sobre as respostas dos estudantes.
- Progressão por lições, fases e níveis.
- Mecânicas de gamificação, como experiência (XP), vidas e acompanhamento do progresso.

Essas funcionalidades fazem parte do planejamento e não devem ser interpretadas como integralmente implementadas.

## Metodologia pedagógica

A proposta educacional do Cappyo está organizada em três elementos complementares:

| Elemento | Descrição |
|---|---|
| **Conteúdo textual** | Explicações teóricas e exemplos práticos organizados por assunto, disponibilizados no website. |
| **Videoaulas** | Vídeos curtos, planejados para ter entre 5 e 7 minutos, acompanhados de legendas como recurso de acessibilidade. |
| **Implementação prática** | Exercícios e atividades interativas desenvolvidos na aplicação Cappyo para reforçar os conhecimentos apresentados. |

A integração desses elementos busca proporcionar uma aprendizagem progressiva, associando a compreensão dos conceitos à sua aplicação prática.

## Conteúdos previstos

A trilha introdutória de SQL contempla os seguintes módulos:

1. **SQL Básico:** introdução aos bancos de dados relacionais e aos comandos fundamentais.
2. **Manipulação de Dados:** operações de inserção, atualização e exclusão de registros.
3. **WHERE Avançado:** condições, operadores e filtragem de informações.
4. **Gerenciamento de Tabelas:** criação e alteração de estruturas de tabelas.
5. **JOIN:** relacionamentos entre tabelas e combinação de informações.

Outros conceitos, como ordenação e agregação de dados, também fazem parte da proposta de aprendizagem.

A organização e a disponibilidade dos materiais poderão evoluir durante o desenvolvimento do projeto.

## Tecnologias utilizadas

### Website

- **HTML5:** estruturação semântica do conteúdo.
- **CSS3:** estilização, responsividade e apresentação visual.
- **GitHub Pages:** publicação do website e da documentação.
- **Git e GitHub:** versionamento e colaboração.

O website utiliza HTML e CSS estáticos, sem necessidade de instalação de dependências ou execução de um processo de compilação.

### Aplicação

A proposta técnica inicial prevê a utilização de React com TypeScript e SCSS no frontend, além de Node.js e TypeScript no backend.

O desenvolvimento da aplicação é mantido em um repositório independente.

## Executando o website localmente

**1. Clone o repositório:**

`git clone https://github.com/nguysutf/cappyo-website.git`

**2. Acesse o diretório:**

`cd cappyo-website`

**3. Abra o arquivo `index.html` em um navegador.**

Opcionalmente, utilize uma extensão como **Live Server**, disponível para o Visual Studio Code, para facilitar a visualização durante o desenvolvimento.

Não é necessário instalar pacotes ou configurar um servidor de aplicação para executar a versão atual do website.

## Estrutura do repositório

Os principais arquivos e diretórios são:

- `index.html` — página inicial de apresentação do Cappyo.
- `assets/css/style.css` — estilos e regras de responsividade da landing page.
- `docs/index.html` — documentação contendo a proposta acadêmica original do projeto.
- `README.md` — apresentação e orientações gerais do repositório.

A estrutura poderá ser ampliada conforme novos materiais didáticos forem incorporados.

## Acessibilidade

O website foi desenvolvido considerando práticas de acessibilidade e usabilidade, incluindo:

- Utilização de elementos HTML semânticos.
- Adaptação a diferentes tamanhos de tela.
- Navegação por teclado.
- Indicação visual de foco nos elementos interativos.
- Link para acesso direto ao conteúdo principal.
- Respeito à preferência do usuário por movimento reduzido.

A acessibilidade também integra o planejamento dos materiais educacionais, especialmente por meio da previsão de legendas nas videoaulas.

## Desenvolvimento e organização

O desenvolvimento do Cappyo é realizado de forma colaborativa, com acompanhamento das atividades por meio do GitHub e do Trello.

O planejamento contempla etapas de definição de escopo, estruturação dos conteúdos, desenvolvimento das funcionalidades, produção de materiais didáticos, testes, documentação e publicação.

**Quadro de atividades:** https://trello.com/b/4BRoHoeM/cappyo

## Equipe

Projeto desenvolvido por estudantes da Universidade Tecnológica Federal do Paraná (UTFPR), campus Cornélio Procópio:

- Caelayne Aparecida Ribeiro Soares
- Iandê de Freitas Richalski
- João Vitor de Oliveira Pinho
- Luiz Felipe Fernandes Ramos
- Pedro Lucas Sales Larini

## Licença

O Cappyo foi concebido como um Recurso Educacional Aberto, com o propósito de facilitar o acesso ao conhecimento.

A licença de distribuição e reutilização do código e dos materiais didáticos ainda precisa ser formalmente definida e documentada no repositório.

---

**Cappyo — Aprenda SQL de forma interativa.**

Projeto acadêmico desenvolvido na UTFPR — Campus Cornélio Procópio, 2026.
