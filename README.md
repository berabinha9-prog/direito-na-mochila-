# Direito na Mochila: o site

Site do e-book gratuito **Direito na Mochila**, do Grupo Escoteiro Santos Dumont (20º Curitiba PR).

A página é uma trilha: você rola, o escoteiro (ou a escoteira) sobe a montanha e, em cada marco, responde se uma frase do livro é mito ou verdade. Cada caminhada sorteia 8 marcos entre 48 (nunca dois do mesmo capítulo) e 14 frases escoteiras entre 48.

## Como editar

Tudo fica em `index.html`, sem build:

- Perguntas: array `BANCO` (capítulo, ponto, frase, `M` ou `V`, explicação). Manter 24 mitos e 24 verdades.
- Frases escoteiras: array `FRASES`.
- Depois de salvar no GitHub, o GitHub Pages atualiza o site em 1 ou 2 minutos.

## Publicação

GitHub Pages, branch `main`, pasta raiz.
