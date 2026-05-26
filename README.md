# King Marketplace

Marketplace oficial del ecosistema **King Framework** para Claude Code.

## Instalación

### Opción 1 — Vía marketplace (recomendado)

```
/plugin marketplace add InformatiK-AI/king-marketplace
/plugin install king-core@king-marketplace
/plugin install king-framework@king-marketplace
```

Para instalar plugins satélite (requieren king-framework instalado primero):

```
/plugin install king-entrepreneur@king-marketplace
```

### Opción 2 — One-liner (macOS/Linux)

```bash
curl -sSL https://raw.githubusercontent.com/InformatiK-AI/king-framework/main/scripts/remote-install.sh | bash
```

### Opción 3 — One-liner (Windows PowerShell)

```powershell
irm https://raw.githubusercontent.com/InformatiK-AI/king-framework/main/scripts/remote-install.ps1 | iex
```

---

## Plugins disponibles

| Plugin | Descripción | Requiere |
|--------|-------------|----------|
| `king-core` | SDLC completo · 47 skills · 10 agentes · genesis, brainstorm, plan, build, review, qa, merge, release y pipeline SDD | — |
| `king-framework` | Protocolos RADAR/CASTLE/SDD/Chronicle · 10 agentes · 36 skills | — |
| `king-entrepreneur` | Ruta completa para fundar y lanzar un SaaS · /validate-idea · /mvp-accelerator · 8 skills | `king-framework` |

---

## Después de instalar

En tu proyecto, ejecuta:

```
/genesis
```

Genera la infraestructura adaptada a tu stack: CLAUDE.md, agentes, índice de skills y conocimiento específico.

---

## Más información

- king-core: [InformatiK-AI/king-core](https://github.com/InformatiK-AI/king-core)
- king-framework: [InformatiK-AI/king-framework](https://github.com/InformatiK-AI/king-framework)
- king-entrepreneur: [InformatiK-AI/king-entrepreneur](https://github.com/InformatiK-AI/king-entrepreneur)
- Autor: InformatiK-AI · j.salgado2k@gmail.com