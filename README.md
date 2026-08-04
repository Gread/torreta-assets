# torreta-assets

Hospedagem publica dos icones de item de inventario Steam do jogo **Torreta**
(App ID 2998660).

Este repositorio existe por um motivo unico: a Steam **nao hospeda** icone de
item de inventario — o campo `icon_url` da itemdef precisa ser um URL HTTPS que
voce controla. O codigo do jogo fica em outro lugar, privado; aqui so ha imagem.

## Conteudo

`crystals/` — o Cristal de Torre, item concedido ao chegar na wave 50 no
Pesadelo, nas cinco raridades. Dois tamanhos por raridade:

| arquivo | tamanho | onde aparece |
|---|---|---|
| `crystal_<raridade>.png` | 200x200 | grade do inventario |
| `crystal_<raridade>_large.png` | 2048x2048 | visao de detalhe |

Raridades: `common`, `uncommon`, `rare`, `epic`, `legendary`.

As cinco sao a MESMA pedra: so a cor e o brilho interno mudam. Cinco formas
diferentes leriam como cinco itens, e nao como um item em cinco graus.

## Como foram feitos

Nao sao desenho: sao geometria marchada por raymarching num shader
(`procedural_cristal.gdshader`, no repositorio do jogo) e assados em PNG. Poligono
chapado nao mostra o que faz uma pedra parecer pedra — faceta, e o que a luz faz
entre elas.

## Licenca

(c) Ricardson Albuquerque. Todos os direitos reservados. Publicado aqui apenas
para servir como origem dos icones na Steam.
