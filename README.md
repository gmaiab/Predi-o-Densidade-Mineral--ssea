# Uso de Aprendizado de Máquina para a Predição de Densidade Mineral Óssea

Repositório contendo o código utilizado para realização dos experimentos da dissertação de mestrado entitulada "Uso de Aprendizado de Máquina para a Predição de Densidade Mineral Óssea"

## Pré-requisitos

- Python3
- virtualenv

## Setup

- Faça o clone do repositório
- Crie um ambiente virtual: `virtualenv .env -p python3`
- Ative a env: `. .env/bin/activate`
- Instale os requerimentos: `pip install -r requirements.txt`
- Crie um diretório `data` e mova o arquivo dataset para esse folder (se você ainda não tem o dataset, por favor entre em contato com os autores ou abra uma issue)

## Execução

- Ative a env: `. .env/bin/activate`
- Inicie os experimentos: `python3 run_experiment.py`
- Depois que os experimentos finalizarem, execute os testes estatísticos: `python3 run_statistical_test.py`

## Informações extras

Os logs serão armazenados no diretório _logs_. As saídas serão armazenadas no diretório _output_.

O repositório poderá ser atualizado com códigos modificados, mais bem documentados ou novos arquivos.
