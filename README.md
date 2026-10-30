# 📚 AluraBooks

Página inicial de uma livraria online de tecnologia, inspirada no layout do **AluraBooks**. O projeto foi construído com **HTML e CSS puros**, seguindo a abordagem **mobile-first**, e usa a biblioteca **Swiper** para os carrosséis de livros.

![Status](https://img.shields.io/badge/status-conclu%C3%ADdo-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Swiper](https://img.shields.io/badge/Swiper-12-6332F6?logo=swiper&logoColor=white)

## 📖 Sobre o projeto

O AluraBooks é uma landing page de e-commerce de livros digitais. A página reúne as seções típicas de uma loja: cabeçalho com menu de categorias, busca, vitrines de livros, destaque de autora, tópicos recentes, newsletter e rodapé institucional.

## ✨ Funcionalidades

- **Cabeçalho responsivo** com menu hambúrguer no mobile (feito só com CSS, usando `checkbox` + `label`, sem JavaScript) e menu horizontal no desktop.
- **Banner de busca** com campo de pesquisa.
- **Carrossel "Últimos Lançamentos"** com paginação, acompanhado de um card de recomendação (*Angular 11 e Firebase*).
- **Carrossel "Mais vendidos"** com card de destaque da **Autora do Mês**.
- **Tópicos visitados recentemente** em formato de tags.
- **Newsletter** para cadastro de e-mail.
- **Rodapé "Grupo Alura"** organizado em Educação, Educação Online e Comunidade, com os logotipos em SVG.
- **Layout responsivo** com breakpoints em `1024px` (desktop) e `1728px` (telas grandes).

## 🛠️ Tecnologias

| Tecnologia | Uso |
| --- | --- |
| HTML5 | Estrutura semântica da página |
| CSS3 | Estilização, variáveis CSS (`:root`), Flexbox e media queries |
| [Swiper 12](https://swiperjs.com/) | Carrosséis (carregado via CDN) |
| [Google Fonts](https://fonts.google.com/) | Poppins, Josefin Sans, Inter, Krona One e Montserrat |
| SVG | Logos, ícones e capas dos livros |

## 📁 Estrutura de pastas

```
AluraBooks/
├── index.html          # Página principal
├── reset.css           # Reset de estilos do navegador
├── style.css           # Variáveis globais e imports dos demais CSS
├── img/                # Logos, ícones e capas em SVG
└── styles/
    ├── header.css      # Cabeçalho e menus
    ├── banner.css      # Banner com campo de busca
    ├── carrossel.css   # Carrosséis e cards
    ├── topicos.css     # Tópicos recentes
    ├── contato.css     # Newsletter
    └── footer.css      # Rodapé
```

## 🎨 Identidade visual

Paleta definida como variáveis CSS em `style.css`:

| Variável | Cor | Uso |
| --- | --- | --- |
| `--cor-background` | `#EBECEE` | Fundo da página |
| `--cor-branco` | `#FFFFFF` | Cards e títulos de seção |
| `--cor-laranja` | `#EB9B00` | Destaques e títulos |
| `--cor-azul-degrade` | `#002F52 → #326589` | Gradiente azul (banner e rodapé) |
| `--cor-preto` | `#000000` | Textos |
| `--cor-cinza` | `#474646` | Textos secundários |

## 🚀 Como executar

Não é necessário instalar nada. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/AluraBooks.git

# Entre na pasta
cd AluraBooks

# Abra o index.html no navegador (ou use a extensão Live Server do VS Code)
```

> ⚠️ É preciso ter conexão com a internet para carregar o Swiper e as fontes do Google, pois ambos são importados via CDN.

## 📱 Responsividade

O projeto parte do layout mobile e evolui para telas maiores:

- **Mobile:** menu hambúrguer, carrossel com cards empilhados.
- **≥ 1024px:** menu de categorias no cabeçalho e layout em colunas.
- **≥ 1728px:** ajustes para monitores grandes.

## 👤 Autor

Feito por **[Thomaz Laizo](https://github.com/ThomazLaizo)**.

---

> Projeto desenvolvido para fins de estudo. Logos, marcas e imagens pertencem ao Grupo Alura.