# Site Willian Castilho | IA Aplicada

> 🇧🇷 Site de página única da mentoria IA Aplicada do Willian Castilho.
> 🇺🇸 Single-page site for Willian Castilho's Applied AI mentoring.

[📋 Backlog / Board](https://github.com/users/williancastilho-iaaplicada/projects/5) · [🧠 Brainstorm](docs/brainstorm.md) · [📐 Requisitos / Requirements](docs/requisitos.md) · [🏗️ Arquitetura / Architecture](docs/arquitetura.md) · [📱 Como trabalhar / How we work](docs/como-trabalhar.md)

---

## 🇧🇷 Português

### O que é
Site de página única da mentoria **IA Aplicada** do Willian Castilho, para publicar em **williancastilho.com.br** (Hostinger).

- Formatos apresentados, nesta ordem: mentoria para empresas, workshops, grupo reduzido (2 a 5 pessoas) e mentoria 1:1.
- Nenhum preço no site. Todos os botões levam ao WhatsApp (35) 99971-0419 com mensagem pronta por formato. Quem responde é o próprio Willian (sem atendimento automático).
- Identidade visual: `identidade_visual_willian_castilho.md` (azul #2563EB / #1E3A8A, fundo #F8FAFC, Plus Jakarta Sans + Inter + JetBrains Mono).
- Regra de conteúdo: o site não cita o nome da empresa onde o Willian trabalha, unidades, fornecedores, sistemas internos nem números reais.

### Status
O andamento em tempo real fica no **[Backlog do GitHub Projects](https://github.com/users/williancastilho-iaaplicada/projects/5)**:
- **Todo**: próximos passos
- **In Progress**: em andamento (com PR aberto quando estiver em revisão)
- **Done**: concluído

### Como rodar
#### Estrutura
```
index.html   página completa (HTML + CSS inline, sem dependências)
img/         fotos tratadas (sem metadados) e imagem de compartilhamento (og.jpg)
FOTOS.md     lista das fotos que ainda faltam
```

#### Seções escondidas
`#bastidores` (galeria) e `#depoimentos` estão com o atributo `hidden` até chegarem fotos de palestras/workshops e depoimentos autorizados. Para mostrar, basta remover `hidden`.

#### Publicar no Hostinger
Enviar `index.html` e a pasta `img/` para `public_html/` do domínio williancastilho.com.br (Gerenciador de Arquivos ou FTP). Ativar SSL no painel.

---

## 🇺🇸 English

### What it is
Single-page site for Willian Castilho's **Applied AI** mentoring, to be published at **williancastilho.com.br** (Hostinger).

- Offers, in order: company mentoring, workshops, small groups (2–5 people) and 1:1 mentoring.
- No prices on the site. Every button opens WhatsApp (+55 35 99971-0419) with a pre-filled message per offer. Willian answers personally (no bot).
- Visual identity: `identidade_visual_willian_castilho.md`.
- Content rule: the site never names Willian's current employer, its sites, suppliers, internal systems or real figures.

### Status
Real-time progress lives in the **[GitHub Projects backlog](https://github.com/users/williancastilho-iaaplicada/projects/5)**:
- **Todo**: next steps
- **In Progress**: being worked on (with an open PR when in review)
- **Done**: finished

### How to run
#### Structure
See the structure block in the Portuguese section above (`index.html`, `img/`, `FOTOS.md`).

#### Hidden sections
`#bastidores` (gallery) and `#depoimentos` (testimonials) carry the `hidden` attribute until action photos and authorized testimonials arrive. Remove `hidden` to show them.

#### Deploy to Hostinger
Upload `index.html` and the `img/` folder to the domain's `public_html/` (File Manager or FTP) and enable SSL.
