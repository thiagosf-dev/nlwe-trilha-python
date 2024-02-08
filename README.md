# BarCode Generator

Projeto de estudo criado no evento da Rocktseat NLWE - trilha de Python

Esta API expõe um endpoint para o recurso TAG, usando o HTTP Method POST, que deve ter no body, uma string que representa o número do código do produto que deverá ser gerado o Código de Barras para impressão

Foram aplicados o uso das seguintes bibliotecas:
- Python 3
- PIP3
- Flask
- pillow
- pre-commit
- PyLint
- python-barcode
- PyTest
- virtualenv
- Cerberus

> Este projeto foi desenvolvido no WSL2, na IDE VSCode, Python3 e o PIP3, em um ambiente virtual do "venv" e teve a rota testada no Postman

Para executar este projeto, basta realizar o clone do mesmo e rodar os seguintes comandos na sequência:

`pip3 install -r requirements.txt`

`python3 run.py`

THE ROUTE: `POST` http://localhost:3000/create_tag

BODY MODEL: `{"product_code":"523"}`

