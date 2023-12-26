# Tecnologia:
<div style="display: inline_block"><br/> 
    <img align="center" alt="python" src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"/>

</div>

## Objetivo:

    Biblioteca feita para adicionar ferramentas uteis para criacao de jogos com python.

## Importar:

    pip install game-utilities-py

## Funções:

### Controles De Sistema:

#### controle_registrar()->
    Permite o registro de contas de players no jogo, usando como banco de dados um arquivo JSON.

#### controle_logar()->
    Permite logar em contas criadas por jogadores.

#### controle_salvarMomento()->
    Permite salvar o estado/fase do jogo de um usuário.
    * O Usuário ja deve ter logado antes.

#### controle_carregarMomento()->
    Permite carregar o estado/fase do jogo de um usuário.
    * O Usuário ja deve ter logado antes.

#### controle_salvarInventario()->
    Permite salvar o inventário de um usuário.
    * O Usuário ja deve ter logado antes.

#### controle_carregarInventario()->
    Permite carregar o inventário de um usuário.
    * O Usuário ja deve ter logado antes.

### Uteis:

#### uteis_timer()->
    Permite criar um timer, que pode ter seu tempo determinado e pode ser tanto CRESCENTE como DECRESCENTE.

#### uteis_gravadorTela()->
    Permite gravar a tela
    *Apenas video, sem som.
