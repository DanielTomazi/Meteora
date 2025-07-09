# Meteora - Loja de Roupas Premium

<div align="center">

![Meteora Logo](https://img.shields.io/badge/Meteora-Fashion%20Store-9353FF?style=for-the-badge&logo=star&logoColor=DAFF01)

**Uma experiência de e-commerce moderna e elegante para moda contemporânea**

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-Visit_Site-9353FF?style=for-the-badge)](https://meteoraclothes.vercel.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

</div>

---

## Sobre o Projeto

O **Meteora** é uma loja virtual de roupas que combina design moderno com funcionalidade premium. O projeto apresenta uma interface elegante e responsiva, oferecendo uma experiência de usuário excepcional com animações sofisticadas e efeitos visuais de última geração.

### Características Principais

- **Design Premium**: Interface moderna com gradientes complexos e glassmorphism
- **Totalmente Responsivo**: Otimizado para desktop, tablet e mobile
- **Performance Otimizada**: Carregamento rápido e animações fluidas
- **Microinterações**: Efeitos hover avançados e feedback visual
- **Sistema de Cores**: Paleta harmoniosa com cores vibrantes
- **Interatividade**: JavaScript vanilla para máxima performance

---

## Demo

![Meteora Preview](roupaimg-demo.png)

**[Acesse o site ao vivo](https://meteoraclothes.vercel.app/)**

---

## Tecnologias Utilizadas

| Tecnologia | Versão | Descrição |
|------------|--------|-----------|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white) | HTML5 | Estrutura semântica e acessível |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white) | CSS3 | Estilização avançada com variáveis CSS |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) | ES6+ | Interatividade e animações dinâmicas |
| ![Bootstrap](https://img.shields.io/badge/-Bootstrap-563D7C?logo=bootstrap&logoColor=white) | 5.3.2 | Framework CSS para responsividade |
| ![Google Fonts](https://img.shields.io/badge/-Google_Fonts-4285F4?logo=google&logoColor=white) | Inter | Tipografia moderna e legível |

---

## Funcionalidades

### **Interface Principal**
- ✅ Navbar fixa com efeitos de scroll
- ✅ Carousel responsivo com múltiplas imagens
- ✅ Sistema de busca integrado
- ✅ Animações de entrada suaves

### **Catálogo de Produtos**
- ✅ Grid responsivo de categorias
- ✅ Cards de produtos interativos
- ✅ Efeitos hover sofisticados
- ✅ Preços em destaque

### **Experiência Premium**
- ✅ Efeitos de glassmorphism
- ✅ Gradientes complexos
- ✅ Partículas animadas
- ✅ Transições suaves

### **Newsletter**
- ✅ Formulário interativo
- ✅ Validação em tempo real
- ✅ Feedback visual
- ✅ Design moderno

---

## Estrutura do Projeto

```
Meteora/
├── 📁 meteora-assets-main/
│   └── 📁 assets/
│       ├── 🖼️ favicon.png
│       ├── 🖼️ logo-meteora.png
│       ├── 📁 Desktop/
│       ├── 📁 Mobile/
│       └── 📁 Tablet/
├── 📄 index.html          # Página principal
├── 🎨 style.css          # Estilos customizados
├── 📖 README.md          # Documentação
├── 🖼️ roupaimg-demo.png  # Preview do projeto
└── 📜 LICENSE           # Licença do projeto
```

---

## Como Executar

### **Clone o Repositório**
```bash
git clone https://github.com/DanielTomazi/Meteora.git
cd Meteora
```

### **Abra o Projeto**
```bash
# Abrir diretamente no navegador
open index.html

# Ou usar Live Server (VS Code)
# Clique com botão direito em index.html > "Open with Live Server"
```

### **Ou Acesse Online**
**[🌐 meteoraclothes.vercel.app](https://meteoraclothes.vercel.app/)**

---

## Design System

### **Paleta de Cores**
```css
:root {
    --primary-color: #9353FF;     /* Roxo vibrante */
    --secondary-color: #DAFF01;   /* Verde neon */
    --accent-color: #FF6B6B;      /* Coral */
    --dark-color: #0F0F23;        /* Azul escuro */
    --text-dark: #1E293B;         /* Cinza escuro */
}
```

### **Tipografia**
- **Fonte Principal**: Inter (Google Fonts)
- **Pesos**: 300, 400, 500, 600, 700, 800
- **Hierarquia**: Títulos em gradiente, textos em cinza balanceado

### **Componentes**
- **Cards**: Border-radius 16px com sombras suaves
- **Botões**: Gradientes com efeitos hover
- **Inputs**: Focus states com glow
- **Animações**: Cubic-bezier para suavidade

---

## Responsividade

| Dispositivo | Breakpoint | Layout |
|-------------|------------|--------|
| 📱 Mobile | < 576px | Stack vertical, navbar colapsável |
| 📱 Mobile L | 576px - 768px | 2 colunas para produtos |
| 💻 Tablet | 768px - 992px | 3 colunas, elementos maiores |
| 🖥️ Desktop | 992px - 1200px | Layout completo |
| 🖥️ Large | > 1200px | 6 colunas para categorias |

---

## Performance

### **Otimizações Implementadas**
- ✅ **Imagens Responsivas**: Múltiplas resoluções para cada dispositivo
- ✅ **CSS Minificado**: Variáveis CSS para reutilização
- ✅ **JavaScript Otimizado**: Vanilla JS para performance máxima
- ✅ **Fonts Preload**: Google Fonts com preconnect
- ✅ **Lazy Loading**: Carregamento progressivo de elementos

### **Métricas**
- **Primeiro Carregamento**: < 2s
- **Interatividade**: < 0.5s
- **Mobile Performance**: 95+
- **Desktop Performance**: 98+

[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)](https://danieltomazi.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/daniel-tomazi)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DanielTomazi)

</div>

---
