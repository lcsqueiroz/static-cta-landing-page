# Static CTA Landing Page

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![WCAG 2.2 AA Compliant](https://img.shields.io/badge/Accessibility-WCAG%202.2%20AA-green.svg)
![Lighthouse Performance Target](https://img.shields.io/badge/Lighthouse-95%2B%20Target-yellow.svg)

> Landing page estática com foco em conversão (CTA), desenvolvida com arquitetura front-end profissional, performance e otimização para mecanismos de busca (SEO).

- **Live Demo:** [Em desenvolvimento]
- **Repositório:** [https://github.com/lcsqueiroz/static-cta-landing-page]

---

## Princípios de Desenvolvimento

Este projeto foi construído seguindo diretrizes estritas de qualidade, performance e acessibilidade.

- **Arquitetura CSS:** Utilização da arquitetura **ITCSS** para garantir uma cascata de estilos lógica, previsível e de baixa especificidade. A nomenclatura segue o padrão **BEM** para modularidade e encapsulamento de componentes.

- **Performance (Core Web Vitals):** O desenvolvimento é orientado para atingir as seguintes metas de performance, aferidas pelo Lighthouse:

  - **Largest Contentful Paint (LCP):** `< 2.5s`
  - **Cumulative Layout Shift (CLS):** `< 0.1`
  - **Interaction to Next Paint (INP):** `< 200ms`
  - _Otimizações incluem lazy loading de imagens, fontes WOFF2 com `font-display: swap` e um caminho de renderização crítico otimizado._

- **Acessibilidade (WCAG 2.2 AA):** O projeto visa conformidade com o nível AA da WCAG 2.2, garantindo:

  - Navegação completa via teclado.
  - HTML semântico com landmarks e hierarquia de títulos correta.
  - Gerenciamento de foco e uso de atributos ARIA quando necessário.
  - Relação de contraste mínima de 4.5:1 para textos.

- **SEO Técnico:** Estrutura otimizada para rastreamento e indexação, incluindo:
  - Meta tags (`title`, `description`).
  - Tags Open Graph e Twitter Cards para compartilhamento social.
  - `robots.txt` e `sitemap.xml`.
  - `<link rel="canonical">` para evitar conteúdo duplicado.

## Stack Tecnológica

- **HTML5:** Semântico, acessível e otimizado para SEO.
- **CSS3:** Arquitetura ITCSS, nomenclatura BEM, Flexbox/Grid e variáveis CSS para theming.
- **JavaScript (ES6+):** Vanilla JS para interatividade, com foco em performance e progressive enhancement.

## Estrutura de Pastas

A estrutura de arquivos foi desenhada para refletir a arquitetura ITCSS e separar as responsabilidades de forma clara.

```
/
├── assets/
│   ├── fonts/          # Arquivos de fontes (WOFF2)
│   └── images/         # Imagens e ícones (SVG, PNG, etc.)
├── src/
│   └── js/             # Scripts JavaScript
│       └── main.js
├── style/
│   ├── 1-settings/     # Variáveis CSS, fontes, configs globais
│   ├── 2-tools/        # Mixins
│   ├── 3-generic/      # Reset, Normalize
│   ├── 4-elements/     # Estilos base de tags (h1, p, a)
│   ├── 5-objects/      # Padrões de layout (container, grid)
│   ├── 6-components/   # Componentes BEM (_button.css, _card.css)
│   ├── 7-sections/     # Seções da página (_hero.css, _footer.css)
│   └── 8-utilities/    # Classes utilitárias (spacing, colors)
├── index.html          # Ponto de entrada do HTML
├── sitemap.xml         # Mapa do site para SEO
├── robots.txt          # Diretivas para crawlers
├── LICENSE             # Licença do projeto
└── README.md           # Este arquivo
```

## Como Rodar o Projeto

Este é um projeto estático. Nenhuma ferramenta de build é necessária para visualização.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/lcsqueiroz/static-cta-landing-page.git
    ```
2.  **Navegue até a pasta do projeto:**
    ```bash
    cd static-cta-landing-page
    ```
3.  **Abra o arquivo `index.html`** no seu navegador de preferência.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

- **Lucas Queiroz Vieira**
- **GitHub:** [github.com/lcsqueiroz](https://github.com/lcsqueiroz)
- **LinkedIn:** [linkedin.com/in/lcsqueiroz](https://www.linkedin.com/in/lcsqueiroz)
- **E-mail:** lqvieira7@gmail.com
