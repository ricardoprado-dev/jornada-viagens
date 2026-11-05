# Jornada Viagens

Site responsivo de uma agência de viagens fictícia, desenvolvido como projeto de estudo de HTML e CSS durante o curso de Responsividade da Alura. O projeto apresenta a agência, ofertas e destinos, além de páginas de pacotes, blog e contato.

## Páginas

- **Início (`index.html`):** apresentação da agência, ofertas da semana, categorias de viagem, destinos populares, condições de pagamento e depoimentos.
- **Pacotes de viagem (`pacotes-de-viagens.html`):** página de um pacote para o Japão, com destinos da excursão, preço, condições de pagamento e depoimentos.
- **Blog (`blog.html`):** artigo sobre uma viagem a Tóquio e sugestões de outros destinos no Japão.
- **Contato (`contato.html`):** informações de contato e formulário com campos para nome, telefone, e-mail, assunto e mensagem.

O menu de navegação conecta as páginas HTML e mantém a navegação na mesma aba.

## Recursos e tecnologias

- HTML5, com elementos semânticos, navegação e conteúdo estruturado.
- CSS3, com estilos separados por página e seção.
- Layout responsivo com media queries e imagens adaptadas a diferentes tamanhos de tela.
- Fonte Montserrat incluída localmente no projeto.
- Imagens e ícones próprios para destinos, ofertas, depoimentos e conteúdo editorial.

O projeto é estático: não utiliza JavaScript, framework, dependências ou processo de build.

## Estrutura do projeto

```text
jornada-viagens/
├── blog.html
├── contato.html
├── index.html
├── pacotes-de-viagens.html
├── README.md
├── css/
│   ├── blog.css
│   ├── categories.css
│   ├── contact.css
│   ├── destinations.css
│   ├── footer.css
│   ├── global.css
│   ├── header.css
│   ├── hero.css
│   ├── offers.css
│   ├── payments.css
│   ├── style.css
│   ├── testimonials.css
│   └── travel-packages.css
├── fonts/
│   └── Montserrat-VariableFont_wght.ttf
└── img/
    ├── blog/
    │   ├── mobile-blog/
    │   ├── pc-blog/
    │   └── tablet-blog/
    ├── contato/
    └── travel-packages/
```

As pastas dentro de `img/` guardam imagens temáticas das páginas de blog, contato e pacotes. A pasta também contém imagens compartilhadas pelo site, como logotipos, ícones, fotos de destinos, ofertas e depoimentos.

### Organização dos estilos

- `style.css` reúne os arquivos CSS do projeto por meio de `@import`.
- `global.css` define a fonte, cores, elementos e estilos compartilhados.
- `header.css` e `footer.css` estilizam o cabeçalho, a navegação e o rodapé.
- `hero.css`, `offers.css`, `categories.css`, `destinations.css`, `payments.css` e `testimonials.css` estilizam seções da página inicial.
- `travel-packages.css`, `blog.css` e `contact.css` contêm estilos específicos das respectivas páginas.

## Como visualizar

1. Abra a pasta `jornada-viagens` no editor ou localize-a no computador.
2. Abra `index.html` em um navegador.

Para desenvolver e testar as páginas em um servidor local, abra a pasta no VS Code e use uma extensão como o Live Server. As demais páginas podem ser acessadas pelo menu do site ou diretamente pelos respectivos arquivos HTML.

## Responsividade

Os estilos usam media queries para adaptar a apresentação a telas mobile, tablet e desktop. Os principais pontos de ajuste utilizados são `768px`, `1024px` e `1440px`; alguns componentes também têm regras específicas para telas a partir de `1920px`. Elementos como banners e galerias utilizam imagens distintas para diferentes larguras quando necessário.

## Observações

- O formulário de contato é apenas a interface HTML: o projeto não possui serviço de envio ou armazenamento das mensagens.
- Alguns links de ofertas, categorias e redes sociais ainda são destinos demonstrativos (`#`) e podem ser conectados a páginas ou serviços reais posteriormente.
