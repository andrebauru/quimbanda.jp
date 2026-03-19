# 🔥 Quimbanda JP — Landing Page

> Site oficial da **Quimbanda JP**, casa de trabalhos espirituais autênticos no Japão.  
> One-page premium com design dark luxury, glassmorphism e animações GSAP.

[![Site](https://img.shields.io/badge/website-quimbanda.jp-C41E3A?style=flat-square&logo=google-chrome&logoColor=white)](https://quimbanda.jp)
[![Feito por](https://img.shields.io/badge/dev-andretsc.dev-D4AF37?style=flat-square&logo=github&logoColor=black)](https://andretsc.dev)
[![Licença](https://img.shields.io/badge/licença-MIT-brightgreen?style=flat-square)](LICENSE)

---

## ✨ Visão Geral

Landing page de alta conversão para serviços de Quimbanda no Japão. Design inspirado em tendências de UI Luxury 2025 combinando estética afro-brasileira com minimalismo japonês.

**Demo:** abra o arquivo `index.html` diretamente no browser — sem servidor necessário.

---

## 🗂️ Estrutura

```
quimbanda.jp/
└── index.html   ← tudo em um único arquivo (HTML + CSS + JS)
```

---

## 🛠️ Stack Técnica

| Tecnologia | Uso |
|---|---|
| **HTML5** | Arquivo único auto-contido |
| **Tailwind CSS** (CDN) | Estilização utilitária completa |
| **GSAP + ScrollTrigger** (CDN) | Animações de entrada e scroll |
| **Google Fonts** | Playfair Display + Plus Jakarta Sans |
| **Unsplash** | Imagens cinematográficas via CDN |

---

## 📐 Seções

| # | Seção | Descrição |
|---|---|---|
| 1 | **Header** | Menu fixo com glassmorphism e CTA WhatsApp |
| 2 | **Hero** | Full-viewport com parallax, headline GSAP e botão pulsante |
| 3 | **Marquee** | Faixa de autoridade com 8 diferenciais em loop |
| 4 | **Diferenciais** | Bento Grid assimétrico 3 colunas |
| 5 | **Serviços** | 10 serviços + CTA card com links WhatsApp individuais |
| 6 | **Sobre** | Split layout com badges flutuantes animados |
| 7 | **Depoimentos** | 6 cards de prova social |
| 8 | **CTA Final** | Seção com glow orbs e botão pulsante |
| 9 | **Footer** | Minimalista com links e contato |

---

## 🎨 Design System

| Token | Valor | Uso |
|---|---|---|
| `--ink` | `#050505` | Background principal |
| `--ink-2` | `#0a0a0a` | Background secundário |
| `--crimson` | `#C41E3A` | Cor primária (Exu) |
| `--gold` | `#D4AF37` | Cor de destaque (Axé) |
| `--cream` | `#F0EDE8` | Texto principal |
| **Display** | Playfair Display | Títulos dramáticos |
| **Body** | Plus Jakarta Sans | Texto corrido |

---

## ⚡ Animações GSAP

- **Hero entrance** — stagger de baixo para cima (tag → headline → sub → CTAs)
- **Parallax** — imagem do hero desliza suavemente no scroll
- **Scroll Reveal** — todas as seções surgem com `opacity + translateY`
- **Stagger** — cards de Bento, Serviços e Depoimentos animam em sequência
- **Hover** — transformações suaves em todos os cards e botões

---

## 📱 Responsividade

- ✅ Mobile (320px+)
- ✅ Tablet (768px+)
- ✅ Desktop (1280px+)
- Bento Grid colapsa para coluna única em mobile
- Menu hamburger com animação de ícone

---

## 💬 WhatsApp

Todos os CTAs apontam para `+81 70-9012-8822` com mensagens pré-preenchidas por serviço:

```
https://wa.me/817090128822?text=Mensagem+pré-preenchida
```

Botão flutuante fixo com animação `ping` sempre visível.

---

## 🚀 Deploy

Arquivo estático puro — compatível com qualquer hospedagem:

```bash
# Vercel (arrastar pasta)
# Netlify (arrastar pasta)
# GitHub Pages
# Qualquer servidor HTTP / CDN
```

---

## 📄 Licença

Copyright © 2026 **Quimbanda JP**. Todos os direitos reservados.  
Desenvolvido por [andretsc.dev](https://andretsc.dev).
