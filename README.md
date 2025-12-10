# 🏗️ NexGen Engenharia - High Performance Landing Page

![Project Status](https://img.shields.io/badge/status-active-success.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Performance](https://img.shields.io/badge/performance-100%25-brightgreen)

> Uma Landing Page institucional desenvolvida com foco extremo em performance (Web Vitals), acessibilidade e SEO técnico. O projeto utiliza uma arquitetura "Zero-Image", substituindo arquivos de mídia pesados por CSS Grids, gradientes e formas geométricas renderizadas pelo navegador.

---

## 🚀 Destaques Técnicos

Este projeto foi arquitetado seguindo princípios de **High Performance Web Development**:

* **⚡ Arquitetura Zero-Bloqueio:** Não utiliza bibliotecas externas pesadas (como jQuery ou Bootstrap). Todo o CSS e JS é Vanilla.
* **🎨 CSS-Only Visuals:** As "imagens" de fundo e elementos gráficos são gerados via CSS (`linear-gradient`, `border-radius`, `transform`), garantindo um carregamento instantâneo e zero *layout shift*.
* **📱 Design Responsivo Fluido:** Utiliza **CSS Grid** (`repeat(auto-fit, minmax...)`) e **Flexbox** para adaptação perfeita de 320px a 4k sem necessidade de media queries excessivas.
* **🔍 SEO Semântico:** Estrutura HTML5 rigorosa (`<header>`, `<main>`, `<section>`, `<article>`, `<footer>`) para máxima indexação por motores de busca.
* **♿ Acessibilidade:** Contraste de cores validado e hierarquia tipográfica clara.
* **🛠 Design System via Variáveis:** Paleta de cores e tipografia centralizadas no `:root` para manutenção escalável.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 Semântico**
* **CSS3** (Custom Properties, Grid Layout, Animations)
* **JavaScript (ES6+)** (apenas para *Smooth Scroll* e interações leves)
* **RemixIcon** (Ícones vetoriais via CDN otimizado)

---

## 🎨 Personalização (Design System)

O projeto utiliza **CSS Custom Properties** para facilitar a personalização do tema. Para alterar as cores da marca, edite a seção `:root` no início do `<style>` ou arquivo CSS:

```css
:root {
    /* Cores Primárias */
    --primary-blue: #007bff;      /* Cor de Ação/Destaque */
    --deep-blue: #0056b3;         /* Hover State */
    
    /* Modo Dark / Estrutural */
    --black: #050a14;             /* Background Principal */
    --dark-slate: #0b1120;        /* Background Secundário */
    --gray-slate: #1e293b;        /* Cards */
    
    /* Tipografia e Ícones */
    --white: #ffffff;
    --light-gray: #94a3b8;
    --accent-steel: #6c757d;
}
