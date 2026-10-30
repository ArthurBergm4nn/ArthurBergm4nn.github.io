# Diretrizes para Agentes de IA (AGENTS.md)

Este documento orienta qualquer agente de inteligência artificial ou desenvolvedor que trabalhe neste repositório.

## 1. Perfil do Projeto e do Usuário
- **Proprietário do projeto:** Arthur Bergmann de Oliveira.
- **Formação:** Graduação em Ciências Contábeis na Universidade Atitus (2º semestre - Turma 2026/1).
- **Foco Profissional:** Áreas contábil e fiscal com forte viés de desenvolvimento de soluções, análise de dados e automação (Power BI, extensões em Qlik Cloud, VBA/Excel).
- **Perfil técnico do usuário:** Usuário leigo em desenvolvimento web tradicional (HTML/CSS/JS), porém com conhecimento em lógica, dados e ferramentas analíticas.
- **Objetivo do projeto:** Portfólio pessoal e profissional de página única (*One-page*), moderno e limpo, hospedado no GitHub Pages.
- **Princípio fundamental:** Simplicidade estrutural, clareza e autonomia para que o Arthur consiga atualizar textos, adicionar projetos e trocar arquivos sem precisar de ferramentas complexas.

---

## 2. Princípios de Desenvolvimento Orientado por Especificação (Spec-Driven Development)
1. **Fonte Única da Verdade (`SPEC.md`):** Nenhuma página, funcionalidade ou estilo deve ser criado sem prévio alinhamento e registro no `SPEC.md`.
2. **Atualização Prévia da Especificação:** Se novas ideias ou requisitos surgirem, eles devem ser incorporados primeiro ao `SPEC.md` antes de serem codificados.
3. **Escrita sem Execução Antecipada:** O agente deve apenas criar ou alterar código quando expressamente instruído pelo usuário após a validação da especificação.
4. **Comentários Didáticos no Código:** Todas as seções do código devem conter comentários claros em português indicando onde alterar fotos, links de redes sociais, arquivos de projetos e currículo em PDF.

---

## 3. Diretrizes Técnicas e Tecnologias
- **Hospedagem:** GitHub Pages (arquivos estáticos diretos na raiz).
- **Pilha de Tecnologias (Stack):**
  - **HTML5 Semântico:** Estrutura clara e acessível (`header`, `nav`, `main`, `section`, `footer`).
  - **CSS3 / Tailwind via CDN ou CSS puro:** Manter a estilização simples e direta, sem necessidade de ferramentas de compilação (Node.js, npm, Webpack, Vite). O site deve funcionar perfeitamente ao dar duplo clique no arquivo `index.html`.
  - **JavaScript Vanilla:** Scripts mínimos e limpos para navegação suave (*smooth scroll*), menu responsivo em telas móveis e modais/filtros se necessário.
- **Design e Cores:**
  - Azul marinho como cor predominante de base/fundo corporativo.
  - Toques em turquesa para destaques analíticos, botões de ação e links.
  - Preto e branco para contraste, tipografia e legibilidade.
- **Organização de Pastas Sugerida:**
  - `index.html` (na raiz do projeto para o GitHub Pages)
  - `/assets/css/` (folhas de estilo)
  - `/assets/js/` (scripts simples)
  - `/assets/images/` (foto de perfil e capas de projetos)
  - `/assets/docs/` (arquivo do currículo em PDF e materiais de apoio)

---

## 4. Instruções de Suporte e Comunicação
- Comunicação direta, profissional e sem jargões desnecessários de desenvolvimento web.
- Passo a passo claro para envio ao repositório no GitHub e ativação do GitHub Pages quando chegar a fase de publicação.
