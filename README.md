# Mapa Sem Sinal HFC — Pelotas

Clone funcional do painel de Porto Alegre, com a base geográfica HFC de Pelotas.

## Atualização diária
Envie a nova exportação do XPERTrack para a pasta `data/`, mantendo no nome `Integridade atual de Node` (CSV/XLSX/XLS). O painel escolhe automaticamente a coleta diária mais recente.

## Base fixa
`base_nodes_pelotas.csv` contém os 94 pontos HFC extraídos do KMZ `RS - PELOTAS - 01.04.2026.kmz`. GPON foi excluído.

## Variações de nomenclatura
`data/cruzamento_variantes_recuperadas.csv` associa derivações lógicas do XPERTrack a uma posição física do KMZ sem fundir a identidade do node. Novos casos podem ser acrescentados em `data/cruzamento_manual.csv`.

## Publicação
No Streamlit Community Cloud, selecione este repositório, branch `main` e arquivo principal `streamlit_app.py`.
