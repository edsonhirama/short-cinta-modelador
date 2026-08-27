# 📋 BRIEF TÉCNICO - ANTIGRAVITY
## Otimização LP Short Cinta Modelador para Cold Traffic (Google Ads)

**Data:** 27/08/2026  
**Prioridade:** 🔴 CRÍTICA  
**Prazo:** FASE 1 (48 horas) / FASE 2 (1-2 semanas)  
**Responsável:** Antigravity Team  

---

## 🎯 CONTEXTO

Tráfego atual: **Google Ads (YouTube in-stream + in-feed)**  
Modelo de vendas: **Cash on Delivery (COD)**  
Problema: LP otimizada para warm traffic, NÃO para cold traffic  
Resultado: Taxa de conversão baixa (1-3%) com alto bounce rate (50-70%)

**Solução:** Reposicionar hero section + adicionar trust signals + clarificar objeções

---

## 🔴 FASE 1 - URGENTE (48 HORAS)

### 1. REESCREVER HERO SECTION (SEÇÃO TOPO)

**O que mudar:**
- **Antes:** "Valorize sua silhueta e invista se mais"
- **Depois:** Título claro em 2-3 linhas explicando O QUÊ é o produto

**Novo conteúdo do hero:**

```
LINHA 1: "Short Cinta Modelador"
LINHA 2: "Silhueta Definida em 30 Segundos"
SUBTÍTULO: "Confortável • Invisível • Durável"

BENEFÍCIOS LINHA (abaixo): ✓ Frete Grátis | ✓ Pague na Entrega
```

**Especificações técnicas:**
- H1 deve ser: "Short Cinta Modelador"
- H2 deve ser: "Silhueta Definida em 30 Segundos"
- Font-size do H1: Clamp(30px, 5vw, 52px)
- Font-size do H2: Clamp(20px, 3.5vw, 32px)
- Color H1: #45102E (plum-dark)
- Color H2: #A43E63 (rose-deep)
- Alinhamento: Center

**O que REMOVER:**
- Tire a palavra "certificado de renda" (confunde)
- Tire textos vagos tipo "invista se mais"

---

### 2. ADICIONAR VÍDEO NO HERO

**Onde:** Lado direito do hero (ou logo abaixo do título, em mobile)

**Requisitos:**
- Duração: 10 segundos (máximo)
- Formato: MP4 ou WebP
- Conteúdo: 
  - Primeiros 3s: Mulher colocando o short (close up)
  - Segundos 4-8: Resultado moldado do corpo
  - Últimos 2s: Produto em pé, confiante
- Legenda em cima do vídeo: "Resultado instantâneo | Confortável o dia todo"
- Auto-play: SIM (mudo)
- Loop: SIM
- Controls: NÃO (sem play/pause visível)

**Especificações:**
- Video container max-width: 500px
- Aspect ratio: 16:9
- Border-radius: 12px
- Box-shadow: 0 8px 24px rgba(69, 16, 46, 0.2)

**Texto na legenda:**
- Font-size: 14px
- Font-weight: 600
- Color: white com text-shadow para legibilidade
- Position: Bottom center do vídeo
- Padding: 16px

---

### 3. ADICIONAR TRUST BADGES (Logo abaixo do hero)

**Localização:** Imediatamente após o hero section, ANTES de qualquer outro conteúdo

**Estrutura:** 4 badges em linha (ou 2x2 em mobile)

```
┌─────────────────────────────────────────┐
│ ⭐ 4.8 de 5 Estrelas    ✅ 15.000+ Clientes │
│                                           │
│ 📦 Frete Grátis Brasil   💯 Devolva Grátis │
└─────────────────────────────────────────┘
```

**Especificações por badge:**

**Badge 1: Avaliações**
- Texto: "⭐ 4.8 de 5 Estrelas"
- Subtexto: "(2.341 avaliações)"
- Background: rgba(31, 122, 77, 0.1) - Verde suave
- Text-color: #1F7A4D (green)
- Font-size: 13px bold
- Padding: 12px 24px

**Badge 2: Clientes**
- Texto: "✅ 15.000+ Clientes"
- Subtexto: "Satisfeitos"
- Background: rgba(194, 90, 120, 0.1) - Rosa suave
- Text-color: #C25A78 (rose)
- Font-size: 13px bold
- Padding: 12px 24px

