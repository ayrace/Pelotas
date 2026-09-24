# Mapa de Nodes HFC — Pelotas

Versão operacional baseada no painel de Porto Alegre, adaptada para Pelotas.

## Atualização diária

A base geográfica, bairros/regiões, aliases e regras ficam neste repositório.
A única informação atualizada manualmente é a coleta do XPERTrack `Pelotas.csv`, na pasta pública do Google Drive definida no app.

Fluxo: XPERTrack → substituir `Pelotas.csv` no Drive → recarregar o Streamlit.

O app tenta localizar pelo nome `Pelotas.csv` dentro da pasta pública. Como contingência, mantém o ID do arquivo validado em 23/09/2026. Não é necessário subir a coleta no GitHub.

## GitHub / Streamlit

Suba os arquivos deste pacote na raiz do repositório, preservando a pasta `data/`. O Streamlit usa `streamlit_app.py` como arquivo principal.


## Validações de cadastro — 23/09/2026
- Excluídos do mapa: FGTAM, FGTAG e CNTAD.
- TRVAI consolidado em TRVAIA (portas 1, 2, 3 e 4); TRVAI não aparece como node separado.
- CRZAA consolidado em CRZAAA (portas 1, 2, 3 e 4); CRZAA não aparece como node separado.
- STRAC consolidado em STRACA; STRAC não aparece como node separado.


## V5 — correções de cadastro
Excluídos do mapa/base geográfica: STRABD, STRABN e AREBC.


## V7 — correção cadastral
- STRABD e STRABN removidos somente da base fixa do mapa.
- Âncora geográfica TVRAIA corrigida para TRVAIA.
- TRVAIA-1, TRVAIA-2, TRVAIA-3 e TRVAIA-4 passam a cruzar diretamente com o node TRVAIA da base fixa.


## V8 — correções cadastrais
- STRBD removido da base fixa, bairros e regiões.
- STRBN removido da base fixa, bairros e regiões.
