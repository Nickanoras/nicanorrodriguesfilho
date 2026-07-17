# Nicanor Rodrigues Filho — Site Oficial

**Mentor de Carreira & Vida | Soberania de Carreira | #AEstratégia**

🔗 **URL:** https://nickanoras.github.io/nicanorrodriguesfilho/

---

## 📁 Estrutura de Arquivos

```
nicanorrodriguesfilho/
├── index.html          # Página principal (único arquivo HTML)
├── sitemap.xml         # Mapa do site para motores de busca
├── robots.txt          # Instruções para crawlers
└── README.md           # Este arquivo
```

---

## 🚀 Como Publicar no GitHub Pages

### 1. Faça upload dos arquivos

No seu repositório `nickanoras.github.io/nicanorrodriguesfilho/`, faça upload de:
- `index.html`
- `sitemap.xml`
- `robots.txt`

### 2. Configure o domínio personalizado (opcional)

Se quiser usar um domínio próprio (ex: `nicanorrodriguesfilho.com.br`):

1. Crie um arquivo `CNAME` na raiz do repositório com o conteúdo:
   ```
   www.nicanorrodriguesfilho.com.br
   ```
2. No painel do seu registrador de domínio, configure um registro CNAME:
   - **Nome:** `www`
   - **Valor:** `nickanoras.github.io`

### 3. Verifique se está online

Acesse: `https://nickanoras.github.io/nicanorrodriguesfilho/`

---

## 🔧 Configurações Pendentes

Antes de divulgar o site, complete estes ajustes:

### 1. Google Analytics 4

No arquivo `index.html`, localize:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
```

Substitua `GA_MEASUREMENT_ID` pelo seu ID real do GA4 (formato: `G-XXXXXXXXXX`).

**Como obter:**
1. Acesse [Google Analytics](https://analytics.google.com)
2. Crie uma propriedade → Tipo: Web
3. Copie o ID de medição (ex: `G-ABC123DEF4`)

### 2. Número de WhatsApp

Substitua todos os `5511999999999` pelo seu número real com DDD.

**Formato correto:** `5511987654321` (55 = Brasil, 11 = DDD, 987654321 = número)

### 3. Foto de Perfil

No hero, substitua a URL da imagem placeholder:
```html
<img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?w=400&h=500&fit=crop&crop=face" ...>
```

Por uma foto sua hospedada no WordPress ou no próprio GitHub.

### 4. Depoimentos

Os 3 depoimentos atuais são fictícios. Substitua por depoimentos reais dos seus clientes.

### 5. Lead Magnet (PDF)

O formulário de captura de e-mail atual exibe um `alert()`. Integre com:
- **Mailchimp** (gratuito até 500 contatos)
- **Brevo** (gratuito até 300 e-mails/dia)
- **Google Forms** (alternativa simples)

---

## 📊 Google Search Console

### 1. Verifique propriedade

1. Acesse [Google Search Console](https://search.google.com/search-console)
2. Adicione a propriedade: `https://nickanoras.github.io/nicanorrodriguesfilho/`
3. Escolha método de verificação: **Tag HTML** ou **Arquivo HTML**

### 2. Submeta o sitemap

1. No Search Console, vá em **Sitemaps**
2. Digite: `sitemap.xml`
3. Clique em **Enviar**

### 3. Solicite indexação

1. Vá em **URL Inspection**
2. Digite a URL completa
3. Clique em **Solicitar indexação**

---

## 🎨 Personalizações de Estilo

As cores e fontes são controladas por CSS variables no início do `<style>`:

```css
:root {
  --bg: #0a0a0a;           /* Fundo principal */
  --accent: #c9a96e;       /* Cor de destaque (dourado) */
  --text: #e8e4df;         /* Texto principal */
  --sans: 'Inter', ...;     /* Fonte sans-serif */
  --serif: 'Playfair Display', ...; /* Fonte serif (títulos) */
}
```

---

## 📱 Funcionalidades Incluídas

| Recurso | Descrição |
|---------|-----------|
| ✅ SEO Técnico | Meta tags, Schema.org, canonical, Open Graph |
| ✅ Responsivo | Desktop, tablet e mobile |
| ✅ Animações | Scroll reveal, timeline sequencial |
| ✅ WhatsApp Float | Botão flutuante com tooltip |
| ✅ FAQ Interativo | Acordeão com toggle |
| ✅ Formulário de Contato | Com validação e campos estratégicos |
| ✅ Lead Magnet | Captura de e-mails para lista |
| ✅ Depoimentos | Cards com prova social |
| ✅ Antes/Depois | Comparativo visual |
| ✅ Menu Mobile | Hambúrguer com animação |
| ✅ Google Analytics | Pronto para GA4 |
| ✅ Acessibilidade | ARIA labels, roles, contraste |

---

## 📝 Licença

© 2026 Nicanor Rodrigues Filho. Todos os direitos reservados.

CNPJ: 44.519.566/0001-08
