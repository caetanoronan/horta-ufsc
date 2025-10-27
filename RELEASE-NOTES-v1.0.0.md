# v1.0.0 — Horta Comunitária UFSC

Data: 2025-10-27
Tag: v1.0.0
Página: https://caetanoronan.github.io/horta-ufsc
Repositório: https://github.com/caetanoronan/horta-ufsc

## Resumo (PT)
Primeira versão pública do site da Horta Comunitária UFSC. Esta release reúne o guia, documentação e funcionalidades para navegação, acessibilidade, impressão e exportação de dados, em português e espanhol.

### Destaques
- Tema claro/escuro com persistência e ícones dinâmicos.
- Site bilíngue (PT/ES) com engine de i18n (texto e atributos ARIA).
- Seção Cronograma (12 semanas) com tradução completa.
- Seção Materiais dinâmica:
  - Carrega MATERIAIS.csv, filtra por categoria e renderiza tabela.
  - Download de CSV no idioma atual (PT/ES), CSV “PT original” e CSV “colunas visíveis”.
  - Controles para ocultar/mostrar colunas e botão de impressão.
- Impressão/PDF com cabeçalho automático (título, descrição e data) e layout limpo.
- Acessibilidade: aria-current no link ativo, foco visível, melhor contraste no modo escuro.
- Música de fundo com controle fixo.

### Arquivos principais
- index.html — SPA com navegação, tema, i18n, Cronograma, Materiais e impressão.
- MATERIAIS.csv — fonte de dados (PT) para a seção Materiais.
- ORCAMENTO.md, CRONOGRAMA-RESUMO.md — materiais complementares.

### Como imprimir/baixar
- Impressão/PDF: botão “Imprimir / Salvar PDF” em Materiais e Cronograma.
- CSV: “Baixar/Descargar CSV (PT/ES)”, “CSV (PT original)” e “CSV (colunas visíveis)”.

---

## Resumen (ES)
Primera versión pública del sitio de la Huerta Comunitaria UFSC. Esta versión reúne la guía, documentación y funcionalidades de navegación, accesibilidad, impresión y exportación de datos, en portugués y español.

### Destacados
- Tema claro/oscuro con persistencia e íconos dinámicos.
- Sitio bilingüe (PT/ES) con motor de i18n (texto y atributos ARIA).
- Sección Cronograma (12 semanas) con traducción completa.
- Sección Materiales dinámica:
  - Carga MATERIAIS.csv, filtra por categoría y renderiza la tabla.
  - Descarga de CSV en el idioma actual (PT/ES), CSV “PT original” y CSV “columnas visibles”.
  - Controles para ocultar/mostrar columnas y botón de impresión.
- Impresión/PDF con encabezado automático (título, descripción y fecha) y diseño limpio.
- Accesibilidad: aria-current en el enlace activo, foco visible, mejor contraste en modo oscuro.
- Música de fondo con control fijo.

### Archivos principales
- index.html — SPA con navegación, tema, i18n, Cronograma, Materiales e impresión.
- MATERIAIS.csv — fuente de datos (PT) para la sección Materiales.
- ORCAMENTO.md, CRONOGRAMA-RESUMO.md — materiales complementarios.

### Cómo imprimir/descargar
- Impresión/PDF: botón “Imprimir / Guardar PDF” en Materiales y Cronograma.
- CSV: “Descargar CSV (PT/ES)”, “CSV (PT original)” y “CSV (columnas visibles)”.

---

## Créditos
- Autoria: Ronan Armando Caetano, José Carlos Martini Filho.
- Disciplina: BIO7247 — Introdução/Introducción à la Extensão Universitária (2025/2).
- Assistência: GitHub Copilot (IA).

## Próximos passos (sugestões)
- Página de impressão dedicada com opções avançadas.
- Acessibilidade adicional (foco por teclado nas seções/tabindex refinado).
- Exportação PDF direta da tabela de materiais (client-side) com formatação.
