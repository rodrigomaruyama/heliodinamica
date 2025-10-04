# Site da Heliodinâmica (página única)

Este repositório contém um site estático de **uma página** para o domínio `heliodinamica.com.br`.

## Como usar

1. **Substitua a imagem de fundo** pela fotografia do módulo fotovoltaico produzido pela Heliodinâmica:
   - Coloque o arquivo em: `assets/heliodinamica-modulo.jpg` (mesmo nome).
   - O `index.html` já referencia esse caminho.

2. **Abrir localmente**
   - Clique duas vezes em `index.html` ou sirva com qualquer servidor estático.

3. **Publicar no seu servidor**
   - Envie todos os arquivos para a raiz do domínio `heliodinamica.com.br`.

4. **Publicar no GitHub Pages (opcional)**
   - Crie um repositório e suba estes arquivos.
   - Ative o GitHub Pages (branch `main` ou `docs`).
   - (Opcional) Inclua um arquivo `CNAME` com o conteúdo `heliodinamica.com.br` e aponte o DNS para o GitHub:
     - Crie quatro registros `A` no seu provedor de DNS para os IPs do GitHub Pages.
     - Crie um `CNAME` `www` apontando para `<seu_usuario>.github.io`.

## Estrutura

```
.
├─ index.html                # Página única (CSS inline)
└─ assets/
   └─ heliodinamica-modulo.jpg  # Substitua por sua foto (não incluída)
```

## Créditos

- Layout minimalista e responsivo, com fundo em tela cheia e cartões translúcidos para legibilidade.
- Tipografia do sistema operacional (sem dependências).
