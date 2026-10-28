# Site Patas Amigas

Homepage de uma associação de adoção de animais do Porto, feita como **exercício de consolidação de HTML e CSS**.

O objetivo foi replicar a página do modelo (`modelo.png`), usando HTML semântico e CSS num ficheiro externo, sem estilos inline.

---
**Tutor:** Francisco Perez

---
**Autor:** Egwaldino Cassuente

---
**Repositório:** [github.com/egwaldino/site-patas-amigas](https://github.com/egwaldino/site-patas-amigas)

---

## Visualização

**Site online:** [egwaldino.github.io/site-patas-amigas](https://egwaldino.github.io/site-patas-amigas/)

---

## Estrutura do projeto

```
SitePatasAmigas/
├── assets/
│   └── img/                      # imagens dos animais (cao.svg, gato.svg, coelho.svg)
├── css/
│   ├── style.css                 # estilos da página principal
│   └── paginaEmConstrucao.css    # estilos da página de aviso
├── html/
│   └── paginaEmConstrucao.html   # página de "em construção"
├── index.html                # página principal
└── README.md
```

> **Nota:** o enunciado pede `index.html` na raiz, `css/` e `img/`. Organizei os ficheiros em pastas `html/` e `assets/` para manter o projeto mais arrumado. Os caminhos dos `<link>` e das imagens foram ajustados para esta estrutura.

---

## Como abrir

1. Clona o repositório:
   ```bash
   git clone https://github.com/egwaldino/site-patas-amigas.git
   ```
2. Abre o ficheiro `index.html` no navegador.
   Também podes usar a extensão **Live Server** do VS Code.

---

## Requisitos do enunciado

### Parte 1. Estrutura HTML

- [x] Uso de `header`, `nav`, `main`, `section`, `article` e `footer`
- [x] Menu em `ul` com quatro links para as secções (`#animais`, `#adotar`, `#visitas`, `#contacto`)
- [x] Um único `h1`, títulos de secção em `h2` e nomes dos animais em `h3`
- [x] Imagens com `alt` que descreve cada animal
- [x] Secção "Como adotar" com lista numerada (`ol`)
- [x] Horário de visitas numa tabela com `thead` e `tbody`
- [x] Formulário com `label` ligados aos campos (`for` / `id`), nome e email obrigatórios, `select` com os três animais, `textarea` e botão

### Parte 2. CSS

| Elemento | O que foi feito |
|---|---|
| Página | Arial com alternativas, texto `#1d1148`, fundo `#f7f7f9`, `line-height: 1.6` |
| body | `padding: 0` e removido bordas padrão do navegador `margin: 0` |
| Cabeçalho | Fundo branco, logótipo à esquerda ("Amigas" em `#e40084`), menu à direita com flexbox |
| Destaque | Fundo `#1d1148`, texto branco e centrado, botão `#e40084` |
| Cartões | `box-sizing: border-box`, 300px de largura, `padding: 16px`, borda de 3px `#1d1148`, `border-radius: 20px`, sombra suave, lado a lado com flexbox e `gap: 24px` |
| Tabela | `max-width: 500px`, cabeçalho com fundo `#1d1148`, células com borda de 1px |
| Formulário | Fundo branco, cantos arredondados, campos com largura total |
| Rodapé | Fundo `#1d1148`, texto branco e centrado |

### Parte 3. Desafios

- [x] Links do menu e botões mudam de cor com `:hover` (`#b8006a` nos botões)
- [x] Selo "Novo" no canto superior direito do cartão do Rex, com `position: absolute` dentro de um cartão com `position: relative`
- [x] Em ecrãs estreitos, o menu e os cartões passam para a linha de baixo com `flex-wrap`, sem scroll horizontal

### Verificação final

- [x] Na DevTools (F12), cada cartão mede 300px de largura
- [x] `commit` e `push` feitos para o GitHub

---

## Extra

Além do que foi pedido, criei uma **página "Em construção"** (`html/paginaEmConstrucao.html`), com o seu próprio CSS, para os links que ainda não têm conteúdo.

---

## Tecnologias

- HTML5
- CSS3 (Flexbox)
- Git e GitHub

---

## O que aprendi

- Estruturar uma página com tags semânticas
- Ligar `label` e campos de formulário para melhorar a acessibilidade
- Usar Flexbox para alinhar o cabeçalho e os cartões, e `flex-wrap` para ecrãs pequenos
- Posicionar elementos com `position: relative` e `absolute`
- Entender o efeito do `box-sizing: border-box` na largura dos elementos

---

© 2026 Egwaldino Cassuente. Exercício realizado para fins de aprendizagem.