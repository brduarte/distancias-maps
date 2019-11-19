# Distancias-Maps

O sistema serve pra nada! O foco foi apenas em criar uma estrutura para consumir API's.

|<img width="50%" src="https://github.com/brduarte/Distancias-Maps/blob/master/img.gif">

## ⚒️ Funcionalidade
  
  - Consultar a distância entre dois pontos geográficos utilizando a API do Google Maps

## 👨‍💻 Executando localmente 

Assegure-se de ter [Node.js](http://nodejs.org/) instalado

- 1º clone o projeto:

```shell script
$ git clone https://github.com/brduarte/Distancias-Maps.git # ou clone seu próprio fork
```

- 2º você precisa ativar api do [Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/start) do Google Maps
- 3º na pasta raiz é preciso renomear o arquivo 'config.exemplo.js' para 'config.js'

Ex: /config.js
```js script
    googleAPi: {
        maps: {
            url: "https://maps.googleapis.com/maps",
            distanceMatrix: {
                uri: 'api/distancematrix/json',
                language: "pt-BR",
                units: "matric",
                key: ""
            }
        }
    }
```

- 4º depois é só executar o projeto

```shell script
$ cd Jogo-Multiplayer
$ npm install
$ npm start
```

## 📝 Documentação 

Para obter mais informações das ferramentas utilizadas:

- [Node.js](https://nodejs.org/en/docs/)
- [Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/start)

## Autor

| [<img width="125px" src="https://avatars2.githubusercontent.com/u/29002558?v=4"><br><sub>@brduarte</sub>](https://github.com/brduarte)|
| :---: |
