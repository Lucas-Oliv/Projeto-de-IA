Projeto de Análise de Desempenho - VALORANT
Este repositório contém o código-fonte de um projeto de Inteligência Artificial focado na análise de dados do cenário competitivo de VALORANT. A ferramenta automatiza a coleta, processamento e análise de estatísticas de jogadores e equipes, gerando relatórios detalhados que vão além das métricas superficiais.

Funcionalidades Principais
Coleta de Dados via Web Scraping: Extrai estatísticas detalhadas de múltiplos campeonatos diretamente do portal VLR.gg.

Sistema de Cache Inteligente: Armazena os dados coletados localmente (vlr_stats_cache.csv) para agilizar execuções futuras, com opção de forçar a atualização.

Análise Estatística Avançada: Aplica Teste-T para verificar a significância estatística nas diferenças de desempenho.

Geração de Visualizações: Cria automaticamente um conjunto de gráficos para análise, incluindo:

Boxplots de consistência (ACS, KD, ADR, KAST).

Gráficos de linha para evolução de desempenho ao longo do tempo.

Heatmaps de correlação entre as métricas.

Relatórios Automáticos: Gera pastas organizadas para cada análise contendo um relatório em Markdown (.md), planilhas com dados gerais e detalhados (.csv) e todos os gráficos (.png).
