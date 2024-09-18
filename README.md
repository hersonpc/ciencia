# Guia de conhecimento científico

Este é um projeto dedicado a desmistificar e simplificar os processos de construção e entendimento da ciência. Nosso objetivo é criar um repositório abrangente e colaborativo que torne o conhecimento científico mais acessível e compreensível para todos.

A documentação oficial do projeto pode ser encontrada em: [https://ciencia.hersonpc.com/](https://ciencia.hersonpc.com/)

## Tecnologias utilizadas

Estamos utilizando [Python3](https://www.python.org/) e [MkDocs](https://www.mkdocs.org/).

## Como baixar e configurar o projeto localmente

Para baixar e configurar o projeto em sua máquina local, siga os passos abaixo:

### 1. Clonando o repositório

Primeiro, clone o repositório do projeto usando o Git:

```bash
git clone https://github.com/hersonpc/ciencia.git
cd ciencia
```

### 2. Criando um ambiente virtual

É recomendável criar um ambiente virtual para instalar as dependências do projeto. Isso evita conflitos de versões e mantém o ambiente isolado.

#### No Windows

```bash
python -m venv venv
.\venv\Scripts\activate
```

#### No Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Instalando as dependências

Com o ambiente virtual ativado, instale as dependências necessárias:

```bash
pip install -r requirements.txt
```

## Executar como serviço local

Após configurar o ambiente, você pode rodar a documentação localmente como um serviço para visualizá-la no navegador.

Use o comando abaixo para iniciar o servidor local do MkDocs:

```bash
make serve

# ou 

mkdocs serve -a 0.0.0.0:7765
```

O comando irá iniciar o servidor na máquina local, geralmente no endereço http://127.0.0.1:7765/. Abra este endereço em seu navegador para visualizar a documentação.

