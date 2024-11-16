# MACACO DE TURING LATEX

O pacote **macacodeturinglatex** é um pacote criado por [Wanderson Gomes da Costa](https://github.com/WandersonGomes) para facilitar a criação de capas e folhas de rosto para trabalhos do IFCE - Tianguá.

# COMANDOS

Adicione o arquivo **macacodeturinglatex.sty** em seu projeto e depois use o seguinte comando:

```latex
\usepackage{macacodeturinglatex}
```

Informando a logo para a capa:

```latex
\logo{img/logo.png}
```

Informando a instituição de ensino:

```latex
\instituicao{ INSTITUIÇÃO DE ENSINO }
```

Informando o campus:

```latex
\campus{ CAMPUS }
```

Informando o curso:

```latex
\curso{ CURSO }
```

Informando o autor do trabalho:

```latex
\autor{ AUTOR DO TRABALHO }
```

Informando o título do trabalho:

```latex
\titulo{ TÍTULO DO TRABALHO ACADÊMICO }
```

Informando o local de realização do trabalho:

```latex
\local{ LOCAL }
```

Informando o ano de realização do trabalho:

```latex
\ano{ ANO }
```

Informando a natureza do trabalho acadêmico:

```latex
\natureza{ NATUREZA DO TRABALHO }
```

Informando o docente responsável (orientador):

```latex
\docente{ PROFESSOR }
```

Gerando a capa:

```latex
\capa
```

Gerando a folha de rosto:

```latex
\folhaRosto
```

# EXEMPLO

> Use LuaLaTex

```latex
% Autor: Wanderson Gomes da Costa
% E-mail: dersom100@gmail.com

\documentclass[a4paper, 12pt]{article}
\usepackage[portuguese]{babel}
\usepackage[utf8]{inputenc}
\usepackage[left=3cm, top=3cm, right=2cm, bottom=2cm]{geometry}

\usepackage{macacodeturinglatex}

% DADOS PARA CAPA
\logo{img/logo.png}
\instituicao{ Instituto Federal de Educação, Ciência e Tecnologia do Ceará }
\campus{ Tianguá }
\curso{ Ciência da Computação }
\autor{ Wanderson Gomes da Costa }
\titulo{ Memorial Acadêmico }
\local{ Tianguá }
\ano{ 2024 }
\natureza{ Memorial apresentado ao curso de Ciência da Computação do Instituto Federal de Educação, Ciência e Tecnologia do Ceará (IFCE), \textit{Campus} Tianguá, como requisito parcial de avaliação na disciplina Metodologia do Trabalho Científico. }
\docente{ Prof. Dr. Fulano de Tal. }

\begin{document}
\capa
\folhaRosto
\end{document}
```
