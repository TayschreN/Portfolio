# Portfolio

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![No Frameworks](https://img.shields.io/badge/frameworks-none-2451CC?style=flat)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?style=flat&logo=githubpages&logoColor=white)

Portfólio pessoal de **Gabriel França da Silva** — estudante de Ciência e Tecnologia (UFABC) em transição de análise de dados para engenharia de dados.

**[→ Ver site ao vivo](https://tayschren.github.io/Portfolio/)**

| Hero | Projetos |
|---|---|
| ![Hero](imagens/tela1.png) | ![Projetos](imagens/tela2.png) |

| Sobre | Formação |
|---|---|
| ![Sobre](imagens/tela3.png) | ![Formação](imagens/tela4.png) |

## Sobre

Catálogo dos meus projetos de dados — engenharia, análise, dashboards e SQL — com certificações, formação acadêmica e currículo. Tudo em um único HTML estático, sem frameworks e sem build.

## Funcionalidades

- **Catálogo filtrável** — projetos organizados em 4 categorias: Engenharia de Dados, Python/EDA/ML, SQL, BI & Dashboards
- **Links diretos** — cada card aponta para o repositório no GitHub e para o dashboard publicado (quando disponível)
- **Seções complementares** — certificações com carga horária, timeline acadêmica e contato
- **Currículo em PDF** — download direto no header e no rodapé
- **Acessível** — skip link, foco visível, respeita `prefers-reduced-motion`
- **Responsivo** — adapta-se de mobile a desktop sem media queries complexas

## Stack

| Camada | Tecnologia |
|---|---|
| Marcação | HTML5 semântico |
| Estilo | CSS3 (variáveis nativas, Grid, Flexbox) |
| Lógica | JavaScript vanilla (ES6+) |
| Fontes | Inter + IBM Plex Mono (Google Fonts) |
| Hospedagem | GitHub Pages |

## Estrutura

```
├── index.html                            # markup, estilos e script (arquivo único)
├── imagens/                              # screenshots do site
│   ├── tela1.png
│   ├── tela2.png
│   ├── tela3.png
│   └── tela4.png
├── curriculo-gabriel-franca-silva.pdf
└── README.md
```

## Rodar localmente

```bash
git clone https://github.com/TayschreN/Portfolio.git
cd Portfolio
start index.html   # Windows ·双击/double-click no arquivo
```

## Arquitetura

Projetos e certificações são declarados em dois arrays JavaScript (`PROJECTS` e `CERTIFICATIONS`) no início da tag `<script>`. A interface (cards, filtros, contadores) é renderizada dinamicamente a partir desses dados — adicionar, remover ou reordenar conteúdo não exige alterar HTML ou CSS. O esquema de cada campo está documentado em comentários no código-fonte.

## Contato

- **LinkedIn**: [linkedin.com/in/gabrielfranca123](https://www.linkedin.com/in/gabrielfranca123/)
- **GitHub**: [github.com/TayschreN](https://github.com/TayschreN)
- **Email**: [gabriel.fsilva26609@gmail.com](mailto:gabriel.fsilva26609@gmail.com)

---

Desenvolvido por Gabriel França da Silva.