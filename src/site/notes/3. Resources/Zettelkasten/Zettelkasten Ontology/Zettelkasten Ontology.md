---
{"dg-publish":true,"permalink":"/3-resources/zettelkasten/zettelkasten-ontology/zettelkasten-ontology/","tags":["type/structure","structure/ontology","theme/zettelkasten","target/zettelkasten"],"dg-note-properties":{"tags":["type/structure","structure/ontology","theme/zettelkasten","target/zettelkasten"],"aliases":["Zettelkasten Ontology","Ontologia Zettelkasten"],"created":"2026-08-26","modified":"2026-08-26","banner":"![[3. Resources/Zettelkasten/Visuals/Zettelkasten_Ontology.png]]","lead":"A Ontologia Zettelkasten define as 5 camadas de notas, propriedades de frontmatter, taxonomia de tags e regras de hiperlinks.","template_type":"Structure"}}
---


# 🏗️ Zettelkasten Ontology (Ontologia & Taxonomia)

[[3. Resources/Zettelkasten/00_Zettelkasten_Hub\|Hub Zettelkasten]] | [[3. Resources/Zettelkasten/Literature Map/Literature Map\|Mapa de Literatura]] | [[3. Resources/Zettelkasten/Views/ARCO View\|ARCO]] | [[3. Resources/Zettelkasten/Views/Inspect View\|Inspect]]

> [!ABSTRACT] **Definição / Definition**
> Um Zettelkasten é um sistema de gestão de conhecimento pessoal composto por cinco elementos fundamentais: **notas, links, metadados, estruturas e processos**.
> A Ontologia define como esses elementos interagem e se organizam em 5 camadas principais.

---

## 📸 Diagrama da Ontologia Zettelkasten

![Zettelkasten_Ontology.png](/img/user/3.%20Resources/Zettelkasten/Visuals/Zettelkasten_Ontology.png)

---

## 🏛️ As 5 Camadas da Ontologia (The 5 Layers)

### 1️⃣ Camada 1: Fleeting Notes (Notas Rápida / Captura)
- **Função**: Ideias temporárias, pensamentos rápidos, notas de reuniões de rascunho.
- **Correspondência LifeOS**: `-1. Capture`
- **Guia**: [[3. Resources/Zettelkasten/Guides/1_Fleeting Notes Guide\|Guia Fleeting Notes]]
- **Regra**: Devem ser revisadas e processadas periodicamente (descartadas ou convertidas em Literature/Permanent Notes).

### 2️⃣ Camada 2: Literature Notes (Notas de Literatura)
- **Função**: Resumos de livros, artigos, podcasts, citações (`#type/quote`), termos (`#type/term`), pessoas (`#type/person`), ferramentas (`#type/tool`).
- **Correspondência LifeOS**: `3. Resources/Literature`
- **Guia**: [[3. Resources/Zettelkasten/Guides/2_Literature Notes Guide\|Guia Literature Notes]]
- **Regra**: Escritas no contexto da fonte original, sempre vinculadas via `based_on:: [[Fonte]]`.

### 3️⃣ Camada 3: Permanent Notes (Notas Permanentes)
- **Função**: Insights atômicos (`#type/note`), perguntas (`#type/question`), prompts (`#type/prompt`), sketchnotes (`#type/sketchnote`).
- **Correspondência LifeOS**: `3. Resources/Permanent`
- **Guia**: [[3. Resources/Zettelkasten/Guides/3_Permanent Notes Guide\|Guia Permanent Notes]]
- **Regras Principais**:
  1. **Atomicidade**: Uma ideia por nota.
  2. **Autonomia**: Escritas com suas próprias palavras, compreensíveis por si sós.
  3. **Reusabilidade**: Conectadas hipertextualmente a outras notas.

### 4️⃣ Camada 4: Project Notes (Notas de Projeto)
- **Função**: Tarefas atreladas a metas com prazos, rascunhos de e-books, artigos e publicações.
- **Correspondência LifeOS**: `1. Projects` / `5. Express`
- **Guia**: [[3. Resources/Zettelkasten/Guides/4_Project Notes Guide\|Guia Project Notes]]

### 5️⃣ Camada 5: Structure Notes (Notas de Estrutura)
- **Função**: Mapas de Conteúdo (MOCs), Índices, Dashboards ARCO/Inspect e Canvases.
- **Correspondência LifeOS**: `3. Resources/Zettelkasten`
- **Guia**: [[3. Resources/Zettelkasten/Guides/5_Structure Notes Guide\|Guia Structure Notes]]

---

## 🏷️ Taxonomia de Tags (Tag System)

A arquitetura Zettelkasten utiliza tags estruturadas em namespaces:

- `#type/*` — Define a classe de nota (ex: `#type/note`, `#type/book`, `#type/quote`, `#type/term`, `#type/structure`, `#type/question`).
- `#theme/*` — Define a área temática (ex: `#theme/zettelkasten`, `#theme/productivity`, `#theme/philosophy`).
- `#structure/*` — Utilizado para notas de estrutura (ex: `#structure/moc`, `#structure/index`, `#structure/view`).
- `#target/*` — Define a meta de saída da nota (ex: `#target/project`, `#target/github`, `#target/article`).

---

## 📋 Propriedades Frontmatter Padrão

```yaml
---
created: YYYY-MM-DD
modified: YYYY-MM-DD
tags:
  - type/note
  - theme/zettelkasten
aliases: []
lead: "Resumo em 1-3 frases sobre o núcleo da ideia da nota."
template_type: Permanent
template_version: "1.0"
---
```

---

## 📊 Diagramas de Modelos de Suporte

### Diagrama de Classes Zettelkasten (UML)
![Zettelkasten_Class_Diagram_2025-04-26.png](/img/user/3.%20Resources/Zettelkasten/Visuals/Zettelkasten_Class_Diagram_2025-04-26.png)

### Modelo de Maturidade (Maturity Model)
![zettelkasten_maturity_2024-11-18.png](/img/user/3.%20Resources/Zettelkasten/Visuals/zettelkasten_maturity_2024-11-18.png)

---

## 🎨 Canvases da Ontologia

- `![[Zettelkasten Ontology.canvas|Ontology Canvas]]`
- `![[How to Use Links with Templates.canvas|Linking Rules Canvas]]`

---
*Retornar ao [[3. Resources/Zettelkasten/00_Zettelkasten_Hub\|Hub Zettelkasten]]*
