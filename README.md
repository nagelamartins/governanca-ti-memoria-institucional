# Governança de TI e Memória Institucional na Administração Pública

## 📌 Sobre o projeto

Este repositório apresenta uma análise de dados desenvolvida como parte de um Projeto Integrador da graduação em Ciência de Dados.

O projeto tinha como objetivo apoiar a continuidade do desenvolvimento do SIGESPRO, um portal web criado para centralizar documentos, procedimentos e informações da Coordenação de Tecnologia da Informação (COTI) da Secretaria Municipal das Subprefeituras de São Paulo.

A análise foi realizada para investigar se a proposta de evolução contínua do portal estava alinhada aos desafios de governança de TI e preservação da memória institucional observados na administração pública.

---

## 🎯 Problema

Em muitos órgãos públicos, informações importantes permanecem dispersas entre documentos, planilhas, e-mails e conhecimento individual dos servidores.

Essa fragmentação dificulta a continuidade dos processos, aumenta a dependência de pessoas específicas e pode comprometer a preservação do conhecimento organizacional ao longo do tempo.

Diante desse cenário, surgiu a seguinte pergunta:

**Como a centralização do conhecimento pode contribuir para a governança de TI e a continuidade dos processos na administração pública?**

---

## ✍️ Minha contribuição

Este Projeto Integrador foi desenvolvido em equipe.

As atividades apresentadas neste repositório, no entanto, foram desenvolvidas integralmente por mim e incluíram:

* Busca e coleta de dados públicos;
* Preparação e tratamento das bases de dados;
* Limpeza e transformação dos dados utilizando Python e Pandas;
* Definição da metodologia de classificação dos investimentos em TI;
* Criação das visualizações;
* Interpretação dos resultados;
* Redação da análise técnica utilizada no relatório final do projeto.

---

## 🗄️ Bases de dados utilizadas

### TIC Governo Eletrônico, 2023 (Cetic.br)

Utilizada para analisar a existência de instrumentos formais de governança de TI em prefeituras brasileiras.

### Base Orçamentária da Prefeitura Municipal de São Paulo, 2025

Utilizada para analisar a distribuição dos investimentos em Tecnologia da Informação no exercício de 2025.

---

## ⚙️ Preparação dos dados

### Base CETIC

A planilha original apresentava células mescladas e estrutura voltada para leitura humana, dificultando a importação direta para o Pandas.

Foi realizada uma etapa prévia de organização dos dados no Excel antes da análise.

### Base Orçamentária

Os dados foram importados diretamente para Python.

Foram realizadas etapas de:

* seleção de colunas;
* filtragem;
* transformação dos dados;
* agrupamentos;
* criação de categorias analíticas.

---

## 📋 Metodologia

Para a análise dos investimentos em TI, foi criada uma função de classificação baseada nas descrições dos projetos e atividades presentes na base orçamentária.

As iniciativas foram agrupadas em três categorias:

| Categoria       | Critério                                       |
| --------------- | ---------------------------------------------- |
| Manutenção      | Operação e continuidade de sistemas existentes |
| Aquisição       | Compra de equipamentos, materiais ou serviços  |
| Desenvolvimento | Criação ou implantação de novas soluções       |

---

## 📊 Principais insights

### Governança de TI

* Capitais apresentam maior adoção de instrumentos formais de governança do que municípios do interior.
* Municípios maiores tendem a possuir maior maturidade em governança de TI.
* Mesmo em grandes municípios, ainda existem lacunas importantes relacionadas ao planejamento tecnológico.

### Orçamento de TI

* Aproximadamente 76,7% do orçamento analisado está concentrado em atividades de manutenção e continuidade.
* Apenas cerca de 1,8% está direcionado a novos desenvolvimentos.
* Os dados sugerem que a continuidade e evolução de sistemas existentes desempenham papel central na estratégia de tecnologia da administração pública.

---

## 🛠️ Ferramentas utilizadas

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook
* Excel

---

## ⚠️ Limitações

Esta análise foi conduzida com o objetivo de investigar se a continuidade do SIGESPRO estava alinhada às necessidades observadas na administração pública.

Dessa forma, a seleção das bases de dados e a construção da metodologia foram orientadas por essa hipótese inicial.

Além disso, a classificação das iniciativas orçamentárias foi construída especificamente para esta análise e pode ser refinada ou reinterpretada em estudos futuros.

---

## 📁 Estrutura do repositório

```text
├── dados/
├── notebook/
├── imagens/
├── relatorio/
└── README.md
```
---

## 📧 Contato:
  * [LinkedIn](https://www.linkedin.com/in/nagelamartins/)
  * [GitHub](https://github.com/nagelamartins)
  * [E-mail](mailto:nagela.msouza@gmail.com)

*Obrigada pela visita! 💛*
