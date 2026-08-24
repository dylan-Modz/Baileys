# Baileys — Tokito

Versão modificada da Baileys usada pela Tokito Bot V10.

## Instalação direta pelo GitHub

No `package.json` da Tokito, use o repositório GitHub desta base como dependência.

Exemplo se o repositório for `DylanModz/Baileys`:

```json
{
  "dependencies": {
    "baileys": "github:DylanModz/Baileys#main"
  }
}
```

Nos arquivos do bot:

```js
const { proto } = require('baileys')
```

ou, por ser um pacote ESM, quando necessário:

```js
const baileys = await import('baileys')
```

## Importante

Este repositório já contém os arquivos compilados em `lib/`, então não depende de `src/` nem de TypeScript para ser instalado a partir do GitHub.

As alterações de botões da Tokito foram preservadas no conteúdo desta versão.
