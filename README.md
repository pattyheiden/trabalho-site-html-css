# Trabalho de HTML e CSS +DEVS2BLU

Projeto acadêmico com duas páginas desenvolvidas em **HTML5 e CSS3**: uma página sobre a loja fictícia Mirror Fashion e uma tabela de classificação de futebol.

## Páginas

- **Sobre a Mirror Fashion (`index.html`):** apresentação da empresa, centro de distribuição, história e diferenciais. 
- **Tabela de classificação (`tabela.html`):** 20 times, escudos, pontuação, jogos, aproveitamento, vitórias e saldo de gols.

## Tecnologias

- HTML5 para a estrutura e o conteúdo das páginas.
- CSS3 para cores, tipografia, posicionamento e adaptação a telas menores.
- Sem JavaScript, frameworks ou dependências externas.

## Estrutura do projeto

```text
trabalho-1/
├── index.html
├── tabela.html
├── css/
│   ├── estilo.css
│   └── tabela.css
└── assets/
    └── icons/        
        ├── logo-rodape.png
        └── logo.png
    └── imgs/
        ├── familia-pelho.jpg    
        └── logo-rodape.png
```

## Como executar

1. Clone o repositório ou baixe e extraia o ZIP.
2. Abra o arquivo `index.html` em um navegador.
3. Use o link ao final da página para acessar a tabela, ou abra `tabela.html` diretamente.

Não é necessário instalar dependências ou iniciar um servidor. As imagens e os estilos estão incluídos no projeto. Links externos precisam de conexão com a internet.

## Recursos implementados

- Estrutura semântica com cabeçalho, conteúdo principal, seções, navegação e rodapé.
- Imagens com textos alternativos e legendas.
- Links internos para as seções História e Diferenciais.
- Adaptação da página Sobre para telas menores.
- Tabela HTML com cabeçalhos, linhas alternadas e cores conforme a referência.
- Rolagem horizontal da tabela em telas estreitas.
- Destaque de foco para navegação por teclado.

A tabela utiliza os elementos `table`, `thead`, `tbody`, `tr`, `th` e `td`. Seus dados são texto HTML selecionável. Somente os escudos são exibidos a partir da imagem de referência, usando `background-position` no CSS.

## Objetivo acadêmico

Praticar a estruturação de páginas, a aplicação de estilos em arquivos CSS separados, o uso de imagens e links e a construção de tabelas em HTML.
