# NOPASTHO — A Casa do Churrasco

Landing page cinematográfica para a **NOPASTHO**, referência em churrasco em Jaú, SP.

## 🔥 Visão Geral

Projeto desenvolvido com foco em experiência digital premium, nível Awwwards/CSS Design Awards.

## ✨ Features

- **Loading cinematográfico** — Logo com partículas de brasa em canvas + light sweep GSAP
- **Smooth scroll** — Lenis com easing customizado, sincronizado com ScrollTrigger
- **SplitType** — Reveal de texto char a char com rotationX (-65°)
- **Scroll horizontal** — Seção de produtos com pin + horizontal scrub (desktop)
- **Galeria com lightbox** — Grid assimétrico 12 colunas + abertura com animação
- **Contador de stats** — Animação numérica com ScrollTrigger (onEnter once)
- **Barra de progresso** — Gradiente vermelho → ember → dourado
- **Canvas de embers** — Hero + CTA final com partículas de brasa
- **Cursor custom** — Dot + ring com mix-blend-mode difference
- **Botões magnéticos** — Efeito magnetic + elastic.out no mouseleave
- **Nav adaptativa** — Transparente → dark glass com backdrop-filter no scroll
- **Mobile premium** — Full-screen nav overlay, touch scroll, layout responsivo
- **Logo real** — PNG embedado via base64 com mix-blend-mode: screen
- **WhatsApp integrado** — CTAs diretos com mensagem pré-preenchida

## 🛠 Stack

| Tecnologia | Uso |
|---|---|
| HTML5 + CSS3 | Estrutura e design system completo |
| GSAP 3.12.5 + ScrollTrigger | Animações e scroll-driven |
| Lenis 1.0.42 | Smooth scroll premium |
| SplitType 0.3.4 | Text splitting para animações |
| Canvas API | Partículas de brasa (loader, hero, cta) |

## 🎨 Paleta de Cores

```
--bg:      #050505  Background principal
--red:     #D62027  Vermelho NOPASTHO
--ember:   #FF5A1F  Brasa/ember
--gold:    #B78A3D  Dourado queimado
--white:   #F2F2F0  Branco suave
--graphite:#1A1A1A  Grafite
```

## 📁 Estrutura

```
nopastho-landing/
├── index.html          # Landing page completa (arquivo único)
└── README.md
```

## 🚀 Deploy

### GitHub Pages
1. Vá em **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / pasta: **/ (root)**
4. Salvar — live em `https://arthurcunzolo.github.io/nopastho-landing`

### Substituições obrigatórias antes de publicar

| Item | Onde | Substituir por |
|---|---|---|
| `5514XXXXXXXXX` | Todos os links WhatsApp | Número real da loja |
| `@nopastho` | Seção Instagram | Handle real |
| Horários | Seção footer | Horários reais das lojas |

## 📍 Lojas

- **Loja 1:** Rua Rui Barbosa, 1369 — Jaú, SP
- **Loja 2:** Av. das Nações, 371 — Jaú, SP

---

Desenvolvido por [ArTech Solutions](https://github.com/ArthurCunzolo)

