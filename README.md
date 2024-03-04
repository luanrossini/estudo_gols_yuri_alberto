# Analise dos 70 gols de Yuri Alberto
Analisando os gols do jogador Yuri Alberto com Python

## Introdução
Yuri Alberto é um atacante brasileiro conhecido por sua habilidade dentro da área e sua capacidade de finalização. Nascido em 2001, ele iniciou sua carreira profissional no Santos FC, onde ganhou destaque pelas categorias de base e foi promovido ao time principal em 2018. Em seguida, teve passagens por clubes como Internacional e Athletico Paranaense antes de se transferir para o Corinthians. Com sua velocidade, técnica e faro de gol, Yuri Alberto tem sido uma peça importante no ataque do Corinthians, buscando sempre contribuir para as vitórias de sua equipe.

### Objetivo:

Analisar os gols do atacante brasileiro Yuri Alberto e tirar insights dos dados coletados e estudados.

### Informações do dataset:
temporada: Ano em que ocorreu o campeonato
competição: Nome do campeonato disputado
rodada: Número da rodada do campeonato ou fase do torneio
data: Data que aconteceu a partida
cidade: Local da partida (C = CASA, F = FORA)
por: Nome do time que Yuri Alberto defende
adversario: Nome do time adversário da partida
resultado: Resultado final da partida
posicao: Nome da posição que Yuri Alberto iniciou a partida
minuto: Número do minuto da execução do gol
para resultado: Resultado temporário que o gol aconteceu
tipo de gol: Tipo do gol executado
assistencia: Nome do jogador que fez a assistência
Obtenção dos Dados e Importação de Bibliotecas

### Análises
# 1. Quais as datas do primeiro e último gol do atacante?
Primeiro gol: 2018-07-03 00:00:00

Último gol: 2024-11-02 00:00:00

# 2. Quais os principais tipos de gols de Yuri Alberto?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/79c399e6-442c-4a44-8e05-e66427b15003)

Nota-se que os principais recursos que o atacante mais tem êsito são nos chutes de pé direito, cabeçada e chute com o pé esquerdo.

Já pênaltis e jogadas individuais não são tão representativas, mostrando que o jogador tende a não ter esses dois pontos como fortes em suas habilidades.

# 3. Qual a distribuição de gols dentro e fora de casa do centro-avante?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/452e8df6-7222-4bb0-a57c-eb9487299db3)

Os dados mostram uma tendência marcante do atacante em marcar mais gols em jogos disputados dentro de casa, sugerindo uma forte influência do fator localização no desempenho do goleador.

# 4. Qual o top 5 times que mais levaram gols e quais os 5 principais assistentes de Yuri Alberto?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/cd8847a2-4e39-4710-b16a-018fca347cc5)

Destaca-se os clubes Atlético-GO, Flamengo, Bahia, São Paulo e Santos como os principais alvos do atacante. É legal destacar que mesmo tendo uma passagem pelo Santos no início de sua carreira, Yuri Alberto tem o time da baixada como uma das 5 principais vítimas em suas estatísticas de gols marcados contra.

# 5. Quais as faixas de tempo de todos os gols?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/0d9d87e2-21ca-4426-8fa5-a2b853791e85)

Yuri tende a marcar mais gols entre os 15 minutos finais de cada tempo e tende a fazer menos gols nos começos das partidas. Isso muito pode ser explicado devido as fortes marcações e estudos que o futebol moderno aplica na etapa inicial de cada partida, o que deixa o jogo mais truncado e com menos possibilidades de finalizações e gols.

# 6. Quais os campeonatos que Yuri mais fez gol? E quais os anos em que ele mais balançou as redes adversárias?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/104e8c13-3eed-4a4c-81d1-b5dfaa4cef90)

Destaca-se o Brasileirão como o principal torneio em que o atacante converte gols em sua carreira e os anos de 2021 e 2022 como as duas principais temporadas em relação a quantidade de gols marcados.

Há de se destacar também a grande diferença de métricas entre os anos de 2018/2019 para 2020, mostrando uma maturidade e evolução do jogador no fundamento de fazer gol.

# 7. Quais os resultados finais dos jogos em que Yuri fez gol? E quais os resultados parciais que os gols resultaram?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/8170099e-7ab6-4561-825f-bbeb59b3ea87)
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/5d03acd1-b4c8-4176-8b51-6c88b308a8ef)

É evidente que os jogos que o atacante marca gol são finalizados com vitória do time do jogador.

Também é importante destacar que a grande volumetria dos gols de Yuri são do tipo "ampliou ou diminuiu o placar" e "fechou o placar", mostrando que o atacante conta com boa conversão durante o andamento da partida.

################################################################################################################################

Para as próximas análises, vamos usar uma outra base de dados agregando mais informações e possibilidades de desdobramentos.

### Informações do dataset:
temporada: Ano em que ocorreu o campeonato
competição: Nome do campeonato disputado
plantel: Número de vezes que o jogador foi relacionado para uma partida
jogos: Número de vezes que o jogador participou de uma partida
pontos_por_jogo: Número de pontos médio por jogo disputado
gols: Quantidade de gols feitos
assistencias: Quantidade de assistencias
gols_contra: Quantidade de gols contra
suplente_utilizado: Quantidade de partidas utilizado como reserva
substituicoes: Quantidade de partidas que foi substituido
cartoes_amarelos: Quantidade de cartões amarelos
expulsoes_dois_amarelos: Quantidade de expulsões com 2 amarelos
expulsoes_vermelho_direto: Quantidade de expulsões com vermelho direto
gol_de_penalti: Quantidade de gols de pênalti
minutos_por_gol: Quantidade de minutos jogador para ocorrer um gol
minutos_jogados: Quantidade total de minutos jogados

### 8. Quantos minutos para participar de um gol Yuri Alberto tem por temporada?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/82990617-d392-4acb-9d40-1fb085ae7b38)

### 9. Qual competição Yuri tem o menor tempo médio para participar de um gol?
![image](https://github.com/luanrossini/estudo_gols_yuri_alberto/assets/119509335/21671c2b-831c-42f8-89d4-09718cb15acb)

Analisando o desempenho da minutagem necessárias para participar de um gol, os dados nos mostram que o atacante está precisando de mais muitos para participar de um gol efetivo.

# Conclusão
É evidente que o atacante Yuri Alberto é um dos grandes nomes dos atacantes da nova safra do futebol brasileiro. O jovem goleador desempenha uma função vital nos times que passa e coleciona números impressionantes.

Nesta análise conseguimos identificar alguns pontos importantes que podem ajudar a entender as boas métricas do jogador, dentre as principais podemos citar:

O atacante tem o chute com o pé direito como principal meio de fazer gols;
O "fator casa" influencia muito na conversão de gols;
Atlético-GO é o clube que mais foi vítima dos goleador e Edenilson o maior assistente
Brasileirão e o Paulistão são as duas competições que tiveram conversões de gols de Yuri;
Grande parte dos gols feitos foram entre 30 à 45 minutos e 75 à 90 minutos;
Ao decorrer dos anos, o jogador tem indicador de minutagens para participações de gols com tendência de aumento, mostrando que o jogador demora mais tempo para fazer gol ou dar uma assistência.
Esse estudo é apenas uma visão macro dos dados disponibilizados e há a possibilidade de desencadear mais estudos e análises futuras.
