# 🥖 Guilherme Padeiro

> Landing page institucional para uma padaria artesanal, desenvolvida
> com **HTML5 semântico** e **CSS3**, com foco em acessibilidade,
> responsividade, hierarquia visual e boas práticas de desenvolvimento
> front-end.

------------------------------------------------------------------------

## ✨ Sobre o projeto

O **Guilherme Padeiro** é uma landing page criada para apresentar uma
marca de panificação artesanal de forma simples, elegante e responsiva.

O projeto foi desenvolvido como uma aplicação **estática**, sem
JavaScript e sem frameworks, priorizando uma estrutura HTML organizada e
estilos CSS reutilizáveis.

### 🎯 Objetivos

-   Criar uma presença digital para uma marca de panificação artesanal.
-   Aplicar **HTML5 semântico**.
-   Desenvolver uma interface **responsiva**.
-   Trabalhar hierarquia tipográfica e espaçamento.
-   Utilizar **CSS Custom Properties** para centralizar tokens visuais.
-   Aplicar princípios básicos de **acessibilidade**.
-   Manter uma estrutura simples e fácil de compreender e evoluir.

------------------------------------------------------------------------

## 🛠️ Tecnologias

  Tecnologia            Utilização
  --------------------- --------------------------------------------
  🧱 **HTML5**          Estrutura semântica e acessível
  🎨 **CSS3**           Layout, responsividade e identidade visual
  🔤 **Google Fonts**   Tipografia
  🖼️ **Unsplash**       Imagens utilizadas na composição visual
  🧩 **SVG**            Ícones e identidade visual

### 🚫 Sem JavaScript

O projeto foi propositalmente desenvolvido **sem JavaScript**,
frameworks ou bibliotecas de interface.

Isso mantém a aplicação leve e permite concentrar o exercício em **HTML
semântico + CSS responsivo**.

------------------------------------------------------------------------

## 📁 Estrutura do projeto

``` text
poc_guilherme_padeiro/
│
├── 📄 index.html
├── 📁 css/
│   └── 🎨 style.css
│
└── 📁 images/
    ├── 🖼️ logo-guilherme-padeiro.svg
    └── 📁 icons/
        ├── instagram.svg
        ├── facebook.svg
        ├── email.svg
        └── whatsapp.svg
```

> As imagens fotográficas utilizadas no layout são carregadas por URL
> diretamente no HTML.

------------------------------------------------------------------------

## 🧭 Estrutura da página

A página está organizada em seções semânticas:

``` text
<header>
   └── <nav>

<main>
   ├── Hero
   ├── Nossa história
   ├── Produtos
   ├── Galeria
   └── Contato

<footer>
   └── Canais de contato
```

### 🏠 Header

Apresenta a identidade da marca e a navegação principal.

### 🥐 Hero

Área de destaque da página com a mensagem principal da marca e chamada
para ação.

### 📖 Nossa história

Apresenta a proposta artesanal da marca e um destaque visual relacionado
à produção de pães.

### 🍞 Produtos

Exibe os principais produtos em cards responsivos.

### 📸 Galeria

Apresenta imagens relacionadas ao universo da panificação.

### 📬 Contato

Reúne informações de contato e uma imagem relacionada ao processo
artesanal.

### 🔗 Footer

Apresenta os canais de contato e as informações de desenvolvimento do
projeto.

------------------------------------------------------------------------

## 📱 Responsividade

O layout utiliza uma abordagem **mobile-first**, adaptando a interface
para diferentes larguras de viewport.

### Breakpoints

  Dispositivo   Regra
  ------------- --------------------
  📱 Mobile     Estilos base
  📲 Tablet     `min-width: 48rem`
  🖥️ Desktop    `min-width: 75rem`

Na versão desktop, alguns elementos recebem ajustes específicos de
composição, como:

-   Grid do hero.
-   Posicionamento da área de destaque da seção "Nossa história".
-   Dimensões das imagens.
-   Tipografia dos títulos.
-   Organização dos cards.
-   Layout da galeria.
-   Posicionamento da seção de contato.

