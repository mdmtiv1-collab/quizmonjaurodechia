# 🥗 Quiz Funil - Protocolo Mounjaro de Chia

Funil de Quiz completo e de alta conversão, modelado e adaptado para o público e cultura do Brasil.

## 🚀 Estrutura do Repositório

```
├── 📄 index.html             # Quiz completo, responsivo e standalone (HTML + CSS + JS)
├── 📁 imagens/               # 21 imagens do funil (antes/depois, tipos de corpo, zonas corporais, etc.)
├── 📁 video/                 # Vídeo da VSL (vsl-mounjaro-de-chia.mp4 via Git LFS + thumbnail)
├── 📄 ROTEIRO_DO_QUIZ.md     # Copy detalhada de cada etapa, perguntas e gatilhos mentais
├── 📄 COMO_CONFIGURAR.md     # Guia rápido para trocar link de checkout, delay de botão e hospedar
└── 📄 ESTRUTURA-E-ROTEIRO.md # Mapeamento comparativo original vs adaptação brasileira
```

## 🇧🇷 Diferenciais da Tropicalização (Mercado Brasileiro)

1. **Linguagem & Tom de Voz:** Foco nos benefícios naturais sacietógenos da chia, com abordagem direta e empática.
2. **Gatilhos de Conversão Locais:**
   - Garantia Incondicional de 7 dias (Art. 49 do Código de Defesa do Consumidor);
   - Selos de segurança e aprovação instantânea via PIX e parcelamento no Cartão de Crédito;
   - Prova social realista ("38 pessoas respondendo agora").
3. **Imagens Dinâmicas por Gênero:** Imagens corporais alternam automaticamente entre modelos femininos e masculinos de acordo com a resposta do visitante.
4. **Preservação Automática de UTMs:** Repasse transparente de parâmetros de tráfego pago (`utm_source`, `utm_campaign`, `utm_content`, `utm_term`, `fbclid`, `src`, `sck`) direto para a página de checkout (Kiwify, Hotmart, PerfectPay, etc.).
5. **VSL com Delay Configurável:** O botão de compra surge automaticamente após o tempo estipulado do vídeo (configurável na constante `CONFIG` no final do `index.html`).

## ⚡ Como Rodar e Hospedar

- **Local:** Dê dois cliques no arquivo `index.html` no seu navegador.
- **Vercel / Cloudflare Pages / Netlify:** Conecte este repositório do GitHub e faça o deploy automático em 1 clique.
- **Hospedagem Tradicional (cPanel / Hostinger):** Suba os arquivos para a pasta `public_html`.
