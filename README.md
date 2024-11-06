# Gerenciamento, configuração e processos de software - N3
**Equipe:** Andrey Garcia dos Santos, Graziela Torres, Sophia Eggert Freire da Rocha

O PokeApp é uma aplicação interativa onde os usuários podem buscar informações detalhadas sobre os Pokémon, como nome, tipo, habilidades, estatísticas e muito mais. O projeto utiliza o ReactJS para a interface do usuário e o TypeScript para garantir maior robustez e segurança no código.

A aplicação consome a PokeAPI (https://pokeapi.co/) para buscar os dados de Pokémon e exibi-los de forma organizada.

## Tecnologias
- ReactJS: Framework para construção da interface de usuário.
- TypeScript: Superset do JavaScript que adiciona tipagem estática.
- Axios: Biblioteca para realizar requisições HTTP.
- PokeAPI: API pública para acessar informações sobre Pokémon.

## Funcionalidade
- Exibir lista de Pokémon: Mostra uma lista com os primeiros Pokémon.
- Detalhes do Pokémon: Ao clicar em um Pokémon, são mostradas informações detalhadas sobre ele.
- Filtro de tipos: Filtro para exibir apenas Pokémon de um tipo específico.

## Pré-requisitos
Node.js (Recomendado: versão 14 ou superior)
npm ou yarn

## Instalação
1. Clone este repositório

```
git clone https://github.com/seu-usuario/pokeapp.git
```

2. Instale as dependências
Navegue até a pasta do projeto e instale as dependências utilizando npm ou yarn.

```
cd pokeapp
```
```
npm install
```
3. Execute a aplicação
Após a instalação das dependências, execute o seguinte comando para iniciar o servidor de desenvolvimento:
```
npm run dev
```
A aplicação estará disponível em http://localhost:3000.
