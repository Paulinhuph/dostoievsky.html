# Arquivo Dostoiévski

Projeto estático em HTML5 e CSS3 inspirado em uma landing page institucional e literária sobre Fiódor Dostoiévski. A proposta visual busca um tom editorial, sóbrio e dramático, com predominância de preto, azul-marinho profundo e vermelho intenso.

## Visão geral

O projeto foi organizado para abrir diretamente no navegador com apenas dois arquivos principais:

- `index.html`
- `css/estilo.css`

Não há JavaScript, bibliotecas externas de interface ou frameworks. A página foi montada com estrutura semântica, comentários didáticos em português e estilos preparados para futura substituição manual das imagens.

## Estrutura de pastas

```text
projeto-dostoievski/
├── index.html
├── css/
│   └── estilo.css
├── img/
│   ├── autor-principal.png
│   ├── obra-1.png
│   ├── obra-2.png
│   ├── obra-3.png
│   ├── obra-4.png
│   ├── obra-5.png
│   ├── obra-6.png
│   └── vida-autor.png
└── README.md
```

## Como abrir no navegador

1. Mantenha a estrutura de pastas exatamente como está.
2. Abra o arquivo `index.html` em qualquer navegador moderno.
3. O CSS será carregado automaticamente a partir de `css/estilo.css`.

## Como trocar as imagens

As imagens foram preparadas para funcionar com placeholders elegantes mesmo quando os arquivos visuais ainda não existem ou não foram substituídos.

Substitua os arquivos dentro da pasta `img/` usando exatamente estes nomes:

- `img/autor-principal.png`
- `img/obra-1.png`
- `img/obra-2.png`
- `img/obra-3.png`
- `img/vida-autor.png`

Se quiser usar nomes diferentes, altere os caminhos em `index.html` dentro de cada bloco com `style="--imagem-url: url('...')"` e também no atributo `src` da imagem acessível correspondente.

## Como alterar os textos

Todos os textos estão diretamente no arquivo `index.html`.

Principais áreas para edição:

- marca e menu no cabeçalho
- título e descrição da seção principal
- cartões da seção “Profundidade Filosófica”
- cartões da seção “Obras-Primas”
- texto da seção “A Vida de um Visionário”
- conteúdo institucional e links do rodapé

## Como alterar as cores principais

As cores centrais estão no topo do arquivo `css/estilo.css`, dentro do bloco `:root`.

Variáveis principais:

- `--cor-fundo`
- `--cor-fundo-secundario`
- `--cor-vinho`
- `--cor-vermelho-destaque`
- `--cor-vermelho-intenso`
- `--cor-texto-principal`
- `--cor-texto-secundario`
- `--cor-borda`

Ao alterar essas variáveis, o restante da interface acompanha automaticamente a nova paleta.

## Seções que compõem a página

A página foi dividida nas seguintes áreas:

1. Cabeçalho com marca e navegação.
2. Seção principal com retrato, título, citação e botões.
3. Seção “Profundidade Filosófica” com três cartões temáticos.
4. Seção “Obras-Primas” com três cartões editoriais.
5. Seção “A Vida de um Visionário” com destaque biográfico.
6. Rodapé com bloco institucional, um único bloco “Explorar” e base legal.

## Como a responsividade foi pensada

O layout foi preparado para três faixas principais:

- `desktop`: colunas amplas, maior respiro lateral e destaque visual mais cinematográfico;
- `tablet`: reorganização gradual das grades e redução de espaçamentos;
- `mobile`: empilhamento das colunas, botões em largura total e adaptação do cabeçalho para leitura confortável.

As imagens usam quadros com fundo em gradiente e camada de `background-image`, o que ajuda a preservar a composição mesmo antes da inserção das imagens finais.
Site: <a href="https://dostoievsky.vercel.app"></a>
<img width="1920" height="1080" alt="Captura de Tela (19)" src="https://github.com/user-attachments/assets/26181f01-e10d-41d9-b547-3bd92e4885db" />
