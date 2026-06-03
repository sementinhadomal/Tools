# DeWalt Brushless Twin Kit — Landing Page

Página de produto e checkout para o **DeWalt Brushless Twin Kit**.

## Estrutura do Projeto

```
furadeira/
├── index.html          # Página principal do produto
├── checkout/
│   └── index.html      # Página de checkout (integrada com Whop)
├── css/                # Estilos globais e fontes
├── js/                 # Scripts da página principal
├── images/             # Imagens do produto
└── fonts/              # Fontes locais (Poppins, Roboto)
```

## Tecnologias

- HTML5 + CSS3 + JavaScript (Vanilla)
- Checkout embarcado via [Whop](https://whop.com) (`data-whop-checkout-plan-id`)

## Como rodar localmente

Para o checkout funcionar, a página precisa ser servida via HTTP (não `file://`):

```bash
npx http-server . -p 8080 --cors -o
```

Depois acesse: **http://localhost:8080**

## Deploy

Compatível com qualquer hospedagem estática:
- GitHub Pages
- Netlify
- Vercel
- Whop (hosting nativo)
