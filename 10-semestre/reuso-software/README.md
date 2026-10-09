# QXD0068 — Reuso de Software (2026.2 — Turma 1A)

[![UFC](https://img.shields.io/badge/UFC-Quixadá-00519C?style=for-the-badge)](https://www.ufc.quixada.ufc.br/)
[![QXD0068](https://img.shields.io/badge/Código-QXD0068-2ea44f?style=for-the-badge)](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software)
[![2026.2](https://img.shields.io/badge/Semestre-2026.2-orange?style=for-the-badge)](../../)

Material de estudo da disciplina **Reuso de Software (QXD0068)**, optativa do curso de **Bacharelado em Engenharia de Software** da Universidade Federal do Ceará — Campus Quixadá.

> **Repositório oficial da disciplina (prof. Francisco Victor)**
> 👉 [pinheirovictor/2026.2_QXD0068_reuso_de_software](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software)
> Contém os códigos-exemplo das aulas práticas de padrões de projeto:
> `strategy-frete`, `factory_notification`, `observer-pedido`, `decorator-cafe`, `facade-compra`.

## Sobre a disciplina

| | |
|:---|:---|
| **Código** | QXD0068 |
| **Nome** | Reuso de Software |
| **Período** | 2026.2 — Turma 1A |
| **Professor** | [Francisco Victor da Silva Pinheiro](https://github.com/pinheirovictor) |
| **Instituição** | UFC — Campus Quixadá |
| **Categoria** | Optativa |

### Ementa (resumo)

Estudo dos fundamentos, técnicas e tecnologias de reuso de software: conceitos e importância, aspectos organizacionais e institucionalização, engenharia de domínio, engenharia de aplicação (padrões de projeto, frameworks), tecnologias de reuso (componentes, middlewares, SOA/microsserviços, linhas de produto) e aspectos gerenciais (métricas de reuso). Inclui formação em pesquisa acadêmica (artigo científico).

### Avaliação

| Componente | Descrição |
|:---|:---|
| **AP1** | Prova escrita dos Módulos 1 e 2 (23/09) |
| **Trabalho 1** | Refatoração com padrões de projeto em sistema legado (entrega 13/10, apresentação 14/10) |
| **Trabalho 2** | Serviço reutilizável (SOA/microserviço) ou Mini-LPS (apresentação 27/11) |
| **Trabalho Final** | Artigo científico em equipes (apresentação e entrega 09/12) |
| **Pesquisa** | 5 marcos + oficinas de pesquisa acadêmica ao longo do semestre |

### Trabalho Final — marcos

| Marco | Conteúdo | Data-limite |
|:---|:---|:---|
| 1 | Equipe, tema e título provisório | 04/09 |
| 2 | Problema, justificativa, objetivos e questões de pesquisa | 07/10 |
| 4 | Protocolo da pesquisa | 18/11 |
| 5 | Acompanhamento da execução | 25/11 |
| — | Artigo científico final | 09/12 |

### Referência para seleção de projetos (Trabalho 1)

- [CodeTriage](https://www.codetriage.com/)

### Bibliografia

A bibliografia básica e complementar está no **Plano de Aula de Reuso - 2026.2.pdf**, dentro da pasta `Aula-00`. Ponto-chave da disciplina: **Design Patterns — GoF** (Gamma, Helm, Johnson, Vlissides).

---

## Estrutura deste material

Organização por aula, seguindo o plano de aulas da disciplina. Cada pasta contém os slides em PDF daquela data.

### Módulo 1 — Fundamentos e Aspectos Organizacionais

| Pasta | Data | Conteúdo |
|:---|:---:|:---|
| [Aula-00](./Aula-00%20-%2012-08%20-%20Apresentação%20da%20disciplina) | 12/08 | Apresentação da disciplina, ementa, avaliação, resultados esperados, bibliografia. Plano de aulas completo. |
| [Aula-01](./Aula-01%20-%2014-08%20-%20Conceitos%20e%20importância%20do%20reuso) | 14/08 | Conceitos e importância do reuso de software; estado da arte e da prática; relação com Engenharia de Software. |
| [Aula-02](./Aula-02%20-%2019-08%20-%20Aspectos%20gerais%20do%20reuso) | 19/08 | Aspectos gerais do reuso; níveis e tipos de artefatos reutilizáveis; aspectos organizacionais (programas de reuso, serviços de suporte); tipos de reuso. |
| [Aula-03](./Aula-03%20-%2021-08%20-%20Institucionalização%20do%20reuso%20e%20barreiras) | 21/08 | Institucionalização do reuso e barreiras culturais, técnicas e gerenciais. Apresentação do Trabalho Final (artigo científico), temas de pesquisa e formação das equipes. |

### Módulo 2 — Engenharia de Domínio e Aplicação

| Pasta | Data | Conteúdo |
|:---|:---:|:---|
| [Aula-04](./Aula-04%20-%2026-08%20-%20Engenharia%20de%20domínio) | 26/08 | Engenharia de domínio: construção de artefatos reutilizáveis; análise de domínio e variabilidades. Descrição do Trabalho 1 (refatoração com padrões). |
| [Aula-05](./Aula-05%20-%2028-08%20-%20Paradigmas%20de%20programação%20e%20reutilização) | 28/08 | Paradigmas de programação e reutilização; Orientação a Objetos para reuso (abstração e parametrização); composição, acoplamento e coesão. |
| [Aula-06](./Aula-06%20-%2002-09%20-%20Introdução%20a%20padrões%20de%20projeto%20(GoF)) | 02/09 | Introdução aos padrões de projeto; o papel do GoF ("Gang of Four") e os 23 padrões clássicos. |
| [Aula-07](./Aula-07%20-%2004-09%20-%20Padrões:%20Strategy,%20Factory,%20Adapter) | 04/09 | Padrões de projeto: **Strategy**, **Factory Method** e **Adapter**. Códigos-exemplo no repositório da disciplina. |
| [Aula-08](./Aula-08%20-%2009-09%20-%20Padrões:%20Observer,%20Decorator,%20Facade) | 09/09 | Padrões de projeto: **Observer**, **Decorator** e **Facade**. |
| [Aula-09](./Aula-09%20-%2011-09%20-%20Padrões:%20Template%20Method,%20Proxy,%20State) | 11/09 | Padrões de projeto: **Template Method**, **Proxy** e **State**. |
| [Aula-10](./Aula-10%20-%2016-09%20-%20Padrões:%20Composite,%20Command,%20Builder,%20Singleton) | 16/09 | Padrões de projeto: **Composite**, **Command**, **Builder** e **Singleton**. |
| [Aula-11](./Aula-11%20-%2018-09%20-%20Revisão%20dos%20módulos%201%20e%202) | 18/09 | Revisão dos Módulos 1 e 2; preparação para a AP1; quiz de reuso (ponto bônus). |
| [Aula-12](./Aula-12%20-%2023-09%20-%20Avaliação%20Parcial%201) | 23/09 | **Avaliação Parcial 1** — prova escrita dos Módulos 1 e 2. Contém o gabarito. |
| [Aula-13](./Aula-13%20-%2025-09%20-%20Oficina%20de%20Pesquisa%20Acadêmica%20I) | 25/09 | **Oficina de Pesquisa Acadêmica I** — do tema ao problema de pesquisa: delimitação do tema, formulação do problema, objetivos geral e específicos, questões de pesquisa. |
| [Aula-14](./Aula-14%20-%2030-09%20-%20Frameworks%20de%20aplicação) | 30/09 | Correção da AP1; frameworks de aplicação e engenharia de aplicação: paradigmas e ciclo de vida. |
| [Aula-15](./Aula-15%20-%2002-10%20-%20Marco%202:%20problema%20e%20objetivos) | 02/10 | **Trabalho Final — Marco 2**: problema, justificativa, objetivo geral, objetivos específicos e questões de pesquisa. Contém a proposta de pesquisa da equipe (Reuso em Microsserviços). |
| [Aula-16](./Aula-16%20-%2007-10%20-%20Tecnologias%20de%20reuso:%20componentes,%20middleware,%20SOA) | 07/10 | Tecnologias de reuso: componentes e middleware; engenharia baseada em serviços (SOA, microsserviços). |
| [Aula-17](./Aula-17%20-%2009-10%20-%20Oficina%20de%20Pesquisa%20Acadêmica%20II) | 09/10 | **Oficina de Pesquisa Acadêmica II** — busca bibliográfica e trabalhos relacionados: palavras-chave, bases científicas, seleção de estudos, organização de referências e matriz de trabalhos relacionados. |

### Módulo 3 — Tecnologias e Gestão do Reuso (a partir de 30/10)

| Aula | Data | Conteúdo |
|:---|:---:|:---|
| Aula 18 | 14/10 | Apresentação do Trabalho 1 — refatoração com padrões de projeto em sistema legado |
| Aula 19 | 30/10 | Tecnologias de reuso: Linha de Produtos de Software |
| Aula 20 | 04/11 | Aspectos gerenciais: métricas de reuso |
| Aula 21 | 06/11 | Oficina de Pesquisa Acadêmica III — planejamento e condução da pesquisa |
| Aula 22 | 11/11 | Encontros Universitários no Campus da UFC em Quixadá |
| Aula 23 | 13/11 | Oficina de Pesquisa Acadêmica IV — coleta de dados e reprodutibilidade |
| Aula 24 | 18/11 | Trabalho Final — Marco 4: protocolo da pesquisa |
| Aula 25 | 25/11 | Trabalho Final — Marco 5: acompanhamento da execução |
| Aula 26 | 27/11 | Apresentação do Trabalho 2 — serviço reutilizável (SOA/microserviço) ou Mini-LPS |
| Aula 27 | 02/12 | Orientação das equipes — Trabalho Final |
| Aula 28 | 04/12 | Oficina de Escrita Acadêmica V — estrutura e preparação do artigo científico |
| Aula 29 | 09/12 | Apresentação e entrega do Trabalho Final — Artigo Científico |
| Aula 30 | 11/12 | Segunda chamada da AP1 |

Datas sem aula: **16/10** (Recesso — Dia do Professor), **21/10 e 23/10** (XV IHC), **20/11** (Feriado — Dia da Consciência Negra).

---

## Conteúdo por pasta (arquivos)

| Pasta | Arquivos |
|:---|:---|
| `Aula-00` | `Aula 00 - [QXD0068 - 1A] Apresentação da disciplina.pdf`, `Plano de Aula de Reuso - 2026.2.pdf` |
| `Aula-01` | `Aula 01 - Conceitos e importância do reuso de software.pdf` |
| `Aula-02` | `Aula 02 - Aspectos gerais do reuso.pdf`, `Aula 02.1 - Aspectos organizacionais.pdf` |
| `Aula-03` | `Aula 03 - Institucionalização do reuso e barreiras.pdf`, `Aula 03.1 - Pesquisa em Reuso com Potencial de Publicação.pdf` |
| `Aula-04` | `Aula 04 - Engenharia de Domínio.pdf` |
| `Aula-05` | `Aula 05 - Paradigmas de programação e reutilização.pdf`, `Aula 05.1 - Composição em OO, Acoplamento e Coesão.pdf` |
| `Aula-06` | `Aula 06 - Introdução a Padrões de Projeto: GoF e os 23 Padrões Clássicos.pdf` |
| `Aula-07` | `Aula 07 - Strategy.pdf`, `Aula 07.1 - Factory Method.pdf`, `Aula 07.2 - Adapter.pdf` |
| `Aula-08` | `Aula 08 - Observer.pdf`, `Aula 08.1 - Decorator.pdf`, `Aula 08.2 - Facade.pdf` |
| `Aula-09` | `Aula 09 - Template Method.pdf`, `Aula 09.1 - Proxy.pdf`, `Aula 09.2 - State.pdf` |
| `Aula-10` | `Aula 10 - Composite.pdf`, `Aula 10.1 - Command.pdf`, `Aula 10.2 - Builder.pdf`, `Aula 10.3 - Singleton.pdf` |
| `Aula-11` | `Aula 11 - Revisão dos Módulos 1 e 2.pdf` |
| `Aula-12` | `GABARITO.pdf` (gabarito da AP1) |
| `Aula-13` | `Aula 13 - Oficina de Pesquisa Acadêmica I.pdf` |
| `Aula-14` | `Aula 14 - Frameworks de Aplicação e o Ciclo de Vida na Engenharia de Aplicação.pdf` |
| `Aula-15` | `Proposta de Pesquisa - Reuso em Microsserviços.pdf` (Marco 2 da equipe) |
| `Aula-16` | `Aula 16 - Componentes e Middleware.pdf`, `Aula 16.1 - Engenharia baseada em Serviços.pdf` |
| `Aula-17` | `Aula 17 - Oficina de Pesquisa Acadêmica II.pdf` |

---

## Padrões de projeto cobertos

| Aula | Padrões |
|:---:|:---|
| 07 | Strategy, Factory Method, Adapter |
| 08 | Observer, Decorator, Facade |
| 09 | Template Method, Proxy, State |
| 10 | Composite, Command, Builder, Singleton |

Exemplos de código no repositório da disciplina: [strategy-frete](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software/tree/main/strategy-frete), [factory_notification](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software/tree/main/factory_notification), [observer-pedido](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software/tree/main/observer-pedido), [decorator-cafe](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software/tree/main/decorator-cafe), [facade-compra](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software/tree/main/facade-compra).

---

## Links úteis

- [Repositório oficial da disciplina](https://github.com/pinheirovictor/2026.2_QXD0068_reuso_de_software)
- [CodeTriage — projetos open source para o Trabalho 1](https://www.codetriage.com/)
- [Repositório do meu curso](https://github.com/josiasdev/esufcqx) — outros materiais da Engenharia de Software (UFC Quixadá)
