#  Mapa Cultural de Boa Viagem 🗺️

![Status do Projeto](https://img.shields.io/badge/status-front--end%20concluído-brightgreen)

Plataforma web front-end projetada para mapear, centralizar e divulgar a rica cena cultural da cidade de Boa Viagem, Ceará.

---

### Índice

- [Sobre o Projeto](#sobre-o-projeto-📖)
- [Recursos Principais](#recursos-principais-✨)
- [Demonstração Visual](#demonstração-visual-📸)
- [Tecnologias Utilizadas](#tecnologias-utilizadas-🚀)
- [Como Executar o Projeto](#como-executar-o-projeto-▶️)
- [Planos Futuros](#planos-futuros-🔮)

---

### Sobre o Projeto 📖

O **Mapa Cultural de Boa Viagem** nasceu como um projeto de portfólio para demonstrar a construção de uma interface web completa, moderna e responsiva utilizando apenas **HTML5 e CSS3**. O objetivo é criar uma ferramenta funcional e visualmente agradável para artistas, produtores e para o público em geral, facilitando o acesso a informações sobre a cultura da região.

O projeto inclui tanto a parte pública do site (o que os visitantes veem) quanto o design de um painel administrativo (a área para gerenciamento de conteúdo).

---

### Recursos Principais ✨

O front-end conta com diversas telas e componentes, incluindo:

* **Página Inicial (`index.html`):**
    * Hero section com imagem de fundo e barra de busca.
    * Grid de cards para navegação por categorias (Agentes, Eventos, Espaços, etc.).
    * Seção de "Destaques" com abas e scroll horizontal.

* **Páginas de Listagem (`agentes.html`, `eventos.html`, etc.):**
    * Layout padronizado com cabeçalho, filtros de busca avançados e grade de resultados.
    * Cards de conteúdo com design consistente.
    * Componente de paginação.

* **Página de Detalhes (`evento-detalhe.html`):**
    * Layout de duas colunas com banner, galeria, descrição detalhada e informações rápidas.
    * Mapa de localização integrado.

* **Painel Administrativo (a "área do cliente"):**
    * **Dashboard (`admin.html`):** Tela principal com widgets de estatísticas, botões de ação e tabela de conteúdo recente.
    * **Página de Perfil (`perfil.html`):** Formulário completo para o usuário editar suas informações.
    * Design responsivo com menu lateral que se adapta a telas menores.

* **Painel de Dados (`relatorios.html`):**
    * Página com visualizações de dados, simulando gráficos e tabelas de um painel de BI.

---

### Demonstração Visual 📸

| Página Inicial | Página de Listagem |
| :---: | :---: |
| <img width="1360" height="768" alt="Captura de tela da Página Inicial" src="https://github.com/user-attachments/assets/3fd98b52-01b7-4872-b168-bbc1462cbc40"> | <img width="1360" height="768" alt="Captura de tela da Página de Listagem de Agentes" src="https://github.com/user-attachments/assets/a6db8fc2-8c96-4e82-a82a-1321eb28cce6"> |

| Detalhe do Evento | Painel Administrativo |
| :---: | :---: |
| <img width="1360" height="768" alt="Captura de tela da Página de Detalhe do Evento" src="https://github.com/user-attachments/assets/17e859ab-7551-48dc-b204-d5076dd3bb5d"> |<img width="1360" height="768" alt="Captura de tela do Painel Administrativo" src="https://github.com/user-attachments/assets/50d3bb90-c931-426f-81f3-93d8854d1977"> |

**[➡️ Ver demonstração ao vivo](https://mapa-cultural-boa-viagem.vercel.app/)**

---

### Tecnologias Utilizadas 🚀

Todo o projeto foi construído do zero com foco nos fundamentos do desenvolvimento web:

* **HTML5:** Estruturação semântica do conteúdo.
* **CSS3:** Estilização completa, utilizando recursos modernos como:
    * Flexbox
    * Grid Layout
    * Animações e Transições
    * Media Queries para responsividade total.
* **AOS.js:** Uma biblioteca leve para animações de scroll.

---

### Como Executar o Projeto ▶️

Por ser um projeto front-end estático, não há necessidade de instalação de dependências.

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
    ```
2.  Abra o arquivo `index.html` no seu navegador de preferência.

---

### Planos Futuros 🔮

Este projeto serve como uma base sólida de front-end. Os próximos passos para torná-lo uma aplicação completa seriam:

-   [ ] **Implementação do Back-end:** Criar a lógica do servidor (usando Node.js, Python, etc.) para gerenciar usuários e conteúdo.
-   [ ] **Conexão com Banco de Dados:** Salvar e consultar todas as informações em um banco de dados (como PostgreSQL, MongoDB).
-   [ ] **Funcionalidades com JavaScript:** Tornar os formulários, login, filtros e o carrossel (que planejamos) totalmente funcionais.

---

Feito por **Marcelo Albuquerque**
