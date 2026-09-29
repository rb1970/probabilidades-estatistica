# Probabilidades e Estatística B com R

Livro Quarto baseado em `Aulas_PEB_1.pdf` (105 slides, 22 exercícios) e no projeto em `Old quarto book/`. Conserva o estilo do livro anterior: tema Cosmo, barra lateral clara com o logótipo, secções numeradas e índice de página à direita. Os capítulos introdutórios sobre R, RStudio e documentação foram integrados antes dos exercícios. O conteúdo está em português europeu e inclui blocos nativos `{webr-r}` editáveis, executados no navegador através da extensão webR do projeto anterior.

## Construir

Instale [Quarto](https://quarto.org/docs/get-started/) e execute na pasta do projeto:

```sh
quarto preview
```

Para gerar os ficheiros estáticos:

```sh
quarto render
```

O resultado fica em `_site/`. Abra `preview.html` para ver o livro dentro da moldura de pré-visualização. Publique todo o diretório `_site/` num servidor HTTPS. O primeiro uso dos blocos interativos descarrega webR; requer internet. Os exemplos usam apenas funções de R base e podem ser copiados para uma instalação local de R.

O PDF disponibilizado contém matéria até à distribuição F. Embora o programa inicial anuncie também amostragem, estimação, testes de hipóteses e regressão, não há conteúdo dessas aulas neste PDF; essas partes não foram inventadas para o tutorial.
