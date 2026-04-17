![GitHub repo size](https://img.shields.io/github/repo-size/Domisnnet/Responsive-Web-Essentials?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/Domisnnet/Responsive-Web-Essentials?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/Domisnnet/Responsive-Web-Essentials?style=for-the-badge)

<h2 id="sobre-o-projeto">1. 📱 Media Queries: Domine a Adaptação de Conteúdo! 💻</h2>

![Status do Build](https://img.shields.io/badge/Status-Online-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML%20%7C%20CSS-blueviolet)
[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/Responsive-Web-Essentials/blob/main/LICENSE)

![Media Queries](src/imagens/media-queries.png)

Bem-vindo ao projeto **Media Query Master**! Este repositório é um guia prático e interativo focado na criação de layouts responsivos. Através de técnicas avançadas de CSS, demonstramos como o conteúdo se adapta fluidamente de smartphones pequenos a telas de TV 4K, garantindo que o design seja sempre funcional e visualmente atraente.

---

## 📚 Tabela de Conteúdo

| 📱 O Projeto | 🛠️ Técnico | 🤝 Comunidade |
| :---: | :---: | :---: |
| [![1. Sobre](https://img.shields.io/badge/1%20-%20Sobre-4CAF50)](#sobre-o-projeto) | [![5. Destaques](https://img.shields.io/badge/5%20-%20Destaques-607D8B)](#destaques-tecnicos) | [![9. Código](https://img.shields.io/badge/9%20-%20Código-795548)](#codigo-fonte) |
| [![2. Techs](https://img.shields.io/badge/2%20-%20Techs-2196F3)](#tecnologias-utilizadas) | [![6. Instalação](https://img.shields.io/badge/6%20-%20Instala%C3%A7%C3%A3o-009688)](#instalacao) | [![10. Créditos](https://img.shields.io/badge/10%20-%20Créditos-607D8B)](#créditos) |
| [![3. Acessar](https://img.shields.io/badge/3%20-%20Acessar-FF9800)](#como-acessar) | [![7. Contribuir](https://img.shields.io/badge/7%20-%20Contribuir-3F51B5)](#como-contribuir) | [![11. Licença](https://img.shields.io/badge/11%20-%20Licença-E91E63)](#licenca) |
| [![4. Funções](https://img.shields.io/badge/4%20-%20Funções-9C27B0)](#funcionalidades) | [![8. FAQ](https://img.shields.io/badge/8%20-%20FAQ-FFC107)](#faq) | [![12. Perfil](https://img.shields.io/badge/12%20-%20Perfil-212121)](#perfil-do-github) |

---

<h2 id="tecnologias-utilizadas">2. ⚙️ Tecnologias Utilizadas</h2>

| Camada | Tecnologias | Descrição |
| :--- | :--- | :--- |
| **Estrutura** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) | Marcação semântica preparada para reestruturação via CSS. |
| **Estilo Base** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Estilização principal seguindo a metodologia **Mobile First**. |
| **Adaptação** | ![Media Queries](https://img.shields.io/badge/Media--Queries-blueviolet?style=flat-square&logo=css3) | Breakpoints estratégicos para Mobile, Tablet, Desktop e TV. |

---

<h2 id="como-acessar">3. 🚀 Como Acessar</h2>

Teste a responsividade redimensionando seu navegador através da demonstração ao vivo:

<div align="left">
  <a href="https://Domisnnet.github.io/Responsive-Web-Essentials/" target="_blank">
    <img alt="Botão Acessar" src="src/imagens/botão.webp" height="70" width="70" />
  </a>
</div>

---

<h2 id="funcionalidades">4. 🧩 Funcionalidades Principais</h2>

O projeto explora as diversas aplicações das Media Queries:

| Funcionalidade | Descrição |
| :--- | :--- |
| 📱 **Mobile First** | Carregamento otimizado começando pela menor tela. |
| 🔀 **Layout Fluido** | Mudança radical de grid (colunas) baseada na largura da tela. |
| 🖨️ **Print Style** | Estilização exclusiva para impressão, removendo elementos desnecessários. |
| 📺 **Suporte a 4K** | Regras específicas para resoluções de grandes dimensões. |
| 🎨 **Feedback Visual** | Cores e elementos que mudam para indicar o breakpoint ativo. |

---

<h2 id="destaques-tecnicos">5. 💻 Destaques Técnicos</h2>

A engenharia do CSS foi dividida para facilitar a manutenção:

### 📐 `style.css` (Base)
Contém os estilos universais e o layout para smartphones. É o arquivo mais leve, garantindo rapidez no carregamento inicial.

### 🔄 `media-query.css` (Adaptação)
Este arquivo contém todos os `@media` rules. Ele é responsável por "sobrescrever" o estilo base à medida que a tela cresce, transformando menus hambúrguer em barras horizontais e empilhamentos em grids.

---

<h2 id="instalacao">6. 🚀 Instalação e Configuração Local</h2>

Analise como os breakpoints foram configurados:

```bash
# Clonar o repositório
git clone https://github.com/Domisnnet/Responsive-Web-Essentials.git(https://github.com/Domisnnet/Responsive-Web-Essentials.git)

# Acessar a pasta
cd Responsive-Web-Essentials
```

---

<h2 id="como-contribuir">7. 🤝 Como Contribuir</h2>

Siga os passos abaixo para adicionar novos layouts:

| Fase | Ação | Link / Comando |
| :---: | :--- | :--- |
| **01** | **Fork** | [![Fork](https://img.shields.io/badge/-Fazer%20Fork-blue?style=flat-square&logo=github)](https://github.com/Domisnnet/Responsive-Web-Essentials/fork) |
| **02** | **Branch** | `git checkout -b feature/NovoBreakpoint` |
| **03** | **Commit** | `git commit -m 'feat: suporte para telas ultrawide'` |
| **04** | **Push** | `git push origin feature/NovoBreakpoint` |
| **05** | **PR** | [![Abrir PR](https://img.shields.io/badge/-Abrir%20PR-green?style=flat-square&logo=git)](https://github.com/Domisnnet/Responsive-Web-Essentials/compare)

### 🐛 Encontrou um problema?
Se algo não estiver funcionando como esperado, não hesite em abrir um chamado:

[![Issues Abertas](https://img.shields.io/github/issues/Domisnnet/Responsive?style=flat-square&color=red&logo=github)](https://github.com/Domisnnet/Responsive-Web-Essentials/issues)
[![Report Bug](https://img.shields.io/badge/Reportar-Erro-critical?style=flat-square&logo=github)](https://github.com/Domisnnet/Responsive-Web-Essentials/issues/new)


---

<h2 id="faq">8. 🧠 Perguntas Frequentes (FAQ)</h2>

<details>
<summary><strong>O que é Mobile First ❓</strong></summary>
<p>📱 <strong>Resposta:</strong> É a estratégia de desenvolver o site primeiro para telas pequenas e depois adicionar recursos para telas maiores. Isso melhora o desempenho e o SEO.</p>
</details>

<details>
<summary><strong>Como testar sem ter vários aparelhos ❓</strong></summary>
<p>🛠️ <strong>Resposta:</strong> Você pode usar o <strong>DevTools</strong> do seu navegador (F12) e clicar no ícone de "Toggle Device Toolbar" para simular diversos modelos de celular.</p>
</details>

<details>
<summary><strong>Quais os breakpoints usados ❓</strong></summary>
<p>📐 <strong>Resposta:</strong> Seguimos os padrões mais comuns: 480px (Mobile L), 768px (Tablet), 1024px (Laptop) e 1280px+ (Desktop).</p>
</details>

---

<h2 id="codigo-fonte">9. 💻 Código Fonte</h2>

Explore a estrutura de pastas e os arquivos CSS:

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=fff)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=fff)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000)
[![Repositório](https://img.shields.io/badge/Repositório-Domisnnet%2FResponsive--Web--Essentials-F7DF1E?style=for-the-badge&logo=github&labelColor=0d1117)](https://github.com/Domisnnet/Responsive-Web-Essentials)

---

<h2 id="créditos">10. 📝 Créditos & Reconhecimentos</h2>

Este projeto foi construído com foco em melhores práticas de UI/UX:

| Atribuição | Responsável / Recurso | Descrição |
| :--- | :--- | :--- |
| **Dev & Design** | **DomisDev** | Implementação técnica de todos os breakpoints CSS. |
| **Mídia** | **YouTube** | Vídeo de demonstração técnica disponível no README. |
| **Referência** | **W3C Standards** | Base técnica para implementação de Media Queries. |
| **Apoio Técnico** | **Google Gemini** | Padronização documental para o modelo King-Domfy. |

### 🎯 Versões (Changelog)
* **v1.0.0:** Lançamento com suporte Mobile, Tablet e Desktop.
* **v1.1.0:** Adicionado suporte para estilos de impressão.

---

<h2 id="licenca">11. 📄 Licença</h2>

Este projeto está licenciado sob a [![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/Responsive-Web-Essentials/blob/main/LICENSE)

---

<h2 id="perfil-do-github">12. 👨‍💻 Perfil do GitHub</h2>

<a href="https://github.com/Domisnnet"> 
  <img src="src/imagens/DomisDev.png" width="90" alt="Acessar perfil GitHub"> 
</a>
