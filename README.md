# DevLinks

Uma página de links pessoal desenvolvida durante o curso Explorer da Rocketseat. Este projeto apresenta um design moderno e responsivo com funcionalidade de alternância entre modo claro e escuro.

## 🚀 Funcionalidades

- **Design Responsivo**: Adaptável para dispositivos móveis e desktop
- **Alternância de Tema**: Botão para alternar entre modo claro e escuro
- **Links Pessoais**: Seção para links importantes e portfólio
- **Redes Sociais**: Ícones para GitHub, Instagram, Discord e LinkedIn
- **Animações Suaves**: Transições e animações CSS para melhor experiência do usuário

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização com variáveis CSS e animações
- **JavaScript**: Funcionalidade de alternância de tema
- **Ionicons**: Ícones para redes sociais
- **Google Fonts**: Fonte Inter para tipografia

## 📁 Estrutura do Projeto

```
DevLinks/
├── assets/
│   ├── avatar-dark.jpeg
│   ├── avatar-light.jpg
│   ├── bg-desktop-light.jpg
│   ├── bg-desktop.jpg
│   ├── bg-mobile-light.jpg
│   ├── bg-mobile.jpg
│   ├── moon-stars.svg
│   └── sun.svg
├── index.html
├── script.js
├── style.css
└── README.md
```

## 🎨 Características do Design

### Modo Escuro (Padrão)
- Fundo escuro com imagem de fundo
- Texto em branco
- Avatar com borda clara
- Ícone de lua e estrelas no switch

### Modo Claro
- Fundo claro com imagem de fundo adaptada
- Texto em preto
- Avatar com borda escura
- Ícone de sol no switch

## 🔧 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/DevAraujo128/DevLinks.git
```

2. Abra o arquivo `index.html` em seu navegador

3. Personalize os links e informações no arquivo `index.html`

4. Modifique as cores e estilos no arquivo `style.css`

## 📱 Responsividade

O projeto é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- **Mobile**: Layout otimizado para dispositivos móveis
- **Desktop**: Layout expandido para telas maiores
- **Imagens de fundo**: Diferentes imagens para mobile e desktop

## 🎯 Personalização

### Alterando Links
Edite as seções no `index.html`:
```html
<ul>
  <li>
    <a href="SEU_LINK" target="_blank">Seu texto</a>
  </li>
</ul>
```

### Alterando Redes Sociais
Modifique a seção `#social-links`:
```html
<div id="social-links">
  <a href="SEU_GITHUB" target="_blank">
    <ion-icon name="logo-github"></ion-icon>
  </a>
</div>
```

### Alterando Cores
As cores são definidas através de variáveis CSS no arquivo `style.css`:
```css
:root {
  --text-color: #ffffff;
  --surface-color: rgba(255, 255, 255, 0.05);
  /* ... outras variáveis */
}
```

## 🚀 Deploy

Para fazer o deploy do projeto, você pode usar:

- **GitHub Pages**: Conecte seu repositório ao GitHub Pages
- **Netlify**: Arraste a pasta do projeto para o Netlify
- **Vercel**: Conecte seu repositório ao Vercel

## 👨‍💻 Autor

**João Araujo**
- GitHub: [@DevAraujo128](https://github.com/DevAraujo128)
- LinkedIn: [João Pedro Araújo Rodrigues](www.linkedin.com/in/joão-pedro-araújo-rodrigues-717170240)

## 📄 Licença

Este projeto foi desenvolvido durante o curso Explorer da [Rocketseat](https://rocketseat.com.br/).

---

Feito com ❤ pela [Rocketseat](https://rocketseat.com.br/) 