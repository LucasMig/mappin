# Mappin App

## Objetivo

Criar uma aplicação que permitisse registrar num mapa as informações sobre sessões de treino do usuário.

A intenção principal foi praticar e aprender mais sobre programação orientada a objetos dentro do JavaScript, e também aprender a utilizar uma biblioteca externa.

## Como testar

O resultado final do projeto está hospedado [aqui](https://mappin.netlify.app/).

Pra adicionar um novo workout, basta clicar no mapa o local onde ele ocorreu. Ao clicar, um form aparecerá na barra lateral, onde é preciso selecionar o tipo do workout (corrida ou ciclismo) e fornecer as informações pedidas.

Após preencher, é só pressionar a tecla Enter pra submeter o formulário.

## Funcionalidades

### Ao carregar

Após a aplicação carregar completamente (considerando que a permissão para usar a localização do dispositivo foi concedida), o mapa irá centralizar de acordo com a localização do usuário.

### Event listeners

Após clicar no mapa, preencher as informações do workout e submetê-las, um marcador aparecerá no mapa mostrando o tipo e a data do workout.

Na barra lateral, além dessas informações, aparecerão alguns outros dados referentes ao workout selecionado. Ao clicar em algum dos workouts já criados, o mapa será re-centralizado de acordo com as coordenadas dele.

### Armazenamento

A aplicação usa a API de localStorage, por isso as informações preenchidas ficarão salvas, mesmo que a página seja recarregada.

## Sobre esse projeto

A aplicação foi criada com HTML, CSS e JavaScript, e também com a biblioteca da [Leaflet](https://leafletjs.com/). Aprendi e pratiquei um pouco mais alguns princípios e práticas como:

- Estruturas de dados
- JavaScript Assíncrono
- Geolocalização
- Orientação a objetos
- Classes no JavaScript
- Interfaces públicas e privadas
- Herança
