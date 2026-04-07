# Design System: MyView "Obsidian Cinema"

## 1. Visão Geral
O MyView utiliza o sistema visual **Obsidian Cinema**, projetado para oferecer uma experiência de curadoria premium, imersiva e focada no conteúdo. A estética é inspirada no ambiente de salas de cinema escuras, utilizando tons profundos e acentos vibrantes.

---

## 2. Tokens de Cores (Paleta Obsidian)

### Cores de Fundo (Surface)
- **Deep Black:** `#0e0e0e` (Fundo principal, sólido)
- **Surface Dark:** `#131313` (Cards, seções e áreas de destaque secundário)
- **Glass Blur:** `rgba(14, 14, 14, 0.6)` com `backdrop-filter: blur(20px)` (Navegação e overlays)

### Cores de Acento (Primary & Brand)
- **Cinema Red:** `#E50914` (Cor principal da marca, logos e CTAs críticos)
- **Coral Glow:** `#ff8e80` (Acento suave, ícones ativos e hover)
- **Neon Purple:** `#bf81ff` (Indicadores de status 'Assistindo' e interações vibrantes)

### Cores de Texto (Typography)
- **High Contrast:** `#ffffff` (Títulos e textos importantes)
- **Medium Contrast:** `#adaaaa` (Sinopses, labels secundárias e estados inativos)
- **Low Contrast:** `#484847` (Bordas sutis e metadados menos importantes)

---

## 3. Tipografia (The Cinema Type)

### Fontes
- **Manrope (Primary):** Utilizada para títulos, logo e elementos de interface que precisam de impacto e modernidade.
- **Inter (Secondary):** Utilizada para corpo de texto, sinopses e metadados, focando em legibilidade máxima em tamanhos menores.

### Escala
- **Display Lg:** Manrope, 36pt, Bold, Tracking -2% (Títulos de filmes em destaque)
- **Headline:** Manrope, 24pt, Semi-Bold (Títulos de seções)
- **Body Regular:** Inter, 14pt, Regular, Line-height 1.6 (Sinopses e descrições)
- **Label Small:** Inter, 10pt, Medium, Uppercase, Tracking 10% (Tags e metadados)

---

## 4. Componentes Padronizados

### Cards de Título
- **Formato:** Vertical (Poster ratio ~2:3)
- **Bordas:** Arredondadas (Radius: 12px)
- **Interação:** Elevação e brilho suave no hover.

### Botões (CTAs)
- **Primary:** Background Cinema Red, Texto Branco, Rounded 8px.
- **Secondary:** Border Low Contrast, Background Transparente, Texto Medium Contrast.

### Filtros (Chips)
- **Estado Inativo:** Fundo Surface Dark, Texto Medium Contrast.
- **Estado Ativo:** Fundo Coral Glow, Texto Deep Black.

---

## 5. Regras de Layout
- **Grid:** 12 colunas (Desktop) / 4 colunas (Mobile).
- **Espaçamento (Gutter):** 24px entre posters.
- **Margens:** 64px (Desktop) / 20px (Mobile).
