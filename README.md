# Automação Web para Obter Cotações

## Problematização

Você trabalha em uma importadora e precisa atualizar diariamente os preços de compra e de venda dos produtos da empresa. Esses produtos têm seus valores vinculados as seguintes moedas:

- Dólar
- Euro
- Ouro

Para obter a cotação dessas moedas, você faz buscas na internet. Com os valores das cotações, você consegue atualizar uma planilha do Excel com os valores de cotação das moedas, os preços de compra e de venda.


## Solução

Este projeto apresenta uma automação com **Selenium** para obter as cotações do dólar, do euro e do ouro e atualizar a planilha com os preços dos produtos.


## Como Reproduzir este Projeto

Inicialmente, navegue para a pasta na qual deseja clonar o repositório deste projeto. Em seguida, digite o seguinte comando:

```bash
git clone https://github.com/diego-torres-coder/Automacao-Web-Busca-de-Cotacoes.git
```

Para criar o ambiente virtual, navegue até a pasta do projeto  e digite o seguinte comando no terminal:

```bash
conda -n automacao-web-cotacoes python=3.10
```

Em seguida, ative o ambiente:

```bash
conda activate automacao-web-cotacoes
```

Com o ambiente ativo, instale as dependências do projeto:

```bash
pip3 install pandas openpyxl numpy jupyter selenium webdriver-manager
```

Alternativamente, você pode instalar as dependências deste projeto a partir do arquivo `requirements.txt`:

```bash
pip3 install -r requirements.txt
```

Execute o Jupyter Notebook:

```bash
jupyter notebook
```

Abra o arquivo principal deste projeto e execute todas as células.

## Bibliotecas Usadas

Estas são as bibliotecas usadas neste projeto:

- pandas
- selenium
- webdriver-manger