**Badge 3: Frete**
- Texto: "📦 Frete Grátis"
- Subtexto: "Brasil todo"
- Background: rgba(201, 162, 39, 0.1) - Ouro suave
- Text-color: #C9A227 (gold)
- Font-size: 13px bold
- Padding: 12px 24px

**Badge 4: Devolução**
- Texto: "💯 Devolva Grátis"
- Subtexto: "7 dias de garantia"
- Background: rgba(31, 122, 77, 0.1) - Verde suave
- Text-color: #1F7A4D (green)
- Font-size: 13px bold
- Padding: 12px 24px

**Container styling:**
- Display: Grid 2x2 (desktop) / Stack (mobile)
- Gap: 16px
- Max-width: 600px
- Margin: 32px auto
- Border-radius: 16px cada badge
- Transition on hover: slight scale (1.02)

---

### 4. ADICIONAR SEÇÃO "OBJEÇÕES RESPONDIDAS"

**Localização:** Logo após os trust badges (ANTES de qualquer vídeo ou testimonial)

**Estrutura:** Uma seção em caixa única com 4 quadrantes

```
┌──────────────────────────────────────────────┐
│                                              │
│  ✓ 4 TAMANHOS       │  ✓ MATERIAL            │
│  P • M • G • GG     │  Lycra 80% + Poliamida │
│                     │  Hipoalergênico        │
├─────────────────────┼────────────────────────┤
│  ✓ GARANTIA         │  ✓ FRETE               │
│  7 dias            │  Grátis Brasil         │
│  Reembolso 100%    │  Entrega 3-5 dias     │
│                     │                        │
└──────────────────────────────────────────────┘
```

**Especificações:**

**Container geral:**
- Background: #FBF6F0 (cream)
- Border: 2px solid #C25A78 (rose)
- Border-radius: 16px
- Padding: 32px
- Max-width: 700px
- Margin: 32px auto
- Grid: 2x2 (desktop) / 1x4 (mobile)
- Gap: 24px

**Cada quadrante:**
- Background: white
- Border: none
- Border-radius: 12px
- Padding: 20px
- Text-align: center
- Box-shadow: 0 2px 8px rgba(0,0,0,0.05)

**Typography:**
- Título (✓ + texto grande):
  - Font-size: 14px bold
  - Font-weight: 700
  - Color: #45102E (plum-dark)
  - Letter-spacing: 1px
  - Text-transform: uppercase

- Subtítulo (descrição):
  - Font-size: 13px
  - Color: #7A5F6B (muted)
  - Line-height: 1.6
  - Margin-top: 8px

---

### 5. REPOSICIONAR CTA PRINCIPAL

**Localização:** Logo após a seção "Objeções Respondidas"

**Texto do botão:**
- **Antes:** "Escolher kit"
- **Depois:** "Sim, Quero Testar - Pago na Entrega"

