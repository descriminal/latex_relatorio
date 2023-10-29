```tex
\documentclass[a4paper, 12pt]{abntex2}

\usepackage[utf8]{inputenc}
\usepackage[brazil]{babel}
\usepackage{graphicx}
\usepackage{geometry} % Pacote para ajustar a margem
\usepackage{lipsum} % Pacote de texto de exemplo

% Informações do relatório
\title{Nome do Relatório}
\author{Seu Nome}
\local{Sua Cidade}
\date{\today}

\begin{document}

\newgeometry{top=3cm, bottom=3cm, left=3cm, right=3cm} % Definindo Margens

% Adicione o logotipo da faculdade
\begin{figure}
\centering
\includegraphics[width=0.4\textwidth]{nomedaimagem.jpg} % Substitua nomedaimagem.jpg pela sua imagem
\end{figure}

\maketitle

\newpage % Quebra de Página após título

% Sumário
\tableofcontents

\newpage % Quebra de Página após título

\section{Introdução}
Nesta seção, você pode introduzir o contexto da experiência e explicar o problema que está sendo abordado.

\section{Fundamentação Teórica}
Nesta seção, forneça informações teóricas relevantes relacionadas à sua experiência.

\section{Metodologia}
Descreva os materiais e equipamentos utilizados, bem como os métodos e processos empregados na realização da experiência.

\section{Resultados}
Apresente os Resultados da experiência de forma clara e concisa, usando tabelas e figuras se necessário.

\section{Discussão}
Analise e interprete os resultados obtidos. Explique qualquer tendência ou padrão observado e discuta as implicações de suas descobertas.

\section{Conclusão}
Resuma as principais conclusões da experiência e indique qualquer trabalho futuro que possa ser necessário.

\newpage % Quebra de Página após título

% Referências
\bibliography{referencias}

% Restaurando margens padrão
\restoregeometry

\end{document}
```
