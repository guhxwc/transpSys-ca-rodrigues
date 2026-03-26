# 🚛 TranspSys — C. A. Rodrigues dos Santos Transportes

Sistema completo de gestão de transportes, desenvolvido para **C. A. Rodrigues dos Santos Transportes Ltda** — Sarandi, PR.

![Status](https://img.shields.io/badge/status-ativo-brightgreen)
![Deploy](https://img.shields.io/badge/deploy-Vercel-black)
![HTML](https://img.shields.io/badge/HTML-100%25-orange)

---

## 📋 Funcionalidades

| Módulo | Descrição |
|--------|-----------|
| 👤 **Clientes** | Cadastro com busca automática por CNPJ/CPF via Receita Federal |
| 🧑‍✈️ **Motoristas** | Cadastro com validação de CNH (dígitos verificadores + vencimento) |
| 🚛 **Veículos** | Cavalo mecânico e carreta, com busca de marca/modelo via tabela FIPE |
| 🏢 **Proprietários** | Dados completos: ANTT/RNTRC, bancários e PIX |
| 📋 **Ordem de Coleta** | Geração de ordens com impressão e envio via WhatsApp |
| 📄 **CTRB** | Contrato de Transporte Rodoviário de Bens com preview e impressão A4 |

---

## 🔗 Integrações com APIs externas

- **BrasilAPI** — Consulta automática de CNPJ
- **ReceitaWS** — Fallback para consulta de CNPJ
- **ViaCEP** — Preenchimento automático de endereço por CEP
- **FIPE** — Busca de marcas e modelos de veículos
- **Google Maps** — Links de navegação nas ordens de coleta

---

## 🚀 Deploy

Este projeto é um **Single Page Application (SPA)** em HTML puro — sem dependências, sem build, sem servidor.

### Deploy na Vercel

1. Faça fork ou clone deste repositório
2. Acesse [vercel.com](https://vercel.com) e conecte sua conta GitHub
3. Clique em **"Add New Project"** → selecione este repositório
4. Clique em **"Deploy"** — zero configuração necessária ✅

### Deploy manual

Basta hospedar o arquivo `index.html` em qualquer servidor web estático.

---

## 💾 Armazenamento de dados

Os dados são salvos no **localStorage do navegador** — sem necessidade de servidor ou banco de dados. Isso significa:

- ✅ Funciona 100% offline após carregado
- ✅ Gratuito, sem custos de infraestrutura
- ⚠️ Dados ficam armazenados no dispositivo (não sincronizam entre computadores)

---

## 🏢 Dados da Empresa (fixos no sistema)

```
C. A. RODRIGUES DOS SANTOS TRANSPORTES LTDA
R. PRINCESA ISABEL, 599 — SARANDI - PR
CEP: 87113-030
CNPJ: 15.663.543/0001-66
IE: 046201406
```

---

## 🛠️ Tecnologias

- **HTML5 / CSS3 / JavaScript ES2022** — puro, sem frameworks
- **Google Fonts** — Syne, DM Sans, Barlow Condensed, IBM Plex Mono
- Compatível com Chrome, Firefox, Edge e Safari

---

## 📁 Estrutura do projeto

```
/
├── index.html          # Aplicação completa (single file)
├── vercel.json         # Configuração de deploy Vercel
└── README.md           # Este arquivo
```

---

## 📄 Licença

Uso exclusivo — C. A. Rodrigues dos Santos Transportes Ltda.
