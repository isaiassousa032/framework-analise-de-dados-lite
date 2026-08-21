# Framework de Análise de Dados — Lite

Framework enxuto para estruturar **projetos curtos de análise de dados**, com foco em prática, repetição do processo analítico e desenvolvimento do raciocínio sobre dados.

A proposta é aplicar um processo de análise completo sem adicionar documentação ou complexidade desnecessária.

> **Pequeno no escopo, completo no raciocínio.**

---

## Sobre o framework

O **Framework de Análise de Dados — Lite** foi criado como uma versão reduzida do meu framework principal de análise de dados.

Enquanto a versão completa é destinada principalmente a projetos médios e longos, esta versão foi pensada para análises rápidas, normalmente desenvolvidas entre **1 e 5 dias**.

O objetivo não é explorar todas as possibilidades de um dataset, mas responder a um conjunto claro de perguntas utilizando evidências.

O processo segue cinco etapas:

```text
Entender
   ↓
Perguntar
   ↓
Analisar
   ↓
Interpretar
   ↓
Concluir
```

---

## Objetivo

O framework busca tornar mais frequente a prática do ciclo completo de análise:

**dados → perguntas → análise → evidências → conclusões**

Isso permite utilizar diferentes datasets, ferramentas e técnicas sem transformar cada análise em um projeto de grande duração.

Entre os principais objetivos estão:

- desenvolver raciocínio analítico;
- praticar análise exploratória de dados;
- melhorar a formulação de perguntas;
- aprender a selecionar métricas e dimensões relevantes;
- desenvolver interpretação de resultados;
- praticar diferentes técnicas de análise;
- experimentar diferentes ferramentas;
- comunicar conclusões de maneira objetiva.

---

## Quando usar

Este framework é indicado principalmente para:

- mini projetos de análise;
- datasets utilizados em cursos e trilhas de estudo;
- datasets públicos;
- estudos exploratórios;
- exercícios de SQL;
- análises com Python;
- análises em Excel ou Google Sheets;
- projetos rápidos em Power BI;
- prática de estatística aplicada;
- experimentação de novas técnicas analíticas.

Para projetos maiores, com maior necessidade de planejamento, documentação e aprofundamento, deve ser utilizado o **Framework de Análise de Dados completo**.

---

## Estrutura

O repositório contém três documentos principais:

### `framework-lite.md`

Apresenta o processo completo do Framework Lite e as perguntas que orientam cada etapa da análise.

### `template-analise-lite.md`

Template reutilizável para documentar uma análise curta, incluindo:

- contexto;
- entendimento dos dados;
- pergunta principal;
- perguntas analíticas;
- hipóteses;
- evidências;
- interpretações;
- conclusões;
- limitações;
- aprendizados.

### `checklist-projeto-curto.md`

Checklist para acompanhar o projeto e identificar quando a análise possui evidências suficientes para ser considerada concluída.

---

## Princípios

### 1. Começar pelo problema

A ferramenta não define a análise.

Primeiro é necessário entender o problema e formular as perguntas. Depois são escolhidas as técnicas e ferramentas adequadas.

### 2. Entender antes de analisar

Antes dos cálculos, é necessário compreender aspectos básicos dos dados:

- o que uma linha representa;
- qual é a granularidade;
- qual é a unidade de análise;
- quais são os fatos;
- quais são as dimensões;
- quais métricas são relevantes.

### 3. Analisar com propósito

Uma análise deve existir porque ajuda a responder uma pergunta.

Não é necessário criar gráficos, métricas ou cálculos apenas porque são possíveis.

### 4. Evidência não é conclusão

Encontrar um número ou padrão é apenas o começo.

O processo deve avançar de:

```text
Resultado
   ↓
Evidência
   ↓
Interpretação
   ↓
Conclusão
```

### 5. Saber quando parar

Um dataset pode permitir dezenas de análises diferentes.

Isso não significa que todas precisam ser realizadas.

> **O projeto termina quando as perguntas propostas foram respondidas com evidências suficientes.**

Novas perguntas podem originar novos projetos.

---

## Laboratório de Análises de Dados

Este framework foi desenvolvido principalmente para apoiar os projetos do repositório **`laboratorio-analises-de-dados`**.

O laboratório reúne projetos curtos utilizando diferentes abordagens, ferramentas e técnicas, como:

- SQL;
- Python;
- pandas;
- Excel;
- Google Sheets;
- Power BI;
- estatística descritiva;
- análise exploratória;
- análise temporal;
- segmentação;
- comparação;
- visualização de dados.

A intenção é aumentar a frequência com que o processo completo de análise é praticado, enquanto projetos médios e longos continuam sendo utilizados para desenvolver análises mais profundas e soluções end-to-end.

---

## Filosofia

Projetos curtos não significam análises incompletas.

O escopo pode ser pequeno enquanto o raciocínio permanece estruturado.

O objetivo deste framework é justamente encontrar esse equilíbrio:

> **menos documentação, menos complexidade e mais ciclos completos de análise.**