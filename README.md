Markdown
# Landing Page AGROVANT — Drone Agrícola

Projeto prático da unidade curricular de **Linguagem de Marcação**, do curso Técnico em Desenvolvimento de Sistemas — SESI/SENAI Itapeva.

## Identificação

| | |
|---|---|
| **Aluno** | Matheus Rodrigues Martins Costa |
| **Turma** | 2° Ano B (Desenvolvimento de Sistemas) |
| **Professor** | Rafael Ribas |
| **Entrega** | 17/08/2026 |

## Sobre o projeto

Landing page de apresentação do **AGROVANT**, um drone agrícola fictício voltado à pulverização e ao monitoramento de lavouras. O objetivo da página é convencer o agricultor a agendar uma demonstração do produto.

O layout foi construído a partir de um protótipo no Figma, com HTML semântico e CSS, sem frameworks.

Neste projeto, desenvolvi a estrutura completa do site da Agrovant utilizando HTML5 e CSS3, organizando a estilização através de variáveis no `:root` e layouts em Flexbox e CSS Grid. O maior desafio foi ajustar a sobreposição das mídias com o cabeçalho fixo e manter a responsividade fluida para telas menores sem quebrar as seções do site.

## Página publicada

**[agrovant-beta.vercel.app]**

## Estrutura de pastas
landing-page-drone/
├── index.html        página principal
├── README.md         este arquivo
├── css/
│   └── style.css     estilos do projeto
└── img/              imagens e vídeos

## Seções da página

- [x] Menu (cabeçalho)
- [x] Hero section
- [x] Especificações
- [x] Vídeo do produto
- [x] Cards de benefícios
- [x] Depoimentos
- [x] Formulário de contato

## Tecnologias e conceitos aplicados

- **HTML5 semântico** — `header`, `main`, `section`, `footer`
- **CSS3** com variáveis em `:root`
- **Flexbox e CSS Grid** para os layouts
- **Design responsivo** com abordagem *mobile first* e media queries
- **Unidades relativas** (`rem`, `%`) no lugar de medidas fixas

## Responsividade

A página foi construída começando pelo celular. O CSS base atende telas pequenas e as media queries acrescentam o comportamento das telas maiores, a partir de **768px**.

| Tela | Comportamento |
|---|---|
| Celular | A navegação do menu é ocultada para economizar espaço, os cards de benefícios e recursos empilham em coluna única e o formulário de contato ocupa toda a largura disponível. |
| Desktop | O menu de navegação fica visível no cabeçalho fixo, os cards de recursos são divididos em 3 colunas via CSS Grid e a seção de contato assume um layout lado a lado com as informações e o formulário. |

## Como rodar localmente

```bash
gh repo clone Matheus-3363/Agrovant
cd landing-page-drone

## Créditos

- Protótipo do layout: material da disciplina
- Imagens e vídeos: material fornecido pelo professor
- Fontes: [Roboto](https://fonts.google.com/specimen/Roboto) e
  [Inter](https://fonts.google.com/specimen/Inter), via Google Fonts
