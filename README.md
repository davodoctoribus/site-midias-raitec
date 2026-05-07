# RAITec — Site Institucional

Projeto desenvolvido por trainees no processo seletivo do **RAITEC** (Robótica, Automação, Inteligência Artificial e Tecnologia), grupo de extensão da Universidade Federal do Ceará.

---

## Estrutura

```
/
├── home.html              Página inicial com hero, notícias e rodapé
├── projetos.html          Página do eixo de Inovação, projetos e integrantes
├── estilo_home.css        Estilos da página inicial
├── estilo_projetos.css    Estilos da página de projetos
└── src/
    ├── logo.png
    ├── logo2.png
    ├── raitec.png
    ├── noticia1.png
    ├── noticia2.png
    ├── logo_inovacao.png
    ├── BB8.png
    ├── painel_solar.png
    ├── gameboy.png
    └── track-webfont/     Fonte customizada Track
```

---

## Implementaçoes

- HTML5 e CSS3 puro, sem frameworks
- Fontes: **Track** (local), **Cairo**, **Ubuntu** via Google Fonts
- Ícones: Font Awesome 6
- Responsivo a partir de `900px` com menu mobile animado
- Encaminhar para o site do dtec no github pages.

---

## Padrão visual

| Elemento       | Fonte    |
|----------------|----------|
| Títulos h1, h2 | Track → Ubuntu (fallback) |
| Subtítulos h3, h4 | Ubuntu |
| Textos e links | Cairo |
| Nav            | Ubuntu |

Cor principal: `#05053f` — Azul escuro institucional  
Cor de destaque: `#09CCCC` — Ciano

---

## Como rodar

Basta abrir `home.html` em qualquer navegador. Não há dependências externas além das fontes carregadas via CDN.

Disponivel tambem no GitHub pages: https://davodoctoribus.github.io/site-midias-raitec/home.html