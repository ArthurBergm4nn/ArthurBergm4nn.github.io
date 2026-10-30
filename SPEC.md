# Especificação do Projeto: Portfólio Profissional (SPEC.md)

Este documento é a especificação formal, visual e funcional do site de portfólio pessoal de **Arthur Bergmann de Oliveira**. Ele serve como fonte única da verdade para o desenvolvimento orientado por especificação (Spec-Driven Development).

---

## 1. Visão Geral e Identificação
- **Nome do Titular:** Arthur Bergmann de Oliveira
- **Formação:** Graduação em Ciências Contábeis — Universidade Atitus (2º Semestre | Turma 2026/1)
- **Posicionamento de Carreira:** Profissional e acadêmico com foco na intersecção entre **Contábil/Fiscal** e **Desenvolvimento de Soluções e Automação** (Power BI, Qlik Cloud, VBA/Excel).
- **Objetivo do Site:** Centralizar e apresentar projetos práticos, competências técnicas e trajetória acadêmica para recrutadores, empresas e parceiros, fortalecendo a presença profissional digital.
- **Hospedagem:** GitHub Pages (gratuito, sem necessidade de servidor back-end).

---

## 2. Identidade Visual e Estilo
- **Conceito Visual:** Sóbrio, tecnológico e analítico — transmitindo precisão contábil e inovação tecnológica.
- **Paleta de Cores:**
  - **Cor Primária:** Azul Marinho profundo (base sólida, corporativa e confiável).
  - **Cor de Destaque / Acento:** Turquesa suave / Ciano analítico (usado em botões de ação, ícones, tags de projetos e destaques visuais).
  - **Neutros:** Preto e Branco (fundo equilibrado, tipografia de alto contraste e fácil leitura).
- **Tipografia:** Famílias sans-serif modernas, limpas e geométricas (ex: Inter ou Montserrat via Google Fonts).
- **Elementos Visuais:**
  - Foto de perfil profissional em destaque na seção de introdução.
  - Cards visuais para cada projeto com tags de tecnologias aplicadas.
  - Ícones vetoriais modernos (via FontAwesome ou Lucide Icons por CDN) para redes sociais e ferramentas.

---

## 3. Arquitetura da Informação e Estrutura de Navegação
O site será estruturado em formato **Página Única (*One-Page*)**, otimizando a experiência do visitante em celulares e desktops, com uma barra de navegação superior fixa com rolagem suave (*smooth scroll*).

### Seções da Página
1. **Barra de Navegação (Navbar Fixa):**
   - Logotipo/Identificador textual: **Arthur Bergmann**
   - Links de atalho rápido: *Início*, *Sobre*, *Competências*, *Projetos*, *Currículo*, *Contato*.
   - Menu hambúrguer adaptável para smartphones.

2. **Seção Hero (Apresentação Principal):**
   - Foto profissional de perfil em moldura destacada com borda turquesa suave.
   - Saudação e nome completo em destaque.
   - Título/Subtítulo dinâmico: *"Ciências Contábeis & Desenvolvimento | Foco em Soluções Contábeis, Fiscais e Business Intelligence"*.
   - Botões de Ação Principal (CTAs):
     - Botão 1: **"Ver Projetos"** (rola suavemente até a seção de projetos).
     - Botão 2: **"Baixar Currículo"** (abre/baixa o PDF do currículo).

3. **Seção Sobre Mim:**
   - Breve biografia destacando a formação na Universidade Atitus (Turma 2026/1).
   - Apresentação da proposta de valor: unir a visão contábil/fiscal ao poder da automação, análise de dados e desenvolvimento de ferramentas para otimização de rotinas e tomadas de decisão.

4. **Seção de Competências Técnicas & Ferramentas:**
   - **Contábil / Fiscal:** Análise contábil, conciliações, rotinas fiscais e visão estratégica de dados.
   - **Business Intelligence & Dados:** Power BI (modelagem DAX, dashboards executivos), Qlik Cloud (criação e desenvolvimento de extensões).
   - **Automação & Programação:** Macros e automações avançadas em Excel (VBA), estruturação de dados.

