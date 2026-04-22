# Bate-papo: Visualização de Dados na Prática

**R-Ladies | Apresentação em Quarto Revealjs**

Slides do bate-papo sobre visualização de dados na prática, desenvolvidos em Quarto com identidade visual R-Ladies.

---

## Sobre

Este repositório contém os slides do bate-papo **Visualização de Dados na Prática**, com foco em ferramentas, comunidades, referências e construção de portfólio para quem trabalha com análise e visualização de dados em R e Python.

A apresentação cobre seis blocos temáticos:

- Abertura e contexto
- Comunidades e aprendizado contínuo (TidyTuesday)
- Ferramentas e prática (R, Python, ggplot2)
- Profissionais e referências da área
- Construção prática de visualizações
- Fechamento e direcionamento

---

## Estrutura do repositório

```
.
├── slides_dataviz_rladies.qmd   # arquivo principal da apresentação
├── styles.css                    # estilo visual com cores R-Ladies
├── logo.png                      # logo exibida nos slides
├── guia_apresentacao_quarto.qmd  # guia para editar e usar a apresentação
└── README.md                     # este arquivo
```

---

## Como usar

### Pré-requisitos

Você precisa ter instalado:

- **R** (versão 4.2 ou superior): [cran.r-project.org](https://cran.r-project.org)
- **RStudio** (versão 2023 ou superior): [posit.co/download/rstudio-desktop](https://posit.co/download/rstudio-desktop)
- **Quarto** (versão 1.4 ou superior): [quarto.org/docs/get-started](https://quarto.org/docs/get-started)

### Clonando o repositório

```bash
git clone https://github.com/JenniferLopes/nome-do-repositorio.git
cd nome-do-repositorio
```

### Gerando os slides

Abra o arquivo `slides_dataviz_rladies.qmd` no RStudio e clique em **Render**, ou execute no terminal:

```bash
quarto render slides_dataviz_rladies.qmd
```

Os slides vão abrir no navegador automaticamente.

### Apresentando

Com os slides abertos no navegador:

| Ação | Tecla |
|---|---|
| Próximo slide | Seta direita ou Espaço |
| Slide anterior | Seta esquerda |
| Tela cheia | `F` |
| Visão geral | `O` |
| Modo apresentador | `S` |

---

## Como editar

Consulte o arquivo `guia_apresentacao_quarto.qmd` incluído neste repositório. Ele cobre em detalhe como editar texto, listas, tabelas, colunas, cores e como adicionar ou remover slides sem experiência prévia com Quarto.

Para gerar o guia em HTML:

```bash
quarto render guia_apresentacao_quarto.qmd
```

---

## Identidade visual

A apresentação usa o `styles.css` com as cores oficiais R-Ladies:

| Variável | Cor | Hex |
|---|---|---|
| `--rladies-purple` | Roxo principal | `#b048a2` |
| `--rladies-purple-light` | Roxo claro | `#d8b5d0` |
| `--rladies-purple-dark` | Roxo escuro | `#88398a` |
| `--rladies-gray` | Cinza texto | `#333333` |

Para adaptar para outra identidade visual, edite os valores no início do arquivo `styles.css`.

---

## Referências utilizadas

- R Graph Gallery: [r-graph-gallery.com](https://r-graph-gallery.com)
- Python Graph Gallery: [python-graph-gallery.com](https://python-graph-gallery.com)
- Data to Viz: [data-to-viz.com](https://www.data-to-viz.com)
- TidyTuesday: [github.com/rfordatascience/tidytuesday](https://github.com/rfordatascience/tidytuesday)
- Cédric Scherer: [cedricscherer.com](https://www.cedricscherer.com)
- Nicola Rennie: [nrennie.rbind.io](https://nrennie.rbind.io)
- Dataviz Inspiration: [dataviz-inspiration.com](https://www.dataviz-inspiration.com)

---

## Autora

**Jennifer Lopes**

Consultora, Mentora e Instrutora em R | Dra. em Melhoramento Genético de Plantas | Criadora do Café com R e cofundadora da R-Ladies Goiânia

- Portfólio: [jenniferlopes.quarto.pub/portifolio](https://jenniferlopes.quarto.pub/portifolio)
- LinkedIn: [linkedin.com/in/jennifer-luz-lopes](https://linkedin.com/in/jennifer-luz-lopes)
- GitHub: [github.com/JenniferLopes](https://github.com/JenniferLopes)
- YouTube: [youtube.com/@jennifercafecomr](https://youtube.com/@jennifercafecomr)

---

*Esta apresentação é parte do projeto Café com R. É open source. Use, adapte e compartilhe.*
