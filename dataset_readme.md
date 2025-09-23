Descrição do Dataset (vlr_stats_cache.csv)
Este documento descreve o conteúdo e a origem do dataset utilizado no projeto de análise de desempenho de VALORANT.

1. Origem
O dataset não é estático; ele é gerado e atualizado dinamicamente pelo script gerador_relatorios_valorant.py. Os dados são extraídos através de Web Scraping do site VLR.gg (https://www.vlr.gg/), que é uma fonte pública e amplamente reconhecida de estatísticas do cenário competitivo de VALORANT.

O arquivo vlr_stats_cache.csv funciona como uma versão de cache local dos dados coletados para agilizar a execução do script.

2. Conteúdo do Arquivo
O arquivo CSV contém as estatísticas de desempenho de jogadores em diversos campeonatos. Cada linha representa o desempenho de um jogador em um campeonato específico.

Principais Colunas (Variáveis):
Player: Nome de usuário (nick) do jogador.

Equipa: Sigla da equipe pela qual o jogador competiu.

Agente: Lista de agentes mais jogados pelo atleta no campeonato.

Campeonato: Identificador do torneio de onde os dados foram extraídos.

Rounds: Número total de rodadas jogadas pelo atleta no campeonato.

ACS (Average Combat Score): Pontuação Média de Combate. Métrica principal de impacto em combate.

KD (Kill/Death Ratio): Razão entre abates e mortes.

KAST: Percentual de rodadas em que o jogador teve um abate (Kill), assistência (Assist), sobreviveu (Survived) ou foi trocado (Traded). Métrica de consistência.

ADR (Average Damage per Round): Dano Médio por Rodada.

KPR (Kills Per Round): Abates por Rodada.

APR (Assists Per Round): Assistências por Rodada.

FKPR (First Kills Per Round): Primeiros Abates por Rodada.

FDPR (First Deaths Per Round): Primeiras Mortes por Rodada.

HS% (Headshot Percentage): Percentual de tiros na cabeça.

3. Utilização
Este dataset serve como a fonte de dados primária para todas as análises, relatórios e visualizações geradas pelo script principal do projeto.
