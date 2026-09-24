# Mapa de Nodes HFC — Pelotas

Versão operacional baseada no painel de Porto Alegre, adaptada para Pelotas.

## Atualização diária

A base geográfica, bairros/regiões, aliases e regras ficam neste repositório.
A única informação atualizada manualmente é a coleta do XPERTrack `Pelotas.csv`, na pasta pública do Google Drive definida no app.

Fluxo: XPERTrack → substituir `Pelotas.csv` no Drive → recarregar o Streamlit.

O app tenta localizar pelo nome `Pelotas.csv` dentro da pasta pública. Como contingência, mantém o ID do arquivo validado em 23/09/2026. Não é necessário subir a coleta no GitHub.

## GitHub / Streamlit

Suba os arquivos deste pacote na raiz do repositório, preservando a pasta `data/`. O Streamlit usa `streamlit_app.py` como arquivo principal.
