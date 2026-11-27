<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./hyze-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="./hyze-logo-light.png">
  <img src="./hyze-logo-light.png" alt="Hyze Cloud" width="260">
</picture>

<br><br>

<img src="./hyze-banner.gif" alt="O Rack, mascote da Hyze, faz o deploy: o código sai do computador, o foguete sobe e as máquinas de sites, APIs e bots acendem." width="100%">

### Hospedagem brasileira para sites, APIs e bots.

Mande o código pelo GitHub ou num ZIP: a Hyze faz o build e coloca no ar com HTTPS,<br>
com o banco de dados no mesmo painel. Em reais, no Pix ou no cartão, com suporte em português.

<br>

[![Testar 7 dias grátis](https://img.shields.io/badge/Testar%207%20dias%20gr%C3%A1tis-7c46ce?style=for-the-badge)](https://hyzecloud.com/pt-br/signup?utm_source=github&utm_medium=org_profile)
[![Site](https://img.shields.io/badge/hyzecloud.com-18181b?style=for-the-badge)](https://hyzecloud.com/pt-br?utm_source=github&utm_medium=org_profile)
[![Documentação](https://img.shields.io/badge/Documenta%C3%A7%C3%A3o-18181b?style=for-the-badge)](https://docs.hyzecloud.app/pt?utm_source=github&utm_medium=org_profile)

</div>

---

### O que dá para colocar no ar

| | |
| :--- | :--- |
| **[Bots](https://hyzecloud.com/pt-br/bot-discord?utm_source=github&utm_medium=org_profile)** | Discord, WhatsApp e Telegram, ligados 24 horas, sem PC aberto |
| **[APIs](https://hyzecloud.com/pt-br/hospedar-api?utm_source=github&utm_medium=org_profile)** | Node.js, Bun, Python e Go, com endereço `seuapp.hyzecloud.app` e HTTPS na hora |
| **[Sites](https://hyzecloud.com/pt-br/sites?utm_source=github&utm_medium=org_profile)** | Next.js, Vite, Astro e sites estáticos, com domínio próprio |
| **[Bancos de dados](https://hyzecloud.com/pt-br/banco-de-dados?utm_source=github&utm_medium=org_profile)** | PostgreSQL, MySQL, MongoDB e Redis no mesmo painel, com backup diário |
| **[CDN](https://docs.hyzecloud.app/pt/guides/cdn?utm_source=github&utm_medium=org_profile)** | Imagens, vídeos e arquivos com link em `cdn.hyzecloud.app`, públicos ou privados |

Planos a partir de **R$ 5,99/mês** · [ver preços](https://hyzecloud.com/pt-br/pricing?utm_source=github&utm_medium=org_profile)

---

### Para quem programa

| Ferramenta | Como instalar | |
| :--- | :--- | :--- |
| **CLI** | `npm i -g @hyze-cloud/cli` | Deploy, builds e logs pelo terminal |
| **SDK TypeScript** | `npm i @hyze-cloud/sdk` | Node.js e Bun · [repositório](https://github.com/Hyze-Cloud/hyzecloud-sdk-ts) |
| **SDK Python** | `pip install hyze-cloud` | Cliente sync e async · [repositório](https://github.com/Hyze-Cloud/hyzecloud-sdk-python) |
| **MCP** | [hyzecloud.com/ia](https://hyzecloud.com/pt-br/ia?utm_source=github&utm_medium=org_profile) | Conecte Claude Code, Cursor ou Codex à sua conta |

```bash
npm i -g @hyze-cloud/cli
hyze login                     # entra pelo navegador
hyze deploy . --name meu-bot   # sobe a pasta atual e acompanha o build
```

```ts
import { HyzeCloud } from "@hyze-cloud/sdk";

const hyze = new HyzeCloud({ apiKey: process.env.HYZE_API_KEY });
const { apps } = await hyze.apps.list();
```

---

<div align="center">
<sub>Hyze Cloud · hospedagem brasileira de sites, APIs e bots · <a href="https://status.hyzecloud.com">status</a> · <a href="https://hyzecloud.com/pt-br/changelog?utm_source=github&utm_medium=org_profile">novidades</a></sub>
</div>
