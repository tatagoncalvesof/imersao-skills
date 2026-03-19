# Especificacoes de Design — Carrossel Instagram

Referencia tecnica completa para design de carrosseis otimizados para Instagram.

---

## Dimensoes e Formatos

| Formato | Dimensao | Proporcao | Uso |
|---------|----------|-----------|-----|
| **Post Feed (padrao)** | 1080x1350px | 4:5 retrato | Carrossel padrao — RECOMENDADO |
| Feed Quadrado | 1080x1080px | 1:1 | Carrossel compacto |
| Story/Reels | 1080x1920px | 9:16 | Stories e Reels |
| Paisagem | 1080x608px | 16:9 | YouTube thumbs |
| Pinterest | 1080x1620px | 2:3 | Pinterest pins |

**Padrao para carrosseis: sempre usar 1080x1350px (4:5)** — ocupa mais espaco no feed, gera mais paradas de scroll.

### Resolucao e Exportacao
- Resolucao minima: 1080px de largura
- Formato de exportacao: PNG (qualidade maxima) ou JPG 95%+
- Tamanho maximo por imagem: 30MB (limite do Instagram)
- Maximo de slides: 20 (limite do Instagram, mas ideal e 5-10)

---

## Zonas do Slide

```
+------------------------------------------+
|           ZONA SEGURA (40px)              |
|  +------------------------------------+  |
|  |                                    |  |
|  |       AREA DE CONTEUDO             |  |
|  |       (1000 x 1270px util)         |  |
|  |                                    |  |
|  |                                    |  |
|  +------------------------------------+  |
|           ZONA SEGURA (40px)              |
+------------------------------------------+
        ^ 40px laterais tambem ^
```

- **Margem segura**: 40px em todos os lados (conteudo nunca encosta na borda)
- **Area do username**: Os primeiros ~100px do topo podem ser cobertos pelo header do Instagram no preview
- **Area inferior**: Os ultimos ~80px podem ser cortados por caption preview

---

## Tipografia

### Fontes Recomendadas (Google Fonts)

**Sans-serif (moderno, limpo):**
- **Poppins** — versatil, amigavel, perfeita para redes sociais
- **Inter** — clean, alta legibilidade, ideal para texto longo
- **Montserrat** — elegante, profissional
- **DM Sans** — geometrica, moderna
- **Space Grotesk** — tech, futurista
- **Raleway** — leve, sofisticada
- **Oswald** — condensada, impactante (otima para titulos)
- **Bebas Neue** — ultra bold, editorial

**Serif (classico, premium):**
- **Playfair Display** — luxo, editorial, beleza
- **Crimson Text** — elegante, literaria
- **Libre Baskerville** — classica, autoridade, advocacia

### Tamanhos de Fonte

| Elemento | Tamanho Minimo | Tamanho Ideal | Tamanho Maximo |
|----------|---------------|---------------|----------------|
| Titulo (Hook) | 48px | 56-64px | 80px |
| Titulo (Conteudo) | 36px | 40-48px | 56px |
| Subtitulo | 20px | 22-28px | 32px |
| Corpo/Paragrafo | 18px | 20-22px | 26px |
| Badge/Etiqueta | 14px | 16-18px | 22px |
| Numeracao | 48px | 56-72px | 96px |
| Dado estatistico | 64px | 72-96px | 120px |

### Regras de Tipografia
- **Maximo 2 fontes** por carrossel (titulo + corpo)
- **Hierarquia clara**: titulo > subtitulo > corpo (diferenca minima de 12px entre niveis)
- **Line-height titulo**: 1.1 a 1.2 (justo)
- **Line-height corpo**: 1.4 a 1.6 (confortavel)
- **Letter-spacing titulo**: 0 a -1px (levemente justo para impacto)
- **Peso do titulo**: Bold (700) ou Extra Bold (800)
- **Peso do corpo**: Regular (400) ou Medium (500)
- **NUNCA usar light (300) ou thin (100)** — nao tem legibilidade em mobile

---

## Cores e Paletas

### Paletas Prontas por Nicho

**Clean (Universal)**
- Texto: #FFFFFF | Overlay: #000000 | Destaque: #3B82F6 | Acento: #60A5FA

**Luxo (Premium)**
- Texto: #F5E6C8 | Overlay: #1A1A2E | Destaque: #D4AF37 | Acento: #FFD700

**Rosa Vibrante (Beleza/Feminino)**
- Texto: #FFFFFF | Overlay: #831843 | Destaque: #EC4899 | Acento: #F472B6

**Natureza (Saude/Bem-estar)**
- Texto: #ECFDF5 | Overlay: #064E3B | Destaque: #10B981 | Acento: #34D399

