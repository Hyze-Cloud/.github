<div align="center">
  <img src="./hyze-logo.png" alt="Hyze Cloud" width="360" />
</div>

<br />

<div align="center">

**Infraestrutura cloud, sem fricção.**

Deploy de aplicações, bancos de dados e automação via API —  
simples, rápido e feito para quem constrói produto.

<br />

[Website](https://hyzecloud.com)
&nbsp;·&nbsp;
[Documentação](https://docs.hyzecloud.app)
&nbsp;·&nbsp;
[Dashboard](https://hyzecloud.com/dashboard)
&nbsp;·&nbsp;
[API](https://api.hyzecloud.com)

</div>

---

### O que fazemos

Plataforma de cloud hosting para times e desenvolvedores que querem **subir, escalar e operar** aplicações com o mínimo de overhead.

| | |
| :--- | :--- |
| **Apps** | Deploy via GitHub, ZIP ou runtime nativo (Node, Bun, Python) |
| **Databases** | Postgres, MySQL, MariaDB, Mongo e Redis gerenciados |
| **API & SDK** | Controle programático de toda a plataforma |
| **Proxy & edge** | Domínios, roteamento e exposição segura das apps |

---

### Open source

| Repositório | Descrição |
| :--- | :--- |
| [`hyzecloud-sdk-ts`](https://github.com/Hyze-Cloud/hyzecloud-sdk-ts) | SDK oficial TypeScript / Node / Bun |
| [`hyzecloud-sdk-python`](https://github.com/Hyze-Cloud/hyzecloud-sdk-python) | SDK oficial Python — cliente sync e async |
| [`hyzecloud-docs`](https://github.com/Hyze-Cloud/hyzecloud-docs) | Documentação — referência da API, guias e SDKs |

---

### Comece em minutos

**SDK TypeScript / Node / Bun**

```bash
npm install @hyze-cloud/sdk
```

```ts
import { HyzeCloud } from "@hyze-cloud/sdk";

const hyze = new HyzeCloud({
  apiKey: process.env.HYZE_API_KEY,
});

const { apps } = await hyze.apps.list();
```

**SDK Python**

```bash
pip install hyze-cloud
```

```python
from hyzecloud import HyzeCloud

client = HyzeCloud()  # lê HYZE_API_KEY

apps = client.apps.list()["apps"]
```

**CLI**

```bash
npm install -g @hyze-cloud/cli
hyze login
```

Mais detalhes na [documentação](https://docs.hyzecloud.app).

---

<div align="center">
  <sub>Build fast. Ship clean.</sub>
</div>