**Especificações do botão:**
- Background: linear-gradient(135deg, #E3C25A 0%, #C9A227 100%) - Ouro
- Text-color: #6B4E00 (dark para contraste)
- Font-size: 18px bold
- Font-weight: 800
- Letter-spacing: 0.5px
- Padding: 20px 40px
- Border-radius: 999px
- Box-shadow: 0 12px 30px rgba(201, 162, 39, 0.4)
- Hover: Transform translateY(-2px), shadow aumenta
- Text-transform: uppercase

**Adicionar abaixo do botão (sub-text):**
- Texto: "Entrega em 3 dias | Devolva grátis em 7 dias"
- Font-size: 12px
- Color: #7A5F6B (muted)
- Font-weight: 600
- Margin-top: 12px

---

### 6. REMOVER OU SEPARAR "PULSEMINHAS ENÉRGICA"

**Ação:** 
- REMOVER completamente da página principal
- OU colocar em página separada/modal (NÃO no flow principal)

**Motivo:** Cria confusão sobre qual é o produto principal. Cold traffic precisa 100% de foco no Short Cinta.

---

## 🟡 FASE 2 - IMPORTANTE (1-2 SEMANAS)

### 7. REFAZER ESTRUTURA DE PREÇO

**Localização:** Seção "Escolha seu kit" (manter posição, mas redesenhar)

**Novo layout:** 3 cards lado a lado (desktop) / Stack (mobile)

```
┌─────────────────┐  ┌──────────────────┐  ┌──────────────────┐
│ KIT SIMPLES      │  │ KIT POPULAR ⭐   │  │ KIT ECONÔMICO    │
│                 │  │ (Mais Vendido)   │  │                  │
│ 1 Short         │  │                  │  │ 3 Shorts         │
│ R$ 119,90       │  │ 2 Shorts         │  │ R$ 229,90        │
│                 │  │ R$ 159,90        │  │                  │
│ Escolha 1 cor   │  │ Escolha 2 cores  │  │ Escolha 3 cores  │
│ Escolha tamanho │  │ Escolha tamanho  │  │ Escolha tamanho  │
│                 │  │                  │  │                  │
│ [ESCOLHER]      │  │ ✓ Economize      │  │ ✓ Economize      │
│                 │  │   R$ 79,80       │  │   R$ 130,80      │
│                 │  │                  │  │                  │
│                 │  │ [ESCOLHER AGORA] │  │ [ESCOLHER]       │
│                 │  │ (destaque ouro)  │  │                  │
└─────────────────┘  └──────────────────┘  └──────────────────┘
```

**Especificações:**

**Card container:**
- Width: calc((100% - 32px) / 3) desktop / 100% mobile
- Background: white
- Border: 2px solid #E8CF8A (gold-light)
- Border-radius: 16px
- Padding: 24px
- Box-shadow: 0 4px 12px rgba(201, 162, 39, 0.15)
- Gap: 16px entre cards

**Card "Popular" (meio):**
- Border-color: #C9A227 (gold darker)
- Border-width: 3px
- Transform: scale(1.05) desktop
- Box-shadow: 0 8px 24px rgba(201, 162, 39, 0.3)

**Badge "Mais Vendido":**
- Position: Top center (absolute, -12px)
- Background: #C9A227 (gold)
- Color: white
- Font-size: 12px bold
- Padding: 6px 16px
- Border-radius: 20px
- Text: "⭐ MAIS VENDIDO"

**Typography dentro dos cards:**
- Título kit: 16px bold, color #45102E
- Preço: 32px bold, color #C9A227, line-height tight
- Descrição: 12px, color #7A5F6B
- Economia: 13px bold, color #1F7A4D (green), margin-top 12px

**Button em card Popular:**
- Background: gold
- Text: "ESCOLHER AGORA"
- Font: 14px bold

---

### 8. CRIAR SEÇÃO "COMO FUNCIONA"

**Localização:** Após os kits de preço

**Estrutura:** 3 passos visuais

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│       01        │    │       02        │    │       03        │
│                 │    │                 │    │                 │
│  Colocar o      │ → │   Moldagem      │ → │  Confortável    │
│   Short         │    │   Instantânea   │    │   o Dia Todo   │
│                 │    │                 │    │                 │
│  [IMAGEM/ICON]  │    │  [IMAGEM/ICON]  │    │  [IMAGEM/ICON]  │
└─────────────────┘    └─────────────────┘    └─────────────────┘
```

**Especificações:**
- 3 cards lado a lado (desktop) / stack (mobile)
- Cada card: 200px width desktop
- Gap: 20px
- Setas entre cards: →
- Numeração: 01, 02, 03 em 48px bold, color #C25A78

**Por card:**
- Background: #FBF6F0 (cream)
- Border-radius: 12px
- Padding: 24px
- Text-align: center

**Descrição:**
- Título: 14px bold, color #45102E
- Texto: 12px, color #7A5F6B

---

### 9. MOVER TESTIMONIAIS PARA TOPO

**Localização:** Logo após a seção "Como Funciona" (antes do vídeo)

**Novo layout:** 3-4 cards com FOTOS REAIS

```
┌─────────────────────┐  ┌─────────────────────┐
│  [FOTO CLIENTE]     │  │  [FOTO CLIENTE]     │
│                     │  │                     │
│  "Adorei! Resultado │  │  "Recomendo muito! │
│   imediato. Super   │  │   Vale cada real"   │
│   recomendo!"       │  │                     │
│                     │  │  ⭐⭐⭐⭐⭐          │
│  ⭐⭐⭐⭐⭐        │  │  Maria Silva        │
│  Ana Costa          │  │  Comprado em Jul   │
│  Comprado em Ago    │  │                     │
└─────────────────────┘  └─────────────────────┘

[Continuam mais 1-2 cards...]
```

**Especificações:**

**Card container:**
- Grid: 4 cards (desktop) / 1 card (mobile)
- Gap: 16px
- Max-width: 1000px
- Margin: 32px auto

**Cada card:**
- Width: calc(25% - 12px) desktop
- Background: white
- Border: 1px solid #E8CF8A (gold-light)
- Border-radius: 12px
- Padding: 16px
- Box-shadow: 0 2px 8px rgba(0,0,0,0.05)

**Foto cliente:**
- Width: 100%
- Height: 140px
- Object-fit: cover
- Border-radius: 8px
- Margin-bottom: 12px

**Depoimento:**
- Font-size: 12px
- Line-height: 1.6
- Color: #3A2A33 (ink)
- Font-weight: 500
- Margin-bottom: 12px
- Font-style: italic

**Rating (estrelas):**
- Color: #C9A227 (gold)
- Font-size: 13px
- Margin-bottom: 8px

**Nome + data:**
- Font-size: 11px bold
- Color: #45102E (plum-dark)
- Margin-top: 8px

---

### 10. REESCREVER FAQ COMO "OBJEÇÕES"

**Remover perguntas genéricas tipo:**
- "Quantas unidades recebo?" (óbvio)
- "Quanto custa?" (já está no preço)

**Adicionar perguntas REAIS de quem chega frio:**

```
❓ "Funciona mesmo ou é só ilusão de óptica?"
✓ [Resposta explicando o mecanismo + resultado comprovado]

❓ "Sou XXL, vai vir no meu tamanho?"
✓ [Lista de tamanhos disponíveis]

❓ "Fica visível por baixo da roupa?"
✓ [Resposta sobre invisibilidade + material fino]

❓ "Posso usar todo dia sem machucar a pele?"
✓ [Material hipoalergênico + respirável]

❓ "Se não gostar, vocês realmente devolvem?"
✓ [Informação clara sobre devolução grátis em 7 dias + frete de retorno grátis]

❓ "Quanto tempo leva para chegar?"
✓ [3-5 dias úteis em qualquer lugar do Brasil]

❓ "Vocês enviam mesmo via COD?"
✓ [Confirmação que sim, paga na entrega, sem antecipação]
```

**Especificações:**
- Manter accordion (expandir/recolher)
- Questão em bold 13px
- Resposta em 12px, color #7A5F6B
- Background expandido: #FBF6F0 (cream)
- Padding: 16px

---

## 📱 ADAPTAÇÕES MOBILE

**Pontos críticos:**

1. **Hero video:** Em mobile, vídeo em full-width (100% container)
2. **Badges:** 2x2 grid em mobile, não 1x4
3. **Kits de preço:** Stack vertical, todos com mesmo tamanho (remover scale 1.05)
4. **Como funciona:** Stack vertical com setas viradas para baixo ↓
5. **Testimoniais:** 1 card por linha, carousel deslizável (ou stack)
6. **Sticky CTA:** Manter sticky CTA mobile que já existe (bom!)

---

## 🎨 CORES E ESTILOS (Referência)

Use as cores existentes do projeto:

```
--plum-dark: #45102E
--rose-deep: #A43E63
--gold: #C9A227
--gold-light: #E8CF8A
--cream: #FBF6F0
--green: #1F7A4D
--muted: #7A5F6B
--ink: #3A2A33
```

---

## 📊 MONITORAMENTO PÓS-IMPLEMENTAÇÃO

**Solicitar dados após deploy:**

1. **Conversion rate** (antes vs depois)
2. **Bounce rate** (antes vs depois)
3. **Scroll depth** (em qual seção as pessoas saem)
4. **Time on page** (tempo médio)
5. **Click-through rate no CTA hero** vs CTA abaixo

---

## ✅ CHECKLIST DE IMPLEMENTAÇÃO

- [ ] Hero section reescrito (título claro)
- [ ] Vídeo 10s adicionado e testado
- [ ] Trust badges criados e posicionados
- [ ] Seção "Objeções Respondidas" implementada
- [ ] CTA principal reenunciado ("Pago na Entrega")
- [ ] "Pulseminhas" removida/separada
- [ ] Mobile responsivo testado
- [ ] Links e botões testados
- [ ] Vídeo em autoplay (mudo)
- [ ] Deploy em staging/preview
- [ ] Cliente revisa
- [ ] Deploy em produção

---

## 📞 DÚVIDAS/AJUSTES

Se algo não ficar claro ou precisar de ajustes, use os 2 documentos de referência:
1. `ANALISE_LP_COLD_TRAFFIC.md` - Análise completa
2. `RESUMO_EXECUTIVO_COLD_TRAFFIC.md` - Resumo rápido

---

**Enviado por:** [Seu nome]  
**Para:** Antigravity Team  
**Prioridade:** 🔴 CRÍTICA - 48 HORAS PARA FASE 1