**Coral (Energia/Quente)**
- Texto: #FFFFFF | Overlay: #7C2D12 | Destaque: #F97316 | Acento: #FB923C

**Royal (Autoridade/Coach)**
- Texto: #EDE9FE | Overlay: #1E1B4B | Destaque: #8B5CF6 | Acento: #A78BFA

**Oceano (Corporativo/Tech)**
- Texto: #F0F9FF | Overlay: #0C4A6E | Destaque: #0EA5E9 | Acento: #38BDF8

**Fogo (Energia/Fitness)**
- Texto: #FEF2F2 | Overlay: #450A0A | Destaque: #EF4444 | Acento: #F87171

**Neutro (Minimalista/Advocacy)**
- Texto: #F3F4F6 | Overlay: #111827 | Destaque: #6B7280 | Acento: #9CA3AF

**Dourada (Elegancia)**
- Texto: #FFFFFF | Overlay: #1C1917 | Destaque: #D29007 | Acento: #FBBF24

**Menta (Frescor/Pet/Jovem)**
- Texto: #FFFFFF | Overlay: #134E4A | Destaque: #14B8A6 | Acento: #5EEAD4

**Ameixa (Feminino/Psico)**
- Texto: #FDF2F8 | Overlay: #581C87 | Destaque: #A855F7 | Acento: #C084FC

**Escuro Pro (Serio/Corporate)**
- Texto: #E5E7EB | Overlay: #000000 | Destaque: #FFFFFF | Acento: #D1D5DB

**Pastel (Suave/Infantil)**
- Texto: #374151 | Overlay: #FDF6E3 | Destaque: #F59E0B | Acento: #FBBF24

**Monocromo (Minimalista)**
- Texto: #FFFFFF | Overlay: #18181B | Destaque: #A1A1AA | Acento: #71717A

---

## Contraste e Acessibilidade