------------------------------------------------------------------------

## 🎨 Identidade visual

As principais cores são centralizadas em **CSS Custom Properties**,
facilitando manutenção e futuras alterações.

``` css
:root {
  --color-background: #fffaf0;
  --color-surface: #ffffff;
  --color-surface-soft: #fff2c7;
  --color-primary: #f4c542;
  --color-primary-dark: #c79500;
  --color-accent: #e9a800;
  --color-heading: #241b10;
  --color-text: #4d4032;
  --color-muted: #766957;
  --color-border: #eadfc7;
  --color-footer: #2b2118;
  --color-white: #ffffff;
}
```

### 🔤 Tipografia

O projeto utiliza duas famílias tipográficas:

-   **Playfair Display** → títulos e destaques.
-   **DM Sans** → textos, navegação e elementos de interface.

A combinação busca equilibrar uma aparência **artesanal e sofisticada**
com boa legibilidade.

------------------------------------------------------------------------

## ♿ Acessibilidade

Foram aplicadas práticas básicas de acessibilidade, incluindo:

-   Uso de **elementos HTML semânticos**.
-   `alt` nas imagens.
-   `aria-label` quando necessário.
-   Estrutura de navegação identificável.
-   Hierarquia de títulos.
-   Contraste entre texto e fundo.
-   Estados de `:hover` e `:focus-within`.
-   Links e elementos interativos visualmente identificáveis.

A intenção é que a estrutura tenha significado tanto para usuários
quanto para tecnologias assistivas.

------------------------------------------------------------------------

## 🧩 Boas práticas aplicadas

### HTML

-   Estrutura semântica.
-   Separação entre conteúdo e apresentação.
-   Imagens com textos alternativos.
-   Hierarquia consistente de headings.
-   Navegação estruturada.

### CSS

-   Abordagem **mobile-first**.
-   Variáveis CSS para tokens visuais.
-   Layout utilizando **CSS Grid** e **Flexbox**.
-   Media queries para adaptação responsiva.
-   Unidades relativas como `rem`.
-   Componentes visuais reutilizáveis.
-   Estados de interação com `:hover` e `:focus-within`.

------------------------------------------------------------------------

## 🚀 Como executar

Como o projeto é estático, não é necessário instalar dependências.

### 1. Clone ou baixe o projeto

``` bash
git clone <URL_DO_REPOSITORIO>
```

### 2. Entre na pasta

``` bash
cd poc_guilherme_padeiro
```

### 3. Abra o projeto

Abra o arquivo:

``` text
index.html
```

Também é possível utilizar uma extensão como **Live Server** no VS Code
para executar a página localmente.

------------------------------------------------------------------------

## 🔍 Referência visual

O projeto foi desenvolvido tendo como referência visual uma landing page
de **e-learning responsiva** disponível no Behance, adaptando a
linguagem visual para o contexto de uma padaria artesanal.

🔗 [Referência no
Behance](https://www.behance.net/gallery/184359459/E-Learning-Responsive-Website-Landing-Page-Design)

------------------------------------------------------------------------

## 🧪 Checklist de qualidade

Antes de considerar uma alteração concluída, recomenda-se verificar:

-   [ ] Layout em mobile.
-   [ ] Layout em tablet.
-   [ ] Layout em desktop.
-   [ ] Navegação funcionando.
-   [ ] Links de contato.
-   [ ] Textos sem erros.
-   [ ] `alt` das imagens.
-   [ ] Contraste.
-   [ ] Estados de interação.
-   [ ] Consistência de espaçamento.
-   [ ] Ausência de overflow horizontal.
-   [ ] Organização do HTML.
-   [ ] Organização do CSS.

------------------------------------------------------------------------

## 👨‍💻 Desenvolvimento

**Guilherme Padeiro --- Landing Page**

Desenvolvido por **Romulo Rosa \| Front-End**.

------------------------------------------------------------------------

## 📄 Licença

Este projeto foi desenvolvido para fins de estudo, prática e
demonstração de conhecimentos em **desenvolvimento front-end**.
