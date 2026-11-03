# Jornada Viagens

Landing page responsiva para uma agência de viagens, desenvolvida como projeto de estudo de HTML e CSS. A página apresenta ofertas, categorias de viagem, destinos populares e condições de pagamento, seguindo a referência visual do projeto.

## Seções da página

- **Apresentação:** imagem principal e texto sobre a agência.
- **Ofertas da semana:** cards de pacotes com destino, preço e link para detalhes.
- **Busca por categoria:** pacotes nacionais e internacionais, transfer e seguro viagem.
- **Destinos populares:** destaques para Tóquio e Osaka.
- **Condições de pagamento:** informações sobre parcelamento, cartão e Pix, acompanhadas por imagens temáticas.

## Tecnologias

- HTML5
- CSS3

O layout usa media queries para adaptar conteúdo e imagens a telas mobile, tablet e desktop. A galeria de pagamento utiliza arquivos de imagem próprios para cada faixa de tela.

## Como visualizar

Abra `index.html` em um navegador. Para uma experiência de desenvolvimento local, também é possível abrir a pasta do projeto com uma extensão de servidor local, como Live Server.

## Estrutura

```text
jornada-viagens/
├── css/
│   ├── categories.css
│   ├── destinations.css
│   ├── global.css
│   ├── header.css
│   ├── hero.css
│   ├── offers.css
│   ├── payments.css
│   └── style.css
├── fonts/
├── img/
├── index.html
└── README.md
```

## Responsividade

- **Mobile:** conteúdo em coluna e imagens de pagamento empilhadas.
- **Tablet:** galeria de pagamento em duas colunas, com a imagem de pessoas ocupando toda a largura.
- **Desktop:** texto de pagamento ao lado da galeria e imagens preparadas para telas maiores.

As imagens de destino, ofertas e demais elementos visuais ficam na pasta `img/`; a tipografia Montserrat fica em `fonts/`.
