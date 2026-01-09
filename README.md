# Catecismo da Igreja Católica - Mapa Mental

Um projeto que apresenta o **Catecismo da Igreja Católica** em forma de **Mapa Mental interativo**, permitindo uma visualização clara e navegável da estrutura completa do catecismo.

## 📋 O que é este projeto?

Este repositório contém o sumário do Catecismo da Igreja Católica convertido em formato Markdown e estruturado como um mapa mental. Utilizando a ferramenta **MarkMap**, o arquivo Markdown é transformado em uma visualização interativa em HTML que facilita a exploração do conteúdo.

## 🗂️ Estrutura do Projeto

- **`Catecismo-pt-BR.md`** - Arquivo Markdown com o conteúdo do catecismo em português (Brasil)
- **`Catecismo-pt.md`** - Versão em português de Portugal
- **`Catecismo.html`** - Visualização em mapa mental (versão original)
- **`Catecismo-pt-BR.html`** - Visualização em mapa mental (português Brasil)
- **`CIC.js`** - Scripts personalizados
- **`.git/`** - Controle de versão Git

## 🚀 Como usar

### Pré-requisitos

- Node.js instalado
- npm (gerenciador de pacotes)

### Gerar os Mapas Mentais

Para gerar o arquivo HTML do mapa mental a partir do Markdown:

```bash
npx markmap-cli Catecismo-pt-BR.md -o Catecismo-pt-BR.html
```

Você também pode gerar para outras versões:

```bash
npx markmap-cli Catecismo-pt.md -o Catecismo-pt.html
npx markmap-cli Catecismo.md -o Catecismo.html
```

### Visualizar o Mapa Mental

Abra o arquivo `.html` gerado no seu navegador para explorar o mapa mental interativo:

```
Catecismo-pt-BR.html
```

## 📖 Sobre o Catecismo

O Catecismo da Igreja Católica é um documento oficial que presenta a doutrina da Igreja Católica de forma sistemática e completa, cobrindo:

- **Primeira Parte**: A profissão da fé (Credo)
- **Segunda Parte**: Os sacramentos da fé (Liturgia)
- **Terceira Parte**: A vida no Cristo (Moral)
- **Quarta Parte**: A oração cristã

## 🎨 Recursos do MarkMap

Os mapas mentais gerados oferecem:

- ✨ Visualização hierárquica interativa
- 🔍 Expansão e contração de nós
- 🎯 Navegação intuitiva pela estrutura
- 📱 Responsivo e adaptável a diferentes telas

## 📝 Estrutura do Mapa Mental

O mapa mental segue a divisão oficial do Catecismo:

```
Catecismo da Igreja Católica
├── Prólogo
├── Primeira Parte: A Profissão da Fé
├── Segunda Parte: Os Sacramentos da Fé
├── Terceira Parte: A Vida em Cristo
└── Quarta Parte: A Oração Cristã
```

## 🛠️ Personalização

Você pode editar os arquivos `.md` para:

- Adicionar anotações pessoais
- Ajustar a estrutura do mapa
- Adicionar links ou referências

Após fazer alterações, regenere os arquivos HTML com o comando mencionado acima.

## 📄 Licença

Este projeto utiliza o conteúdo do Catecismo da Igreja Católica, que é um documento oficial da Igreja Católica Romana.

## 🔗 Links Úteis

- [Catecismo da Igreja Católica - Vaticano](https://www.vatican.va/archive/ENG0015/_INDEX.HTM)
- [MarkMap - Ferramentas de Mapa Mental](https://markmap.js.org/)

---

**Criado para facilitar o estudo e exploração do Catecismo da Igreja Católica através de uma visualização moderna e interativa.**
