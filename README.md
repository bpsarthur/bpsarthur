<div align="center">

<h1>Arthur Berti Petersen Scholze</h1>

<strong>Cibersegurança Ofensiva & Defensiva &nbsp;|&nbsp; Hardware Hacking RFID/NFC &nbsp;|&nbsp; AI-Powered Security</strong>

<br /><br />

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Top%202%25-red?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/bpsarthur)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthur-berti-petersen-scholze-ab32a12b2/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=microsoftoutlook&logoColor=white)](mailto:arthur.b.p.s@outlook.com.br)
[![Anthropic CVP](https://img.shields.io/badge/Anthropic-CVP%20Verified-6B48FF?style=for-the-badge&logo=anthropic&logoColor=white)](https://anthropic.com)

<img src="https://komarev.com/ghpvc/?username=bpsarthur&label=Profile%20views&color=0e75b6&style=plastic" alt="bpsarthur" />

</div>

---

## Sobre mim

Profissional de cibersegurança ofensiva e defensiva com base no **Sul do Brasil (RS — Ibirubá)**, atuando na **AUVP Capital**.

- Aprovado no **Cybersecurity Verification Program (CVP) da Anthropic** — um dos poucos profissionais verificados globalmente para uso dual-use com Claude (exploração de vulnerabilidades, payloads, ferramentas ofensivas)
- **Top 2%** no TryHackMe — ranking global em plataforma de hacking prático
- Palestrante na **UNICRUZ (Universidade de Cruz Alta)** — identificação e análise prática de falhas de segurança em ambientes reais
- Integro **IA via MCP** ao workflow diário de cibersegurança — não como experimento, mas como ferramenta de produção

---

## Reconhecimentos

| Conquista | Detalhe |
|---|---|
| **Anthropic CVP** | Cybersecurity Verification Program — profissional verificado para uso dual-use (exploração, payloads, ferramentas ofensivas) |
| **TryHackMe Top 2%** | Ranking global em plataforma de hacking prático |
| **Palestrante UNICRUZ** | Palestra sobre identificação e análise de falhas de segurança em ambientes reais |

---

## Stack & Áreas de Atuação

### Ofensiva
```
Pentest / Red Team  ·  Bug Bounty  ·  Análise de Vulnerabilidades
Burp Suite  ·  nuclei  ·  OWASP  ·  MITRE ATT&CK
Desenvolvimento de payloads e exploração
```

### Hardware Hacking / RFID & NFC
```
Proxmark3 (Iceman fork) — uso avançado para análise de cartões
MIFARE Classic — Fudan FM11RF08, magic Gen1a / Gen2 / CUID, backdoor key Quarkslab 2024
T5577  ·  EM410x  ·  HID Prox  ·  Indala  ·  AWID  ·  Hitag
EMV — Mastercard M/Chip Advance (CDA, ARQC online, AIP)
iClass  ·  PicoPass  ·  LEGIC Prime
```

### Blue Team / Defensiva
```
SIEM — desenho de arquitetura, integração com threat intel
Vulnerability scanning contínuo
Endpoint Security (EPM, MDM) — implementação e treinamento
IRP (Incident Response Plan)  ·  DRM (dark web, brand protection)
Compliance em contexto bancário
```

### Cloud & Infra
```
Azure — VNet, NSG, Key Vault, Bastion, Standard_D4s_v5
AWS   — VPC, Security Groups, Secrets Manager, SSM Session Manager, EC2 m5/m6i
Dimensionamento de infra, custos comparativos, Reserved Instances
Linux (Debian, hardening)  ·  Bash scripting
```

### Desenvolvimento
```
Python (FastMCP, automação, integração com ferramentas)
C (intermediário)              Lua (scripts Proxmark3)
Bash / scripting               JavaScript / Node.js
MCP (Model Context Protocol) — desenvolvimento de servers customizados
```

---

## Projetos em Destaque

### Proxmark3 MCP Server

> Wrapper Python que expõe **~56 comandos** do cliente Iceman como tools MCP.

- Cobre: LF, HF, MIFARE, EMV, T55xx, scripts Lua/Python
- Integração com Claude via **stdio JSON-RPC**
- Autodetect de device via `pm3.bat` no Windows + ProxSpace
- Permite rodar análises de cartão e emissão de comandos Proxmark diretamente no contexto de uma conversa com o Claude

---

### Plano de Implementação de Segurança Corporativo
Arquitetura em camadas documentada e implementada:
```
Endpoint Security (EPM/MDM)
  └── SIEM (threat intel integrado)
        └── Vulnerability scanning contínuo
              └── IRP (Incident Response Plan)
                    └── DRM (dark web + brand protection)
```

---

### Análise EMV com Proxmark3
Relatório técnico não-destrutivo de cartão Mastercard M/Chip Advance:
- CDA (Combined Dynamic Data Authentication)
- ARQC (online) com análise de Application Interchange Profile (AIP)
- Mapeamento completo de tags EMV sem alteração do cartão

---

### Sites Vulneráveis para Demo — Palestra UNICRUZ
Ambiente de demonstração ao vivo com falhas intencionais:
`SQLi` · `IDOR` · `XSS` · `MD5 sem salt` · `IDs sequenciais`

---

## IA em Cibersegurança

> IA em cibersec não é futuro — é ferramenta diária.

- **Anthropic CVP** — aprovado para uso dual-use (exploração, payloads, ferramentas ofensivas)
- Desenvolvimento de **MCP Servers** para integrar ferramentas de segurança com Claude
- Workflow diário com LLMs em análise ofensiva e defensiva
- Acredito que o diferencial não é usar IA, é saber o que pedir pra ela e validar o que ela entrega

---

## Contato

| Canal | Link |
|---|---|
| Email | [arthur.b.p.s@outlook.com.br](mailto:arthur.b.p.s@outlook.com.br) |
| LinkedIn | [Arthur Berti Petersen Scholze](https://www.linkedin.com/in/arthur-berti-petersen-scholze-ab32a12b2/) |
| TryHackMe | [bpsarthur](https://tryhackme.com/p/bpsarthur) |
| GitHub | [bpsarthur](https://github.com/bpsarthur) |

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=bpsarthur&show_icons=true&theme=dracula&locale=en" alt="GitHub Stats" />

<img src="https://github-readme-stats.vercel.app/api/top-langs?username=bpsarthur&show_icons=true&theme=dracula&locale=en&layout=compact" alt="Top Languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=bpsarthur&theme=dark" alt="Streak Stats" />

</div>
