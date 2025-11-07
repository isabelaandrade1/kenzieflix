# Flix

Projeto desenvolvido na parte 2 da maratona de programação da Kenzie Academy Brasil.

## O que é este projeto?

O Flix é uma página estática que recria, para fins educacionais, a interface inicial da Netflix. Foi construída com HTML5 e CSS3 para praticar semântica, tipografia, espaçamento, posicionamento (Flexbox) e responsividade. O layout inclui cabeçalho com navegação, seção de destaque com botões ("Assistir" e "Mais informações") e listas horizontais de filmes como "Em alta", "Só na Netflix" e "Top 10 no Brasil hoje".

Não há backend ou reprodução de vídeos: todas as imagens estão em `assets/img` e os estilos em `assets/css/style.css`. Para visualizar localmente, basta abrir o arquivo `index.html` no navegador ou servir a pasta do projeto em um servidor HTTP simples.

## O Projeto

### Estrutura de arquivos

- flix
    - README.md
    - index.html
    - /assets
        - /css
            - style.css
        - /img

### Fonte

- 'Roboto', sans-serif;

### Cores

- Preto: #141414
- Bege: #E5E5E5
- Branco: #FFFFFF
- Cinza escuro: #6D6D6E
- Vermelho: #B9090B
- Cinza claro: #808080

## Desafios

### 1. Ícones cabeçalho

Adicione os ícones ao cabeçalho. As imagens necessárias já foram baixadas e estão nesse projeto. Você vai encontrar essas imagens em `/assets/img`.

Seu trabalho aqui, é apenas adicioná-las ao cabeçalho, assim como está o layout dao figma. Veja um exemplo abaixo:

<img src="./assets/img/desafio1.png" width="500px">

### 2. Finalizar botões "Assistir" e "Mais informações"

Esse desafio é dividido em duas partes.

#### 2.1 Adicionar modificador ao botão "Mais informações"

Você deve ter percebido que o botão "Mais informações", possui um estilo um pouco diferente do botão "Assistir". Seu trabalho nesse desafio, é adicionar os estilos que diferenciam o botão "Mais informações".

_*Dica: note que a cor de fundo do botão mais informações possui um transparência, não é uma cor sólida(opaca)_

#### 2.2 Adicionar ícones

Esses dois botões possuem um ícone. Nessa parte do desafio você precisa adicionar os devidos ícones aos devidos botões.

Os ícones já foram baixados no projeto e você os encontra em `/assets/img`.

Veja abaixo um exemplo do resultado final, ao finalizar as duas partes do desafio 2:

<img src="./assets/img/desafio2.png" width="500px">

### 3. Adicionar as seções "Só na Netflix" e "Top 10 no Brasil hoje"

Na aula mostramos o desenvolvimento de duas seções de lista de filmes. Seu trabalho nesse desafio é utilizar o que mostramos na aula, como referência para adicionar mais duas seções, "Só na Netflix" e "Top 10 no Brasil hoje".

As imagens necessárias para a finalização desse desafio, também já foram baixadas e salvas nesse projeto. Você vai encontrá-las em `/assets/img`.

Veja um exemplo abaixo do resultado esperado:

<img src="./assets/img/desafio3.png" width="100%">

### 4. Finalizar rodapé

Seu trabalho nesse desafio é adicionar os elementos faltantes no rodapé.

Veja abaixo um exemplo do resultado final esperado:

<img src="./assets/img/desafio4.png" width="100%">

### 5. Estilizar scrollbar da seções de filmes

Para aplicar o efeito de carrossel às seções de filmes, foi adicionado uma scrollbar em cada uma das seções. Mas o estilo padrão não é lá muito agradável, estéticamente falando.

Para evitar que isso estrague seu layout, adicione um estilo que combine com a cara do seu site. Para isso, você pode adicionar o seguinte código ao seu CSS:

```css
*{
    scrollbar-width: thin;
    scrollbar-color: #fff #141414;
    
}
*::-webkit-scrollbar {
    width: 9px;
}

*::-webkit-scrollbar-track {
    background: #141414;
}

*::-webkit-scrollbar-thumb {
    background-color: #fff;
    border-radius: 20px;
    border: 2px solid #141414;
}
```

## Layout

### Figma

- [Figma desktop](https://www.figma.com/proto/hd2wX65H6ZVLTOilHR64mi/Flix?node-id=0-1&t=VF3mQkf0KOTv7K9h-1)
- [Figma mobile](https://www.figma.com/file/6Ruhg2NFs3CDxtoWLBfEsz/NetflixApp?node-id=0%3A1)

### Imagem

- [Imagem Desktop](./assets/img/desktop.png)
- [Imagem Mobile](./assets/img/mobile.png)

### Resultado final

- [Flix](https://kenzie-academy-brasil.github.io/kenzieflix/)