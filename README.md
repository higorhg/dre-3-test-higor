# dre-test - Apache Airflow - Smooth Operator
<picture width="500">
  <img
    src="https://github.com/apache/airflow/blob/19ebcac2395ef9a6b6ded3a2faa29dc960c1e635/docs/apache-airflow/img/logos/wordmark_1.png?raw=true"
    alt="Apache Airflow logo"
  />
</picture>

## Pré-requisitos

Certifique-se de ter o Docker e o Docker Compose instalados em seu sistema antes de prosseguir.

## Como Usar

1. Clone este repositório em seu sistema local:
```
git clone https://github.com/higorhg/dre-3-test-higor.git
```
2. Navegue até o diretório clonado:
```
cd dre-3-test-higor
```
3. Crie um arquivo `.env` baseado no arquivo `env.example`. Você pode fazer isso executando o seguinte comando:
```
cp env.example .env
```
4. Edite o arquivo `.env` conforme necessário, ajustando as variáveis de ambiente de acordo com sua configuração.

5. Inicie os containers do Apache Airflow usando Docker Compose:
```
docker-compose up -d
```
Os containers serão criados e iniciados com base na configuração definida no arquivo `compose.yml`.

## Estrutura do Repositório

- `dags/`: Contém os arquivos de Definição de Fluxo de Dados (DAGs) do Apache Airflow.
- `plugins/`: Possível diretório para adicionar plugins personalizados do Airflow.
- `compose.yml`: Arquivo de definição do Docker Compose para os containers do Apache Airflow.
- `env.example`: Arquivo exemplo contendo variáveis de ambiente necessárias para configurar o ambiente do Apache Airflow.
