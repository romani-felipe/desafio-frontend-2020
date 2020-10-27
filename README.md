# Desafio frontend

Olá seja bem vindo ao desafio técnico para vaga de desenvolvedor frontend da Wide Software.

## O desafio

Como bons brasileiros, gostamos de uma boa música para curtir nos momentos mais apropriados com as pessoas que gostamos. Esperamos que você também goste de música e do clima agrdável do nosso país, pois é a partir disso que sua solução será criada.

Precisamos de um sistema que seja possível criar playlists e assossiar uma faixa de temperatura (graus célsios) para ela, assim o sistema irá sempre nos mostrar qual a playlist indicada para o clima atual.

Por Exemplo:

- Clima entre 10 e 15 graus tocar 'Minha playlist de rock'
- Clima entre 16 e 22 graus tocar 'Minha playlist de clássicos'

Lembrando que acima são somente exemplos, o usuário deve conseguir criar quantas playlists ele quiser, ser capaz de adicionar e remover músicas da playlist. Ao acessar o sistema a primeira tela deve informar a melhor playlist baseado na temperatura atual.

Você deverá usar a API do Spotify (https://developer.spotify.com/) para gerenciar playlistas dos usuários e a API da Open Weather para buscar informações do clima (https://openweathermap.org/api).

### Dicas 

- O armazenamento dos dados pode ser feito através do local storage do navegador ou alguma outra solução efêmera.
- Necessidade de backend fica a seu critério, porém não é requisito do teste.
- O design, usabilidade fica a seu critério.
- Pode ser utilizado design sistem prontos.
- As APIS são gratuítas para utilizar.
- O sistema deverá ter duas responsabilidades, gerenciar playlistas e indicar qual a melhor playlist para o clima atual na região do usuário
- O usuário deve conseguir fazer login através de uma conta do spotify usando o Single Sign On do Spotify.


## O que será avaliado?

- Raciocínio para resolver o problema proposto
- Escalabilidade
- Performance
- Qualidade
- Manutenibilidade
- Clareza do código
- Responsividade da página
- Usabilidade
- Qualidade estética da interface desenvolvida

## O que devo entregar?

Um repositório no github, deve ser público, com documentação e instrução de como executar a solução.

### Diferencial
- Adicionar acessibilidade
- Entregar com pipeline de continous integration usando Github Action, para garantir que os testes estão funcionando na Master.
- Entregar imagem docker pública no docker hub