### Regras de Contraste
- **Minimo WCAG AA**: ratio 4.5:1 (texto normal sobre fundo)
- **Ideal WCAG AAA**: ratio 7:1
- **Texto sobre imagem**: SEMPRE usar overlay (gradiente ou solido) para garantir legibilidade
- **Texto sobre fundo claro**: usar texto escuro (#111827 ou mais escuro)
- **Texto sobre fundo escuro**: usar texto claro (#F3F4F6 ou mais claro)

### Overlay sobre Imagens
- **Overlay solido**: opacidade 0.3 a 0.5 (30-50%)
- **Overlay gradiente**: direcao de baixo para cima (to-top), opacidade 0.3 a 0.6
- **Cor do overlay**: preferencialmente preto (#000000) ou a cor dominante da paleta
- **NUNCA colocar texto sobre imagem sem overlay** — mesmo com sombra, a legibilidade e ruim

### Sombra de Texto
- **Cor**: preto ou cor escura da paleta
- **Blur**: 4-8px para legibilidade, 10-15px para efeito neon
- **Opacidade**: 0.3 a 0.7
- **Usar quando**: texto sobre imagem com overlay leve

---

## Layouts por Tipo de Slide

### Hook (Slide 1 — Capa)
- Texto centralizado (horizontal e vertical)
- Fonte titulo: 56-64px, bold
- Overlay: 0.35-0.45
- Swipe indicator: ATIVO
- Background: imagem forte ou gradiente impactante
- Badge: opcional (NOVO, GRATIS, etc.)

### Conteudo (Slides Intermediarios)
- Texto alinhado a esquerda, posicionado na parte inferior
- Fonte titulo: 40-48px, regular ou bold
- Overlay: 0.2-0.3
- Numeracao: se aplicavel, numero grande (56-72px) no canto superior
- Corpo de texto: se houver, 20-22px, regular

### CTA (Ultimo Slide)
- Texto centralizado
- Fonte titulo: 48-56px, bold
- Overlay: 0.4-0.5
- Badge: ATIVO (SALVE, SIGA, COMENTE, COMPARTILHE)
- Fundo: pode ser cor solida da paleta (sem imagem) para contraste

### Dados/Estatisticas
- Numero centralizado: 72-96px, bold
- Label abaixo: 20-24px, regular
- Fundo com overlay forte: 0.4-0.5
- Cor do numero: cor de destaque da paleta

### Quote/Frase
- Texto centralizado com aspas decorativas
- Fonte: serif (Playfair Display, Crimson Text)
- Tamanho: 36-44px
- Autor abaixo: 18-20px, italico

---

## Elementos Decorativos

### Swipe Indicator
- Posicao: parte inferior central do slide 1
- Icone: seta para a direita ou texto "Arraste >"
- Cor: branco com opacidade 0.7-0.8
- Tamanho: icone 24px ou texto 16px

### Badge/Etiqueta
- Posicao: canto superior direito (padrao) ou inferior direito
- Formato: retangulo com bordas arredondadas (8px)
- Fundo: cor de destaque da paleta
- Texto: branco, bold, 14-18px, uppercase
- Padding: 8px horizontal, 4px vertical
- Presets: NOVO, GRATIS, LIMITADO, EXCLUSIVO, VAGAS ABERTAS, OFERTA, -50%, HOT, VIP, ULTIMO DIA

### Divisor/Divider
- Tipo: linha horizontal
- Posicao: entre titulo e subtitulo
- Cor: branco ou cor de destaque
- Espessura: 2-3px
- Largura: 40-60px (curto, decorativo)

### Borda
- Uso: moldura ao redor do slide
- Espessura: 2-4px
- Cor: cor de destaque ou branco
- Border-radius: 0 (reto) ou 16px (arredondado)
- Margem interna: 8-12px

### Numeracao de Slides
- Posicao: canto superior esquerdo ou direito
- Formato: "01" ou "1/7"
- Cor: cor de destaque com opacidade 0.6
- Tamanho: 14-16px

---

## Backgrounds

### Gradientes Prontos
- **Escuro**: linear-gradient(135deg, #0f0f0f 0%, #1a1a2e 50%, #16213e 100%)
- **Quente**: linear-gradient(135deg, #f12711 0%, #f5af19 100%)
- **Oceano**: linear-gradient(135deg, #667eea 0%, #764ba2 100%)
- **Rosa**: linear-gradient(135deg, #f093fb 0%, #f5576c 100%)
- **Natureza**: linear-gradient(135deg, #11998e 0%, #38ef7d 100%)
- **Dourado**: linear-gradient(135deg, #D29007 0%, #FBBF24 50%, #D29007 100%)

### Cores Solidas
- Preto: #000000
- Branco: #FFFFFF
- Azul escuro: #0F172A
- Bege suave: #FDF6E3

### Regras para Background com Foto
- Usar imagem de alta qualidade (minimo 1080px)
- Aplicar overlay SEMPRE
- Preferir imagens com area "limpa" onde o texto vai ficar
- Evitar imagens muito detalhadas que competem com o texto
- Desfoque (blur) leve pode ajudar a legibilidade

---

## Layout Presets do Imperatriz dos Carroseis

Presets disponiveis no app para aplicacao direta:

### Minimalista
- Fonte: Inter, regular, 40px titulo / 20px subtitulo
- Texto: branco, inferior esquerdo
- Overlay: gradiente to-top, 0.2
- Sombra: blur 5px, opacidade 0.3

### Ousado
- Fonte: Poppins, bold, 64px titulo / 28px subtitulo
- Texto: branco, centralizado
- Overlay: solido, 0.4
- Sombra: blur 8px, opacidade 0.7
- Texto com fundo: opacidade 0.3

### Classico
- Fonte: Playfair Display, regular, 52px titulo / 22px subtitulo
- Texto: #F3F4F6, centralizado
- Overlay: gradiente to-top, 0.3
- Sombra: blur 2px, opacidade 0.6

### Magazine
- Fonte: Oswald, bold, 56px titulo / 18px subtitulo
- Texto: branco, superior esquerdo
- Overlay: solido, 0.15
- Divisor: ativo, branco

### Neon
- Fonte: Space Grotesk, bold, 48px titulo / 22px subtitulo
- Texto: #E0F2FE, inferior centralizado
- Overlay: gradiente to-top, 0.5 (#0F172A)
- Sombra neon: #38BDF8, blur 12px
- Borda: #38BDF8, 2px

### Elegante
- Fonte: Crimson Text, regular italico, 50px titulo / 20px subtitulo
- Texto: #FEF3C7, centralizado
- Overlay: gradiente to-top, 0.35 (#1C1917)
- Sombra dourada: #D4AF37, blur 6px
- Divisor: ativo, #D4AF37

---

## Checklist de Qualidade Visual

Antes de finalizar qualquer carrossel, verificar:

- [ ] Tamanho correto: 1080x1350px (4:5)
- [ ] Texto dentro da zona segura (40px das bordas)
- [ ] Contraste minimo 4.5:1 entre texto e fundo
- [ ] Hierarquia tipografica clara (titulo > subtitulo > corpo)
- [ ] Maximo 2 fontes diferentes
- [ ] Swipe indicator no slide 1
- [ ] CTA no ultimo slide
- [ ] Consistencia visual entre todos os slides (mesma paleta, fontes, estilo)
- [ ] Texto legivel em tela de celular (simular visualizacao mobile)
- [ ] Overlay aplicado onde ha texto sobre imagem
- [ ] Nenhum texto cortado nas bordas
- [ ] Badge visivel e legivel (se usado)
- [ ] Numeracao consistente (se usado formato numerado)
