# Jogo de Pokémon em Python

Este é um jogo de Pokémon básico desenvolvido em Python.

## Funcionalidades

* Escolha de Pokémon inicial
* Batalhas entre jogadores e inimigos
* Captura de Pokémon selvagens
* Sistema de dinheiro
* Exploração de áreas selvagens

## Como executar

1.  Clone o repositório:

    `git clone https://github.com/dolthub/dolt`

2.  Instale as dependências:

    (Se houver alguma dependência externa, liste-as aqui)

3.  Execute o jogo:

    `python main.py`

## Estrutura do projeto

* `main.py`: Arquivo principal do jogo
* `pokemon.py`: Classes e funcionalidades relacionadas aos Pokémon
* `pessoa.py`: Classes e funcionalidades relacionadas aos jogadores e inimigos

## Classes

* `Pessoa`: Classe base para jogadores e inimigos
* `Player`: Classe para jogadores, herda de `Pessoa`
* `Inimigo`: Classe para inimigos, herda de `Pessoa`
* `Pokemon`: Classe base para Pokémon
* `PokemonFogo`: Classe para Pokémon do tipo Fogo, herda de `Pokemon`
* `PokemonEletrico`: Classe para Pokémon do tipo Elétrico, herda de `Pokemon`
* `PokemonAgua`: Classe para Pokémon do tipo Água, herda de `Pokemon`

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença

Este projeto está sob a licença [Nome da licença].
