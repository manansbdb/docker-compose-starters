<p align="center">
  <img src="docs/banner.svg" alt="docker-compose-starters banner" width="100%" />
</p>

<h1 align="center">docker-compose-starters</h1>

<p align="center">
  <strong>EN</strong> Ready-to-adapt Compose files for common stacks.<br/>
  <strong>PT</strong> Ficheiros Compose prontos a adaptar para stacks comuns.
</p>

<p align="center">
  <a href="https://github.com/manansbdb/docker-compose-starters/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/type-starter-a855f7?style=for-the-badge" alt="starter" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Ready-to-adapt Compose files for common stacks. | Ficheiros Compose prontos a adaptar para stacks comuns. |

```mermaid
flowchart LR
  A["📦 Clone"] --> B["⚙️ Configure"]
  B --> C["🚀 Use in project"]
  style A fill:#a855f7,stroke:#7e22ce,color:#fff
  style B fill:#0ea5e9,stroke:#0369a1,color:#fff
  style C fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone

```bash
git clone https://github.com/manansbdb/docker-compose-starters.git
cd docker-compose-starters
```

### Use / Usar

```bash
cd postgres-redis && docker compose up -d
```

### Requirements / Requisitos

- `git`
- No paid services required / Sem serviços pagos

---

## What's included / O que inclui

| Path | EN | PT |
|------|----|----|
| `postgres-redis/docker-compose.yml` | PostgreSQL + Redis | PostgreSQL + Redis |
| `nginx-app/docker-compose.yml` | Nginx reverse proxy + app | Nginx reverse proxy + app |

## Quick start / Início rápido

```bash
cd postgres-redis && docker compose up -d
```

**EN:** Copy env examples, set passwords, and never commit real secrets.

**PT:** Copia os exemplos de env, define passwords e nunca faças commit de segredos reais.

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

**Network / Rede:** BTC (Bech32).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
