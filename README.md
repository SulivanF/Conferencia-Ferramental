# 🛠️ Relatório de Conferência de Ferramental

Sistema web moderno e responsivo desenvolvido para o controle, checagem e emissão de relatórios de ferramentas, equipamentos e veículos da equipe técnica. O projeto conta com suporte integrado para preenchimento de campos, seleção de status, descrição de pendências e **assinatura digital interativa**, permitindo salvar e exportar o documento em PDF de forma limpa e profissional.

---

## 🎨 Principais Funcionalidades

- **Layout Moderno & Elegante:** Interface em modo escuro com paleta de cores refinada (tons de bordô/vinho profissional) que evita o cansaço visual.
- **Tabela Dinâmica de Ferramentas:** Relação completa de itens e equipamentos com seletor de status (*OK, Danificado, Manutenção*) e controle de quantidade.
- **Parecer e Pendências:** Seção dedicada para registrar o diagnóstico geral da conferência e detalhar eventuais ocorrências.
- **Assinatura Digital Múltipla:** Blocos dedicados com suporte a *canvas* (para desenho via mouse ou telas touch) para assinatura de até dois técnicos e do responsável.
- **Otimizado para Impressão / PDF:** Folha de estilos personalizada (`@media print`) que oculta botões interativos e garante que todo o parecer final e as assinaturas fiquem perfeitamente alinhados e agrupados na mesma página.

---

## 🚀 Como Utilizar

Como se trata de uma aplicação puramente front-end (HTML5, CSS3 e JavaScript nativo), você não precisa instalar nenhum servidor ou dependência complexa.

1. Faça o download ou clone este repositório.
2. Abra o arquivo **`index.html`** diretamente em qualquer navegador web moderno (Google Chrome, Microsoft Edge, Firefox, etc.).
3. Preencha os campos do relatório, interaja com os seletores, desenhe as assinaturas nos quadros correspondentes e clique no botão **"Salvar / Imprimir PDF"**.

---

## 📁 Estrutura do Projeto

```text
📦 Conferencia-Ferramental
 ┗ 📜 index.html  # Arquivo único contendo estrutura, estilos e lógica
