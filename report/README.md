# Templates de Relatórios

Este repositório contém uma coleção de templates para relatórios académicos e técnicos, desenhados para facilitar o processo de documentação de projetos.

## 📂 Conteúdos do Repositório

O repositório está organizado em três categorias principais de templates:

---

### 1. LI4 Template

Estes templates foram desenvolvidos colaborativamente por docentes e alunos para a Unidade Curricular de **Engenharia de Software (LI4)** na **Universidade do Minho**. São ideais para projetos que exigem uma estrutura institucional rigorosa.

Disponível em três formatos:

- **LaTeX:** Para máxima precisão tipográfica e gestão automática de referências.
- **Typst:** Uma alternativa moderna e rápida ao LaTeX.
- **MS Word:** Para quem prefere um editor WYSIWYG tradicional.

🔍 [**Visualizar PDF de Exemplo**](previews/li4-report.pdf)

---

### 2. Template Simples

_Desenvolvido por: Eduardo Freitas Fernandes_

Um template minimalista em LaTeX e Typst focado na simplicidade e rapidez. É a escolha ideal para relatórios curtos, trabalhos laboratoriais ou entregas rápidas.

- **Destaques:** Layout limpo, exemplos básicos de tabelas e inserção de imagens.
- **Uso:** Projetos de pequena escala.

🔍 [**Visualizar PDF de Exemplo**](previews/simple-report.pdf)

---

### 3. Template Avançado LaTeX

_Desenvolvido por: Eduardo Freitas Fernandes_

Uma versão evoluída e rica em funcionalidades do template simples. Este template foi desenhado para relatórios de grande escala, projetos que exigem uma apresentação visual e técnica superior.

- **Destaques:** \* Gestão modular de ficheiros (`preamble`, `cover`, `report`).
- Diagramas vetoriais complexos com **TikZ**.
- Realce de sintaxe profissional para vários tipos de código (**Listings**).
- Estrutura dedicada para Referências Bibliográficas e Anexos.
- Hiperligações interativas e PDF metadata.

- **Uso:** Projetos complexos e extensos.

🔍 [**Visualizar PDF de Exemplo**](previews/custom-report.pdf)

---

## 🛠️ Como Utilizar

1. **Escolha o seu formato:** Navegue até ao ficheiro `.zip` correspondente ao template pretendido.
2. **Extraia os ficheiros:** Cada template contém a estrutura necessária para começar a escrever imediatamente.
3. **Compilação (LaTeX/Typst):** \* Para LaTeX, utilize o motor `lualatex` ou `xelatex`.

- Para Typst, utilize o comando `typst compile`.

## 📌 Requisitos

- Para os templates LaTeX, recomenda-se uma distribuição completa (TeX Live ou MiKTeX).
- Para o template Typst, deverá ter o compilador `typst` instalado ou utilizar o editor online.
