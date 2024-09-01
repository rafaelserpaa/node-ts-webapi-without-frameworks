# Podcast Manager

### Descrição
Um app ao estilo netfix, aonde possa centralizar diferentes episódios podcasts separados por categoria

### Domínio

Podcasts feitos em vídeo

### Features

- Listar os podcasts em sessões  de categorias
    - [saúde, bodybuilder, mentalidade, humor]
- Filtrar episódios por nome de podcast


## Como

### Feature:
    Listar os podcasts em sessões  de categorias

### Como vou implementar:
    Vou retornar em uma api rest o 
    nome do podcast, nome do episódio, imagem de capa,link, categoria
```js
[
{
    podcastName: "flow",
    episode: "CBUM - Flow #319",
    videoId: "pQSuQmUfS30",
    cover: "https://i.ytimg.com/vi/pQSuQmUfS30/maxresdefault.jpg",
    link: "https://www.youtube.com/watch?v=pQSuQmUfS30"
    category: ["saúde","esporte","bodybuilder"]
},
{
    podcastName: "flow",
    episode: "RUBENS BARRICHELLO - Flow #339",
    videoId: "4KDGTdiOV4I",
    cover: "https://i.ytimg.com/vi/4KDGTdiOV4I/maxresdefault.jpg",
    link: "https://www.youtube.com/watch?v=4KDGTdiOV4I"
    category: ["esporte", "corrida"]
},
]
```
