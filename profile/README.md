<div align="center">

# Hyze Cloud

**Infraestrutura cloud, sem fricção.**

Deploy de aplicações, bancos de dados e automação via API —  
simples, rápido e feito para quem constrói produto.

<br />

[Website](https://hyzecloud.com) · [Documentação](https://docs.hyzecloud.app) · [Dashboard](https://hyzecloud.com/dashboard) · [API](https://api.hyzecloud.com)

</div>

---

### O que fazemos

Hyze Cloud é uma plataforma de cloud hosting para times e desenvolvedores que querem **subir, escalar e operar** aplicações com o mínimo de overhead.

| | |
| :--- | :--- |
| **Apps** | Deploy a partir de GitHub, ZIP ou runtime nativo (Node, Bun, Python) |
| **Databases** | Postgres, MySQL, MariaDB, Mongo e Redis gerenciados |
| **API & SDK** | Controle programático de toda a plataforma |
| **Proxy & edge** | Domínios, roteamento e exposição segura das apps |

---

### Open source

Construímos em público o que faz sentido compartilhar.

| Repositório | Descrição |
| :--- | :--- |
| [`hyzecloud-sdk-ts`](https://github.com/Hyze-Cloud/hyzecloud-sdk-ts) | SDK oficial TypeScript / Node / Bun |
| [`hyzecloud-docs`](https://github.com/Hyze-Cloud) | Documentação da API e da plataforma |

---

### Comece em minutos

```bash
npm install @hyzecloud/sdk
```

```ts
import { HyzeCloud } from "@hyzecloud/sdk";

const hyze = new HyzeCloud({
  apiKey: process.env.HYZE_API_KEY,
});

const { apps } = await hyze.apps.list();
```

Mais detalhes na [documentação](https://docs.hyzecloud.app).

---

<div align="center">

**Build fast. Ship clean.**

<br />

<sub>
  © Hyze Cloud · Feito com cuidado para quem desenvolve
</sub>

</div>
