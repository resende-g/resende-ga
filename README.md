# resende-ga — roteiros dos vídeos

Repositório para organizar e publicar roteiros em Markdown com [mdBook](https://rust-lang.github.io/mdBook/). O site adota a paleta prata, grafite e vermelho e as superfícies translúcidas do [portfólio resende-g](https://github.com/resende-g/resende-g.github.io).

Site: <https://resende-g.github.io/resende-ga/>

## Adicionar um roteiro

1. Copie `src/modelo.md` para `src/um-titulo-curto.md`.
2. Escreva e revise o roteiro.
3. Inclua o arquivo em `src/SUMMARY.md`. Apenas páginas listadas nesse sumário aparecem no site.
4. Envie a alteração para `main`; o GitHub Actions compila e publica o livro.

Mantenha rascunhos fora de `SUMMARY.md` até decidir que podem ser publicados.

## Visualizar localmente

Instale o mdBook e execute na raiz do repositório:

```sh
mdbook serve --open
```

## Publicação

O workflow em `.github/workflows/deploy.yml` compila o livro e o publica em GitHub Pages ao receber alterações na branch `main`. Ele também configura a origem do Pages como **GitHub Actions** na primeira execução.

## Licença

O conteúdo original deste repositório está sob **CC0 1.0 Universal**, conforme `LICENSE`. Isso permite que outras pessoas reutilizem os roteiros sem pedir autorização. A licença não cobre materiais de terceiros que você incluir; confira os direitos desses materiais antes de publicá-los.
Créditos: https://github.com/Soberana-TV/tecnologiaeclasse
