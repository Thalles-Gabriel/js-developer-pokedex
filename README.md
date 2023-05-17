# Projeto PokeFilter

Projeto criado na trilha educacional da DIO focada no aprendizado de front-end em preparação para a framework Angular.

## Descrição do projeto

O projeto se baseia em transformar as utilidades já existentes da [PokeApi](https://pokeapi.co) e expandir as mesmas para um caso de uso voltado aos tipos e habilidades dos Pokemons.

## Funcionalidades

Ao entrar no site, será gerada uma lista completa de todos os Pokemons fornecidos pela PokeApi, essa qual poderá ser filtrada entre três diferentes opções: 

1. Habilidades
2. Tipos
3. Individual

Na caixa de texto poderá ser digitado o valor qual as opções se orientam, por exemplo, se busca por um Pokemon do tipo fogo basta apenas digitar *Fire* enquanto a opção *Tipo* está selecionada.

### Individual

A opção Individual se refere ao nome do Pokemon em si, voltando apenas este se houver.

### Metodologia de filtragem

A lista não se refaz após o acionamento da filtragem, permitindo que adicione quantos valores de filtragem quiser como uma busca de Pokemon tipo *Fire* seguido de uma habilidade *Blaze*. Podendo levar a muitas filtragens enquanto houver um Pokemon correspondente.
Caso necessite recomeçar a busca, há um botão *Reset* que refará a lista inteira tal como era no começo


### Navegação

Pelos dois botões *Próximo* e *Anterior* é possível navegar pelos resultados da lista que mostra 20 Pokemons por página até seu fim.

### Foco do projeto

Meu foco neste projeto foi aprender o máximo com o básico de Javascript antes de se adentrar nas várias frameworks do mercado. Aprender promessa, métodos assíncronos, renderização de componentes, utilizar API's já existentes e interpretação de seus dados. Aprimorei também algumas técnicas de css com Flexbox entre outros.
