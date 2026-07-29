
# Redirect Portfolio: GitHub Pages to Framer

Este repositório contém o arquivo `index.html` responsável por fazer o redirecionamento automático do domínio/link anterior do portfólio oficial do pianista e compositor **Daniel Grajew** para a nova plataforma desenvolvida no **Framer**.

---

## 🚀 Como Funciona

O arquivo `index.html` utiliza duas abordagens simples de redirecionamento:
1. **Meta Refresh Tag:** Redireciona o visitante instantaneamente (`0` segundos) para o novo endereço.
2. **Fallback Manual:** Apresenta um hiperlink direto caso o navegador do visitante não execute o redirecionamento automático.

---

## 🛠️ Código Atual do `index.html`

```html
<!doctype html>
<html lang="pt-BR">
  <head>
    <meta charset="utf-8">
    <title>Redirecionando...</title>
    <meta http-equiv="refresh" content="0; url=[https://danielgrajew.framer.website/daniel-grajew](https://danielgrajew.framer.website/daniel-grajew)">
  </head>
  <body>
    <p>Redirecionando para <a href="[https://danielgrajew.framer.website/daniel-grajew](https://danielgrajew.framer.website/daniel-grajew)">[https://danielgrajew.framer.website/daniel-grajew](https://danielgrajew.framer.website/daniel-grajew)</a></p>
  </body>
</html>
