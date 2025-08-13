# 🎨 Projeto de Ícones

![Adobe Illustrator](https://img.shields.io/badge/Made%20with-Adobe%20Illustrator-FF9A00?logo=adobeillustrator&logoColor=white&style=for-the-badge)

Conjunto de ícones originais desenvolvidos no **Adobe Illustrator**. O objetivo é oferecer um sistema visual consistente para apps, web e materiais impressos.

---

## 📁 Estrutura do Repositório

```markdown
icons/                     # Ícones finais (SVG/PNG), organizados por categoria
  ├─ frameworks/           # Engrenagens (Frameworks)
  ├─ bibliotecas/          # Livros (Bibliotecas)
  ├─ linguagens/           # Quebra-cabeças (Linguagens)
  ├─ bancos/               # "BD" (Bancos de dados)
  └─ ferramentas/          # Ícones redondos (Ferramentas)
source/                    # Arquivos .ai originais, mesmos subdiretórios de "icons/"
preview/                   # Imagens de pré-visualização (PNG/JPG)
LICENSE
README.md
palette.ai                 # Paleta de cores base (opcional)
```
---

## 🧭 Categorias & Legenda Visual

Para facilitar identificação rápida, cada categoria usa um **formato de ícone** específico:

- ⚙️ **Engrenagens = Frameworks**  
  Exemplos: Angular, Vue, .NET, Spring.

- 📚 **Livros = Bibliotecas**  
  Exemplos: Redux, Lodash, NumPy.

- 🧩 **Quebra-cabeças = Linguagens**  
  Exemplos: JavaScript, Python, C#, Go.

- 🗄️ **BD = Bancos de Dados**  
  Exemplos: PostgreSQL, MySQL, MongoDB.

- 🔵 **Ícones redondos = Ferramentas**  
  Exemplos: VS Code, Docker, Git, Figma.

> A forma do ícone comunica a categoria **sem depender do texto**.  
> Assim, a identidade visual fica clara mesmo em tamanhos pequenos.

---

## 📐 Especificações de Design

- **Formato principal:** SVG (otimizado para web, responsivo)  
- **Exportação complementar:** PNG (256, 512, 1024 px, fundo transparente)  
- **Dimensão base de desenho:** 512 × 512 px (artboard)  
- **Grid:** 8 px (elementos alinhados ao grid, margens 32 px)  
- **Traço:** 2 px (equivalente proporcional ao 512 px)  
- **Estilo:** Flat/Sem skeuomorfismo; uso moderado de cantos arredondados  
- **Paleta:** definida em `palette.ai` (cores nomeadas e documentadas)

---

## 🧱 Convenções de Nomes

- Arquivos **SVG/PNG**: `categoria-nome.svg`  
  Exemplos:
  - `frameworks-angular.svg`
  - `bibliotecas-redux.svg`
  - `linguagens-javascript.svg`
  - `bancos-postgresql.svg`
  - `ferramentas-docker.svg`

- Artboards no Illustrator: 1 artboard por ícone, nome igual ao arquivo.

---

## 🚀 Como Usar

1. **Baixe** o arquivo desejado na pasta `icons/<categoria>/`.
2. **Importe** no seu projeto (HTML, React, Android, iOS, etc).
3. **Personalize** cores alterando `fill`/`stroke` no SVG (quando aplicável).

Exemplo (inline SVG em HTML):

```html
<!-- Exemplo com um ícone de linguagem -->
<svg class="icon" aria-label="JavaScript" role="img"> ... </svg>

<style>
  .icon { width: 32px; height: 32px; }
  /* Personalização de cor quando o SVG usa currentColor */
  .icon { color: #f7df1e; }
</style>
```

## 🖼️ Pré-visualização (exemplos)

| Categoria       | Ícone (preview)                      | Arquivo                                 |
|----------------|---------------------------------------|------------------------------------------|
| Frameworks     | ![Angular](preview/frameworks/angular.png)         | `icons/frameworks/frameworks-angular.svg` |
| Bibliotecas    | ![Redux](preview/bibliotecas/redux.png)            | `icons/bibliotecas/bibliotecas-redux.svg` |
| Linguagens     | ![JavaScript](preview/linguagens/javascript.png)   | `icons/linguagens/linguagens-javascript.svg` |
| Bancos         | ![PostgreSQL](preview/bancos/postgresql.png)       | `icons/bancos/bancos-postgresql.svg`     |
| Ferramentas    | ![Docker](preview/ferramentas/docker.png)          | `icons/ferramentas/ferramentas-docker.svg` |

> Substitua as imagens e caminhos acima pelos seus arquivos reais em `preview/` e `icons/`.

---

## 🧪 Qualidade & Otimização

- Remover metadados e `title/desc` redundantes no SVG (manter acessíveis se úteis).
- Usar `currentColor` quando fizer sentido para permitir troca de cor via CSS.
- Minimizar paths (Pathfinder/Unite e Simplify) para reduzir tamanho de arquivo.
- Validar contraste de cores em fundos claros e escuros.

---

## 🤝 Contribuição

---

## 📜 Licença

Licença **MIT** (ver arquivo `LICENSE`).  
Sinta-se livre para usar e modificar, mantendo os créditos.

---

### ✏️ Autor

Criado no **Adobe Illustrator** por **Amaro Netto**.
