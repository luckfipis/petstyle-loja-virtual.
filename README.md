# 🐾 Pet&Style — Loja Virtual

> Página inicial de uma loja fictícia especializada em produtos para pets com estilo. Projeto desenvolvido como exercício prático de **Tailwind CSS**, aplicando conceitos de layout responsivo, mobile-first, Flexbox e Grid.

---

## 📸 Visão Geral

A **Pet&Style** é uma loja virtual fictícia que oferece produtos como caminhas, brinquedos, coleiras e roupinhas para pets. O site foi construído com HTML puro e Tailwind CSS via CDN, sem necessidade de instalação ou build.

---

## 🗂️ Estrutura do Projeto

```
petstyle-loja-virtual/
├── index.html       # Arquivo principal da aplicação
└── README.md        # Documentação do projeto
```

---

## 📄 Seções da Página

| Seção | Descrição |
|---|---|
| **Header** | Logo, menu de navegação desktop e menu hambúrguer para mobile |
| **Hero** | Chamada principal, imagem de destaque, badges e indicadores |
| **Produtos** | 4 cards de produtos com imagem, descrição e preço |
| **Banner** | Faixa de destaque com frase institucional |
| **Depoimentos** | 3 avaliações de clientes fictícios com estrelas |
| **Contato** | Informações de contato e formulário com feedback de envio |
| **Footer** | Logo, créditos e links para redes sociais |

---

## 🛍️ Produtos Cadastrados

- **Caminha Veludo Chic** — R$ 189,90
- **Kit Brinquedos Fun** — R$ 79,90
- **Coleira Boho Luxe** — R$ 124,90
- **Casaco Winter Paws** — R$ 79,90 *(de R$ 99,90)*

---

## 🎨 Tecnologias Utilizadas

- **HTML5** — estrutura semântica da página
- **Tailwind CSS v3** — via CDN, para toda a estilização
- **Google Fonts** — Playfair Display (display) + DM Sans (corpo)
- **JavaScript vanilla** — menu mobile, smooth scroll e feedback do formulário
- **Unsplash** — imagens de pets gratuitas e de alta qualidade

---

## 📐 Conceitos de Tailwind Aplicados

### Mobile-First e Breakpoints
Todos os layouts partem da versão mobile e se adaptam com os prefixos `sm:`, `md:` e `lg:`:

```html
<div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
```

### Flexbox
Usado no header, hero e footer para alinhar elementos em linha:

```html
<div class="flex items-center justify-between h-16 md:h-20">
```

### Grid
Usado na seção de produtos e depoimentos:

```html
<div class="grid grid-cols-1 md:grid-cols-3 gap-6">
```

### Classes utilitárias aplicadas
`gap`, `justify-center`, `items-center`, `px-`, `py-`, `rounded-`, `shadow-`, `text-`, `bg-`, `font-`, `border-`, `hover:`, `transition-`, `hidden`, `flex`, `grid`

---

## 🎨 Paleta de Cores

| Nome | Hex | Uso |
|---|---|---|
| Cream | `#FAF6F0` | Fundo principal |
| Caramel | `#C8894E` | Cor de destaque / botões |
| Bark | `#6B4226` | Títulos e textos primários |
| Sage | `#7A9E7E` | Badges e acentos secundários |
| Blush | `#F2D4C2` | Fundos suaves e bordas |
| Charcoal | `#2D2926` | Texto corrido |

---

## ✨ Funcionalidades

- ✅ Layout totalmente responsivo (mobile, tablet e desktop)
- ✅ Menu hambúrguer funcional para telas pequenas
- ✅ Smooth scroll nas âncoras de navegação
- ✅ Hover com elevação nos cards de produto
- ✅ Formulário de contato com feedback visual de envio
- ✅ Animações CSS de entrada (`fade-up`, `fade-in`)
- ✅ Badges de desconto, novidade e mais vendido nos produtos

---

## 🚀 Como Rodar o Projeto

Nenhuma instalação necessária. Basta:

1. Clonar ou baixar o repositório:
   ```bash
   git clone https://github.com/seu-usuario/petstyle-loja-virtual.git
   ```

2. Abrir o arquivo `index.html` diretamente no navegador:
   ```bash
   # ou simplesmente dê duplo clique no arquivo
   open index.html
   ```

> O Tailwind CSS é carregado via CDN, então é necessária conexão com a internet para que os estilos funcionem corretamente.

---

## 🧪 Testando a Responsividade

Use o **DevTools** do navegador (`F12`) e ative o modo de dispositivo responsivo para testar em diferentes tamanhos de tela. Os principais breakpoints são:

| Breakpoint | Largura |
|---|---|
| Mobile (padrão) | < 640px |
| `sm:` | ≥ 640px |
| `md:` | ≥ 768px |
| `lg:` | ≥ 1024px |

---

## 📚 Referências

- [Documentação oficial do Tailwind CSS](https://tailwindcss.com/docs/)
- [Unsplash — Imagens gratuitas](https://unsplash.com/)
- [Google Fonts](https://fonts.google.com/)

---

## 👩‍💻 Autoria

Projeto desenvolvido como exercício prático de front-end com Tailwind CSS.

---

*Feito com 💛 para os melhores amigos do mundo 🐶🐱*
