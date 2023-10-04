# eletronica-digital
Eletrônica Digital

## Criar arquivos de requisitos

No arquivo `requirements.txt`, coloque o seguinte conteúdo:

```
mkdocs
mkdocs-material
```

## Instalação dos requisitos

No terminal (Ctrl+J), digite o comando: `pip3 install -r requirements.txt`


## Criação de novo projeto

Execute: `mkdocs`

Observe a saída do comando.

Execute: `mkdocs new`

Observe a saída do comando.

Execute: `mkdocs new .`

## Execução do servidor de teste

Execute: `mkdocs serve`

Clique no botão "Open in browser" que aparecerá no canto inferior direito.

## Personalização do site

Pesquise no Google por [material mkdocs.yml](https://google.com/search?q=material+mkdocs.yml) e veja os exemplos.

## Criação de novas páginas

Vá ao diretório [/docs](/docs/) e crie arquivos Markdown (Extensão `.md`).


## Visualização dos arquivos novos e alterados, e adição deles

- `git status`
- `git add .`
- `git status`


## Registro das mudanças e sincronização com repositório remoto (GitHub)

- `git commit -m "MENSAGEM"`
- `git status`

Escolha uma mensagem relevante.

- `git push`

## Publicação do site

- `mkdocs`

Veja qual é o subcomando do MkDocs para publicar no GitHub, execute-o e siga as instruções (TV! Te vira!).

Não conseguiu? Pois então [veja essa pequena ajuda](ajuda-publicacao-github.md).

## Aprendendo mais sobre Markdown

Veja:

1. [Guia básico de Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)
1. [Markdown Help -- em inglês](https://commonmark.org/help/)
2. [Markdown Tutorial -- em inglês](https://commonmark.org/help/tutorial/)

## Diagramas

Você já ouviu falar do Mermaid JS?

Não. Pois veja:

1. [Mermaid JS Cheat Sheet](https://jojozhuang.github.io/tutorial/mermaid-cheat-sheet/)
1. [Mermaid JS live](https://mermaid.live/)

Para habilitar os diagramas Mermaid em seu site:

1. Adicione uma linha com `mkdocs-mermaid2-plugin` no arquivo [requirements.txt](requirements.txt);
1. Instale os novos requisitos. Vá ao terminal e execute: `pip3 install -U -r requirements.txt`
1. Edite o arquivo [mkdocs.yml](mkdocs.yml) e acrescente as seguintes linhas:

```
plugins:
    - search
    - mermaid2
```

Depois [execute o servidor de teste](#execu%C3%A7%C3%A3o-do-servidor-de-teste) e refaça os outros passos (Adição, publicação e etc.).
