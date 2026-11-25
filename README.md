# Clothing Store (ecommerce)

Site estático de uma loja de roupas femininas, feito com HTML, CSS e JavaScript puros. O projeto é um front-end de vitrine: não tem carrinho, login nem back-end.

## Captura de tela

<!-- Adicione aqui um print da página inicial. Exemplo: ![Página inicial](imagems/print-home.png) -->

## Tecnologias

- HTML5
- CSS3 (carrosséis animados feitos só com CSS)
- JavaScript (o arquivo `js/srcipt.js` existe, mas ainda está vazio)

## Páginas

| Arquivo | Descrição |
| --- | --- |
| `index.html` | Página inicial: banner, carrossel de marcas, seção "For Sale", carrossel de peças e rodapé com formulário de feedback |
| `produtos.html` | Página de produtos (por enquanto reaproveita o banner e o carrossel de marcas) |
| `quemSomos.html` | Página "Quem somos" (estrutura inicial) |
| `contato.html` | Página de contato (estrutura inicial) |

Todas as páginas têm o mesmo cabeçalho com menu de navegação e o mesmo rodapé.

## Estrutura de pastas

```
ecommerce/
├── index.html
├── produtos.html
├── quemSomos.html
├── contato.html
├── css/
│   └── style.css
├── js/
│   └── srcipt.js
└── imagems/      (logo, favicon, logos de marcas e fotos dos produtos)
```

## Como executar

Não precisa instalar nada.

1. Baixe ou clone o repositório:
   ```bash
   git clone https://github.com/Fernando3M/ecommerce.git
   ```
2. Abra o arquivo `index.html` no navegador (duplo clique), ou use a extensão Live Server do VS Code.

## Estado do projeto

Em desenvolvimento. O que já existe é o layout da vitrine. Ainda falta:

- Conteúdo próprio das páginas Produtos, Quem somos e Contato
- Lógica em JavaScript (o botão "Enviar feedback" ainda não envia nada)
- Carrinho e finalização de compra

## Autor

[Fernando3M](https://github.com/Fernando3M)
