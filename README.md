# Big Burger - Sistema PDV

Sistema de Ponto de Venda (PDV) completo para restaurantes e lanchonetes. Aplicacao web single-page, sem necessidade de backend ou banco de dados.

## Funcionalidades

- **Cardapio / PDV** - Catalogo de produtos com categorias, busca e carrinho de compras
- **Garcom / Mesas** - Gestao de mesas com PIN de acesso, lancamento de consumo e fechamento de conta
- **Cozinha (KDS)** - Kitchen Display System com temporizador e controle de status dos pedidos
- **Relatorio de Vendas** - Metricas de vendas, historico de pedidos e impressao de comprovantes
- **Configuracoes** - Dados do estabelecimento, cardapio dinamico e parametros do sistema

## Tecnologias

- HTML5 + CSS3 + JavaScript puro (sem dependencias externas)
- Google Fonts (Inter)
- Design dark mode responsivo
- Pronto para impressao termica ESC/POS (58mm / 80mm)

## Como usar localmente

Abra o arquivo `index.html` diretamente no navegador. Nao e necessario servidor.

## Deploy no Vercel

1. Faca fork ou clone este repositorio
2. Acesse [vercel.com](https://vercel.com) e conecte sua conta GitHub
3. Importe o repositorio
4. O Vercel detectara automaticamente como site estatico
5. Clique em **Deploy**

## Configuracoes padrao

| Parametro | Valor |
|-----------|-------|
| PIN do Garcom | `1234` |
| Taxa de Entrega | `R$ 5,00` |
| Numero de Mesas | `15` |
| Chave PIX | `bigburger@pix.com.br` |

> Altere as configuracoes pelo menu **Configuracoes** dentro do sistema.

## Licenca

MIT
