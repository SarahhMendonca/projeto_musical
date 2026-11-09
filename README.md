# 🎵 Sistema Musical — Fase 1: Frontend (HTML5 & CSS3)

Este repositório contém a **Fase 1** do projeto **Sistema Musical**, voltada para o desenvolvimento do frontend estático da aplicação. O projeto contempla a estrutura semântica das telas e a estilização responsiva do sistema de gestão musical.

## 📌 Sobre o Projeto

A Fase 1 estabelece toda a interface visual e experiência do usuário (UI/UX) para o gerenciamento de artistas e acervo musical. O layout foi construído do zero utilizando HTML5 semântico e CSS3 puro (Flexbox e CSS Grid), sem a necessidade de frameworks externos.

### 🎯 Funcionalidades da Interface

* 🔐 **Tela de Autenticação:** Layout de login centralizado com dica visual de credenciais.
* 🎛️ **Painel / Menu Principal:** Navegação por cards responsivos para acesso às funcionalidades do sistema.
* 🎤 **Gerenciamento de Artistas:** Formulário de cadastro em grade (2 colunas) e tabela de exibição com ações de edição/exclusão.
* 🎵 **Cadastro de Músicas:** Formulário para inclusão de faixas vinculadas a um artista, suporte a links do YouTube, upload de capa e inclusão de letra.
* 🎼 **Biblioteca Musical:** Visualização completa do acervo com barra de filtros dinâmicos por artista, gênero e busca geral.

## 📂 Estrutura de Arquivos

```text
sistema-musical/
├── styles.css               # Folha de estilos principal (design system único)
├── login.html               # Tela de login / autenticação
├── index.html               # Menu principal de navegação
├── cadastro_artista.html    # Cadastro e listagem de artistas
├── cadastro_musica.html     # Cadastro e listagem de músicas
└── listagem_musicas.html    # Biblioteca musical com filtros
```

## 🎨 Destaques da Estilização (CSS)

* **Variáveis CSS (`:root`):** Padronização de cores primárias, estados de botões (*hover*, *focus*), espaçamentos e sombras.
* **Design Responsivo (`@media`):** Adaptação completa para dispositivos móveis (até 768px), ajustando tabelas com rolagem horizontal e formulários em coluna única.
* **Micro-interações:** Efeitos visuais suaves em botões e animações nos cards do menu principal.

## 💻 Como Executar o Projeto

Como a **Fase 1** contempla apenas o frontend estático:

1. Clone este repositório ou baixe os arquivos em seu computador:
   ```bash
   git clone https://github.com/seu-usuario/sistema-musical.git
   ```
2. Abra a pasta do projeto.
3. Clique duas vezes no arquivo `login.html` (ou abra-o em qualquer navegador de sua preferência).

## 🛠️ Tecnologias Utilizadas

* **HTML** — Estruturação semântica das páginas.
* **CSS** — Estilização, variáveis de tema, Flexbox, CSS Grid e media queries.
* **VS Code** — Editor de código utilizado no desenvolvimento.