5. **Seção de Projetos em Destaque:**
   Exibição em cards modernos contendo título, resumo do desafio/solução, tags das tecnologias utilizadas e botões de ação com suporte a materiais futuros:
   - **Projeto 1: Dashboard Financeiro em Power BI**
     - *Foco:* Visualização de indicadores econômico-financeiros, DRE gerencial e métricas de fluxo de caixa.
     - *Status de Materiais:* Espaço reservado para visualização/link de demonstração quando disponível.
   - **Projeto 2: Desenvolvimento de Extensões no Qlik Cloud**
     - *Foco:* Personalização e extensão de recursos nativos para atender necessidades específicas de análise de dados.
     - *Status de Materiais:* Espaço reservado para documentação/capturas de tela do funcionamento da extensão.
   - **Projeto 3: Desenvolvimento de Macros e Automações em VBA (Excel)**
     - *Foco:* Otimização de rotinas repetitivas, tratamento de planilhas contábeis/fiscais e aumento de produtividade operacional.
     - *Status de Materiais:* Espaço reservado para download de amostras ou guia descritivo de automação.

6. **Seção de Download do Currículo:**
   - Bloco visual chamativo para convidar recrutadores a salvar o currículo atualizado.
   - Botão direto: **"Baixar Currículo em PDF"** apontando para o arquivo no repositório (`/assets/docs/curriculo-arthur-bergmann.pdf`).

7. **Seção de Contato e Conexões Profissionais:**
   - Mensagem de encerramento convidando para conexões profissionais e parcerias.
   - Links diretos e clicáveis:
     - **LinkedIn**
     - **E-mail**
     - **WhatsApp** (com mensagem inicial configurada)
     - **Instagram**

8. **Rodapé (Footer):**
   - © Arthur Bergmann de Oliveira — Todos os direitos reservados.
   - Menção sutil: *"Hospedado no GitHub Pages"*.

---

## 4. Requisitos Funcionais (RF)
- [ ] **RF01 - Navegação Fluida:** A barra de menu superior deve permitir navegar diretamente entre as seções da página com transição suave.
- [ ] **RF02 - Apresentação Pessoal e Foto:** Exibir a foto de perfil profissional com dimensionamento adequado e boa resolução.
- [ ] **RF03 - Catálogo Inicial de Projetos:** Apresentar os 3 projetos principais com descrição, tags e botões preparados para receber materiais futuros (com estado "Em breve" ou link configurável).
- [ ] **RF04 - Download Direto de Currículo:** Link direto e funcional para baixar o currículo em formato PDF.
- [ ] **RF05 - Canais de Contato:** Botões funcionais apontando para LinkedIn, WhatsApp (link `https://wa.me/...`), E-mail (`mailto:...`) e Instagram.
- [ ] **RF06 - Design Totalmente Responsivo:** Adaptação completa para smartphones, tablets e desktops de diferentes resoluções.

---

## 5. Requisitos Não Funcionais (RNF)
- **RNF01 - Compatibilidade Nativa com GitHub Pages:** O projeto deve ser composto estritamente por arquivos estáticos (`index.html`, arquivos de estilo e imagens/documentos locais).
- **RNF02 - Facilidade de Manutenção (Usuário Leigo):** O código HTML deve ser limpo e repleto de comentários explicativos em português (`<!-- FOTO DO PERFIL: Altere o link da imagem abaixo -->`), para que o próprio Arthur consiga atualizar dados sem depender de suporte técnico.
- **RNF03 - Velocidade e Otimização:** O site deve carregar em menos de 2 segundos, utilizando assets leves e fontes otimizadas.
- **RNF04 - Contraste e Acessibilidade:** Conformidade com padrões de contraste WCAG entre o azul marinho, turquesa, preto e branco para garantir leitura confortável.

---

## 6. Próximos Passos (Roteiro de Implementação)
1. **Etapa 1 (Concluída):** Elaboração dos arquivos de especificação ([`AGENTS.md`](file:///C:/Users/silbe/.gemini/antigravity/scratch/portfolio-administracao/AGENTS.md) e [`SPEC.md`](file:///C:/Users/silbe/.gemini/antigravity/scratch/portfolio-administracao/SPEC.md)).
2. **Etapa 2 (Validação do Usuário):** Leitura e aprovação da especificação pelo Arthur.
3. **Etapa 3 (Construção dos Arquivos):** Criação da estrutura de pastas (`/assets/css`, `/assets/images`, `/assets/docs`) e do `index.html` estático completo.
4. **Etapa 4 (Publicação):** Instruções passo a passo para envio ao GitHub e ativação do GitHub Pages.
