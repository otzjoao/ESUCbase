# Kit A.A.A.E.S.U.C — Catálogo Oficial 2024

Catálogo de produtos da Associação Atlética Acadêmica de Engenharia de Software.

## Estrutura do projeto

```
projeto_kit/
├── index.html         # Página principal
├── css/
│   └── style.css      # Todos os estilos
├── img/
│   ├── camisa_frente.png
│   ├── camisa_costas.png
│   ├── caneca_branca.jpg
│   ├── caneca_preta_verde.jpg
│   ├── caneca_preta_branca.jpg
│   ├── caneca_verde.jpg
│   ├── chaveiro.png
│   ├── carteirinha.jpg
│   ├── kit_completo.png
│   └── kit_vertical.png
└── README.md
```

## Como usar

Abra o `index.html` diretamente no navegador, ou use a extensão **Live Server** no VSCode para ver com reload automático.

## Como editar

### Trocar uma imagem
Substitua o arquivo na pasta `img/` mantendo o mesmo nome, ou atualize o atributo `src` no `index.html`.

### Adicionar um novo produto
Copie um bloco `.card` existente no `index.html` e ajuste o `src`, `alt`, e os textos dentro de `.card-info`.

### Mudar cores
Todas as cores estão centralizadas no `css/style.css`. As principais variáveis de cor usadas são:
- `#060c06` — fundo da página
- `#4CAF50` — verde destaque
- `#152615` — bordas e linhas
- `#d4ecd4` — texto principal
- `#2a5a2a` — texto secundário

### Alturas dos cards
Use as classes utilitárias `.h-160`, `.h-200`, `.h-240`, `.h-280`, `.h-300`, `.h-340`, `.h-380`, `.h-420` no elemento `<img>` para controlar a altura de cada imagem.

### Grids
- `.grid-2` — 2 colunas
- `.grid-3` — 3 colunas
- `.grid-4` — 4 colunas

Em telas menores que 900px, todos os grids viram 1 coluna automaticamente.

## Fontes

As fontes são carregadas via Google Fonts (requer internet):
- **Bebas Neue** — títulos e números
- **Barlow Condensed** — textos e labels
