# 🚀 Guia de Configuração e Uso do Quiz

O seu funil de quiz está pronto e localizado dentro da pasta:
`monjauro de chia` na sua **Área de Trabalho**.

---

## 📁 Arquivos da Estrutura:
1. `index.html` -> O quiz completo, responsivo e estilizado (pronto para rodar).
2. `ROTEIRO_DO_QUIZ.md` -> Toda a copy e perguntas detalhadas para referência ou para usar em Typeform/Quizell.
3. `COMO_CONFIGURAR.md` -> Este guia prático.

---

## ⚙️ Como Personalizar o Quiz em 2 Minutos

Abra o arquivo `index.html` em qualquer editor de texto (como Bloco de Notas ou VS Code) e localize o bloco de configuração no final da página (linha ~550):

```javascript
const CONFIG = {
  // 1. LINK DO SEU CHECKOUT (Kiwify, Hotmart, PerfectPay, Cakto, etc.):
  checkoutUrl: 'https://pay.kiwify.com.br/SEU_CHECKOUT_AQUI',

  // 2. TEMPO EM SEGUNDOS PARA O BOTÃO DE COMPRA APARECER:
  //    0   = Aparece IMEDIATAMENTE (ideal para você testar agora)
  //    840 = 14 minutos (padrão de VSL para tráfego pago)
  ctaDelaySeconds: 0,

  // 3. TEXTO E VALOR DO BOTÃO:
  ctaButtonText: 'QUERO MEU PLANO PERSONALIZADO · R$ 67,00 →',

  // 4. NÚMERO DE VISITANTES AO VIVO (PROVA SOCIAL):
  baseViewers: 38
};
```

---

## 🎯 Diferenciais Já Inclusos para o Mercado Brasileiro:
1. **Preservação Automática de UTMs:**
   Quando você rodar anúncios no Facebook/Instagram Ads ou TikTok Ads, todos os parâmetros como `utm_source`, `utm_campaign`, `utm_content`, `utm_term`, `src`, `sck` e `fbclid` serão automaticamente repassados para a URL do seu checkout na Kiwify/Hotmart, garantindo que suas vendas sejam rastreadas perfeitamente.
2. **Garantia de 7 Dias do CDC e Selos do PIX:**
   Aumenta drasticamente a taxa de cliques (CTR) e conversão para o público brasileiro.
3. **Imagens Dinâmicas por Gênero:**
   Se a pessoa escolher Mulher, todas as ilustrações corporais serão femininas. Se escolher Homem, serão masculinas.
4. **Player Panda Video Já Integrado:**
   O player já está configurado no formato mobile ideal (9:16 vertical), sem barras pretas laterais.

---

## 🌐 Como Colocar no Ar (Hospedagem Gratuita ou Própria):
* **Opção 1 (Mais fácil e grátis):** Crie uma conta na [Vercel](https://vercel.com) ou [Cloudflare Pages](https://pages.cloudflare.com) e basta arrastar a pasta `monjauro de chia` para lá. Em 30 segundos seu link estará funcionando.
* **Opção 2 (Hostinger / cPanel / Apache):** Basta fazer upload do arquivo `index.html` para a pasta `public_html` do seu domínio ou subdomínio.
* **Opção 3 (WordPress):** Você pode subir o arquivo via FTP ou criar uma página em branco e incorporar via iframe.
