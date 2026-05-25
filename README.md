# ECC Curated — Nakama Galih Agent Skills

Curated subset of [ECC](https://github.com/affaan-m/ECC) (191K⭐) — hanya skills yang relevan untuk 3 agent: **Franky**, **Luffy**, **Nami**.

## Struktur

```
skills/          — 55 curated skills (dari 232 original)
agents/          — agent definitions
rules/           — coding & security rules
scripts/         — utility scripts
package.json     — ECC universal package
```

## Skills per Agent

### 🔧 Franky (DevOps/Infra) — 25 skills
```
homelab-network-setup, homelab-pihole-dns, homelab-wireguard-vpn,
homelab-vlan-segmentation, homelab-network-readiness, uncloud,
docker-patterns, deployment-patterns, production-audit, canary-watch,
security-scan, security-review, github-ops, git-workflow, terminal-ops,
python-patterns, api-design, database-migrations, postgres-patterns,
redis-patterns, prompt-optimizer, token-budget-advisor, cost-tracking,
continuous-learning-v2, automation-audit-ops
```

### ₿ Luffy (Crypto/DeFi) — 12 skills
```
defi-amm-security, evm-token-decimals, llm-trading-agent-security,
nodejs-keccak256, agent-payment-x402, x-api, deep-research,
market-research, data-scraper-agent, autonomous-loops,
continuous-agent-loop, openclaw-persona-forge
```

### 📋 Nami (Assistant/Content) — 18 skills
```
article-writing, content-engine, seo, brand-voice, crosspost,
google-workspace-ops, email-ops, messages-ops, unified-notifications-ops,
research-ops, knowledge-ops, documentation-lookup, investor-materials,
remotion-video-creation, manim-video, vite-patterns, frontend-patterns,
dashboard-builder
```

## Cara Pakai

### Agent: "Pelajari skill X"
```bash
# Clone repo
git clone --depth 1 https://github.com/nandaroose/ECC.git /tmp/ecc-curated

# Copy skill yang relevan ke skills folder agent
cp -r /tmp/ecc-curated/skills/<skill-name> ~/.hermes/skills/
```

### Galih: "Tambah skill X ke Franky/Luffy/Nami"
Franky/Luffy/Nami akan:
1. Clone repo ini
2. Copy skill yang diminta ke `~/.hermes/skills/`
3. Skill otomatis terdeteksi di next session

## Sumber
- Original: [affaan-m/ECC](https://github.com/affaan-m/ECC) (MIT License)
- Curated: [nandaroose/ECC](https://github.com/nandaroose/ECC)
- Dipilih: 55 dari 232 skills (24%)
- Terakhir update: 2026-05-24
