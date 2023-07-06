# Projeto Google Maps em React

Este projeto foi desenvolvido por Erik Tomelin, Vinicius Ferri e Gustavo Malkovski, e possui como objetivo demonstrar a integração do Google Maps em uma aplicação React, com recursos como adicionar marcadores, zoom in e zoom out, controles básicos ocultados, autocomplete nas localizações, serviço de direção e renderização das direções.

## Funcionalidades Principais

- Google Maps em React: O projeto utiliza a biblioteca React para renderizar o mapa do Google Maps.
- Adicionar marcadores: É possível adicionar marcadores no mapa para indicar pontos de interesse ou localizações específicas.
- Zoom in e zoom out: A aplicação permite controlar o nível de zoom no mapa, permitindo uma visualização mais detalhada ou uma visão mais ampla.
- Controles básicos ocultados: Os controles padrão do Google Maps, como os botões de zoom e controle de rotação, podem ser ocultados para uma interface mais limpa e personalizada.
- Autocomplete nas localizações: É implementado um recurso de autocomplete para facilitar a busca de localizações. Os usuários podem digitar um endereço ou lugar, e a aplicação sugere opções à medida que o usuário digita.
- Serviço de direção: A aplicação utiliza o serviço de direção do Google Maps para calcular rotas entre dois pontos específicos.
- Renderização das direções: As rotas calculadas são exibidas no mapa, permitindo visualizar a direção a ser seguida.

## Iniciando o App

Para executar o aplicativo, siga as etapas abaixo:

1. Crie uma chave de API no Google Developers Console e certifique-se de habilitar o acesso de terceiros à sua API, caso contrário, ocorrerá um erro de "development purposes only".
2. Adicione um arquivo `.env` ou `.env.local` na pasta raiz do projeto e especifique sua chave de API da seguinte forma: `REACT_APP_GOOGLE_MAPS_API_KEY=your_api_key_here`.
3. No diretório do projeto, execute o seguinte comando, dependendo do gerenciador de pacotes que você está usando:

Usando Yarn:

```
yarn install
yarn start
```

Ou usando npm

```
npm install
npm start
```
## Artefato
![alt text](Diagramas/artefatos.jpg)

## Pipeline
![image](https://github.com/erik-tomelin/quick-map-search/assets/63025296/cd431e42-6e9c-4fe2-a48a-08a02d7a6394)

Isso instalará as dependências do projeto e iniciará o aplicativo. Acesse `http://localhost:3000` em seu navegador para visualizar o aplicativo.

# Projeto de Geração de Labirintos e Busca de Caminhos com o Algoritmo A*
link para o projeto: https://colab.research.google.com/drive/1jhSCs2Iw_O3h7MvYy28ZHChUl1o0SBz2?usp=sharing

Este projeto consiste em uma implementação em Python do algoritmo A* (A-Star) para geração de labirintos aleatórios e busca de caminhos entre um ponto de início e um ponto de objetivo no labirinto. O objetivo principal é demonstrar o funcionamento do algoritmo A* e sua aplicação em problemas de busca de caminhos.

## Funcionalidades Principais
- Geração de labirintos: Utilizando o algoritmo de caminhada aleatória, o projeto gera labirintos aleatórios com caminhos livres e paredes.
- Algoritmo A*: O algoritmo A* é aplicado para encontrar o caminho mais curto entre um ponto de início e um ponto de objetivo no labirinto.
- Heurística de distância de Manhattan: Para estimar a distância entre os nós, é utilizada a heurística de distância de Manhattan, que considera a soma das distâncias -horizontais e verticais entre os pontos.
- Marcação de caminhos: O caminho principal encontrado pelo algoritmo A* é marcado no labirinto com o símbolo '*', facilitando a visualização do caminho percorrido.
- Caminhos alternativos: Além do caminho principal, o projeto gera caminhos alternativos para explorar diferentes rotas no labirinto.
Como utilizar


Siga as instruções abaixo para executar o projeto em sua máquina:
- Certifique-se de ter o Python instalado em seu ambiente.
- Faça o download dos arquivos do projeto.
- Execute o arquivo maze_solver.py em um interpretador Python.

Ao executar o código, o projeto irá gerar um labirinto aleatório e encontrar o caminho mais curto entre o ponto de início e o ponto de objetivo utilizando o algoritmo A*. 
O caminho principal será marcado no labirinto com o símbolo '*', indicando o percurso realizado. Além disso, serão gerados caminhos alternativos para explorar diferentes rotas no labirinto.

## Mapa Gerado e a busca de caminhos com o Algoritmo A*
![image](https://github.com/erik-tomelin/quick-map-search/assets/63025296/ae6d83c8-e60f-42e6-9110-29d485740c31)
