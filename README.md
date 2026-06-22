### [PORTUGUESE / ENGLISH BELOW] ###

# 🛍️ Casa & Lar - Landing Page de E-Commerce

<img width="1920" height="1080" alt="desktop-celular-lp" src="https://github.com/user-attachments/assets/9ae30189-01df-407b-912a-006ec09396e7" />

Desenvolvimento de uma landing page de e-commerce moderna, fluida, responsiva e focada em performance para a loja **Casa & Lar**, estabelecimento fictício responsável pela venda móveis, roupas, plantas, decorações e produtos artesanais de alta qualidade.

Este projeto foi construído para fornecer uma experiência de compra agradável e interativa, com design sofisticado, transições suaves e interface responsiva para celulares, tablets e desktops.

---
## 📷 Preview

Visualize a landing page funcional deste e-commerce [AQUI!](https://allespin.github.io/ecommerce-landing-page-casa-e-lar/)

---

## 🚀 Tecnologias Utilizadas

| Tecnologia | Uso |
| :--- | :--- |
| HTML5 | Estruturação semântica do layout e conteúdo da página. |
| Tailwind CSS v3 | Estilização responsiva e moderna baseada em classes utilitárias. |
| PostCSS | Processamento e otimização dos estilos CSS. |
| Autoprefixer | Adição automática de prefixos de navegadores para compatibilidade do CSS. |
| JavaScript (ES6+) | Lógica de interação do usuário (menu responsivo, slider, carrinho). |
| JSON | Estruturação de dados e gerenciamento de configurações/dependências do projeto. |
| Google Fonts | Carregamento das fontes tipográficas do projeto (Montserrat e Cormorant Garamond). |
| Material Symbols | Iconografia limpa para elementos interativos da interface. |
| IonIcons | Pacote de ícones adicionais para enriquecimento visual do layout. |

---

## ✨ Principais Funcionalidades

1. **Cabeçalho inteligente**: Barra de navegação que se fixa no topo da página quando o usuário rola para baixo (após 50px), mudando seu plano de fundo para garantir uma leitura de tela confortável.

2. **Menu responsivo**: Menu lateral interativo que se abre em dispositivos menores, melhorando a navegabilidade em smartphones.

3. **Menu dropdown interativo**: Submenu dinâmico para categorias da loja (Produtos, Roupas, Plantas, Acessórios, Mochilas, Relógios e Promoções).

4. **Carrinho de compras modal**: Janela modal interativa para visualização fácil de itens selecionados.

5. **Slider de avaliações / Review dos clientes**:
   - Carrossel automático com transição a cada 2 segundos.
   - Botões manuais de navegação ("Anterior" e "Próximo").
   - Pausa inteligente no carrossel quando o usuário passa o mouse por cima (hover) para facilitar a leitura das avaliações dos clientes, retornando o movimento ao tirar o ponteiro.
   
6. **Efeitos visuais sofisticados**: Elementos com blur dinâmico, efeitos de zoom suave em imagens durante o hover e seções de destaque para promoções selecionadas.

---

## 📁 Estrutura do projeto

Abaixo está o mapeamento dos principais arquivos e pastas do projeto:

```text
casaelar/
├── assets/                  # Arquivos estáticos e recursos do site
│   ├── imgs/                # Imagens do e-commerce (móveis, roupas, etc.)
│   ├── images/              # Ícones e imagens originais do template base
│   └── js/
│       └── script.js        # Lógica JavaScript (Slider, Navbar, Modal)
├── dist/                    # Pasta de distribuição gerada pelo Tailwind
│   └── style.css            # CSS compilado e otimizado para produção
├── src/                     # Pasta de código fonte dos estilos
│   └── style.css            # Estilo fonte utilizando diretivas do Tailwind
├── index.html               # Página principal da aplicação
├── package.json             # Dependências de desenvolvimento e scripts
├── postcss.config.js        # Configuração do PostCSS
├── tailwind.config.js       # Customizações do Tailwind (paleta de cores, fontes)
└── README.md                # Documentação técnica e do projeto
```

---

## ⚙️  Como executar o projeto localmente


### Pré-requisitos
Certifique-se de ter o [Node.js](https://nodejs.org/) instalado em seu computador para poder instalar as dependências e compilar os estilos do Tailwind CSS.

### Passo 1: Clone este repositório
Abra o terminal e execute o comando abaixo para clonar o repositório em sua máquina:
```bash
git clone https://github.com/allespin/ecommerce-landing-page-casa-e-lar.git
```

### Passo 2: Instalar dependências
Navegue até a pasta do projeto clonado e execute o comando para instalar as ferramentas de desenvolvimento (Tailwind CSS, PostCSS, Autoprefixer):
```bash
npm install
```

### Passo 3: Compilar os estilos (CSS)
Para gerar o arquivo final de CSS compilado na pasta `dist/style.css`, você possui dois scripts configurados:

*   **Para desenvolvimento (Modo Observador / Watch):**
    Este comando observa as alterações nos seus arquivos HTML e CSS fonte e recompila automaticamente sempre que você salvar algo:
    ```bash
    npm run watch
    ```

*   **Para produção (Build único):**
    Gera o CSS compilado final de uma só vez:
    ```bash
    npm run build
    ```

### Passo 4: Visualizar no navegador
Após compilar o CSS pelo menos uma vez, basta abrir o arquivo ```index.html``` diretamente em qualquer navegador, ou utilizar extensões como o **Live Server** (do VS Code) para ter atualizações automáticas em tempo real.

---

## 🛠️ Detalhes de customização do Tailwind CSS

No arquivo `tailwind.config.js`, foram mapeadas cores específicas que dão a identidade visual aconchegante da marca:

- **`papaya_whip` (`#ffefd5`)**: O tom claro e elegante de fundo.
- **`caf_noir` (`#4f3120`)**: O tom marrom escuro sofisticado usado para textos principais e botões.
- **`jet` (`#333333`)**: Textos secundários.
- **`butterscotch` (`#e9973f`)**: Destaques de preços, descontos e taxas de desconto de promoções.

---

# 🛍️ Casa & Lar - E-Commerce Landing Page (English)

A modern, fluid, responsive, and performance-focused e-commerce landing page for **Casa & Lar**, a fictional store specializing in high-quality furniture, clothes, plants, decor, and handcrafted items.

This project was built to provide an attractive and interactive shopping experience with sophisticated design, smooth transitions, and a responsive layout that adapts to mobile devices, tablets, and desktops.

---
## 📷 Preview

Visualize a functional landing page for this e-commerce [HERE!](https://allespin.github.io/ecommerce-landing-page-casa-e-lar/)


---

## 🚀 Technologies used

| Technology | Use |
| :--- | :--- |
| HTML5 | Semantic structuring of the page layout and content. |
| Tailwind CSS v3 | Responsive and modern styling using utility classes. |
| PostCSS | Processing and optimization of CSS styles. |
| Autoprefixer | Automatically adding vendor prefixes to CSS for browser compatibility. |
| JavaScript (ES6+) | User interaction logic (mobile menu, slider, cart toggling). |
| JSON | Data structuring and project configuration/dependency management. |
| Google Fonts | Loading typography styles for the project (Montserrat and Cormorant Garamond). |
| Material Symbols | Modern and clean iconography for interactive interface elements. |
| IonIcons | Additional icon library used to enhance visual styling. |

---

## ✨ Key features

1. **Sticky header**: Navigation bar that sticks to the top of the page when the user scrolls down (after 50px), changing its background to ensure perfect readability.

2. **Mobile off-canvas menu**: An interactive sidebar menu that opens on smaller devices, improving navigation on smartphones.
3. 
4. **Interactive dropdown menu**: A dynamic submenu for store categories (Products, Clothes, Plants, Accessories, Backpacks, Watches, and Sales).
5. 
6. **Shopping cart modal**: An interactive modal window for easily viewing selected items.
7. 
8. **Review / Testimonial slider (custom slider)**:
   - Auto-sliding carousel that transitions every 2 seconds.
   - Manual navigation buttons ("Prev" and "Next").
   - Smart pause on hover so users can comfortably read client reviews, resuming movement when the mouse pointer leaves.

9. **Clean design**: Dynamic blur elements, smooth zoom effects on images during hover, and highlighted sections for special deals.

---

## 📁 Project structure

Below is the directory mapping of the main project files and folders:

```text
casaelar/
├── assets/                  # Static assets and site resources
│   ├── imgs/                # E-commerce images (furniture, clothes, etc.)
│   ├── images/              # Icons and original images from base template
│   └── js/
│       └── script.js        # JavaScript logic (Slider, Navbar, Modal)
├── dist/                    # Distribution folder generated by Tailwind
│   └── style.css            # Compiled and optimized CSS for production
├── src/                     # Style source files folder
│   └── style.css            # Source CSS using Tailwind directives
├── index.html               # Main application HTML file
├── package.json             # Dev dependencies and scripts
├── postcss.config.js        # PostCSS configuration
├── tailwind.config.js       # Tailwind configuration (color palette, fonts)
└── README.md                # Project and technical documentation
```

---

## ⚙️ How to run the project locally

### Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed on your computer to install development dependencies and compile Tailwind CSS styles.

### Step 1: Clone this repository
Open the terminal and run the command below to clone the repository to your machine:
```bash
git clone https://github.com/allespin/ecommerce-landing-page-casa-e-lar.git
```

### Step 2: Install dependencies
Navigate into the cloned project folder and execute the command to install dev tools (Tailwind CSS, PostCSS, Autoprefixer):
```bash
npm install
```

### Step 3: Compile styles (CSS)
To compile the CSS styles into the `dist/style.css` file, you have two configured scripts:

*   **For development (Watch Mode):**
    This command watches for changes in your HTML and source CSS files and automatically recompiles whenever you save:
    ```bash
    npm run watch
    ```

*   **For production (Single Build):**
    Generates the final compiled CSS in one run:
    ```bash
    npm run build
    ```

### Step 4: View in browser
After compiling the CSS at least once, simply open ```index.html``` directly in any browser, or use extensions like VS Code's **Live Server** to get real-time hot reloading.

---

## 🛠️ Tailwind CSS Customization Details

In the `tailwind.config.js` file, specific colors were mapped to give the brand its cozy visual identity:

- **`papaya_whip` (`#ffefd5`)**: The light and elegant background tone.
- **`caf_noir` (`#4f3120`)**: The sophisticated dark brown tone used for primary text and buttons.
- **`jet` (`#333333`)**: Secondary text color.
- **`butterscotch` (`#e9973f`)**: Highlights for prices, discounts, and sale badges.
