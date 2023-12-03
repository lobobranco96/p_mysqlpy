# PROJETO 2 - ETL 

Descrição do Projeto

Este projeto tem como objetivo realizar um processo de ETL (Extração, Transformação e Carga) para manipulação e movimentação de dados. Os passos principais são:

Extração (Extract):

Criação de dados aleatórios utilizando um sistema de geração simulada.
Armazenamento dos dados em um DataFrame.

Transformação (Transform):

Utilização do MySQL Connector para conectar-se a uma instância do Azure Database for MySQL.
Armazenamento dos dados gerados no banco de dados, incluindo a aplicação de transformações necessárias.

Carga (Load):

Criação de três visualizações (views) a partir dos dados armazenados no banco de dados.
Organização e estruturação dos dados para facilitar o acesso.

Transferência para o Azure Blob Storage:
Utilização de uma pipeline de cópia de dados para transferir os dados para o Azure Blob Storage, um armazenamento em nuvem.

Componentes Utilizados
Linguagem de Programação: Python
Ferramentas: MySQL Connector, Azure Database for MySQL, Azure Blob Storage
Estrutura de Dados: DataFrame
Plataforma: Azure

Instruções de Execução
Configuração do Ambiente:

Certifique-se de ter o MySQL Connector instalado.
Configure as credenciais de acesso ao Azure.
Execução do Projeto:

Execute o script de geração de dados.
Execute o script de transformação e carga no banco de dados.
Verifique as visualizações criadas no banco de dados.
Transferência para o Azure Blob Storage:

Configure a pipeline de cópia de dados para transferir os dados para o Azure Blob Storage.
