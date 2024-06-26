# ProjetoMySql-Oficina-mecanica
Projeto de desenvolvimento de um modelo de banco de dados para uma Oficina Mecanica no MYSQL
![image](https://github.com/cibelemoraes/ProjetoMySql-Oficina-mecanica/assets/93668580/3e7d9d1d-da59-4687-888f-9dd2ab27bfb3)
# Banco de Dados para Oficina Mecânica

## Descrição

Este projeto apresenta a modelagem de um banco de dados relacional para gerenciar uma oficina mecânica. Utilizamos o MySQL Workbench para criar um esquema que organiza informações de clientes, veículos, ordens de serviço, equipes, funcionários e serviços oferecidos.
## linguagem utilizada
sql
## Estrutura das Tabelas

- **Clientes**: Informações dos clientes.
- **Veiculo**: Detalhes dos veículos.
- **Clientes_has_Veiculo**: Relaciona clientes e veículos.
- **OrdemServico**: Gerencia ordens de serviço.
- **Equipe**: Informações das equipes de trabalho.
- **Funcionario**: Dados dos funcionários.
- **Servico**: Descrição dos serviços oferecidos.
- **Servico_has_OrdemServico**: Relaciona serviços com ordens de serviço.
- **TabelaPreco**: Detalhes da tabela de preços.
- **TabelaDePreco_has_OrdemServico**: Relaciona tabelas de preços com ordens de serviço.

## Benefícios

- Melhora a organização e eficiência do atendimento ao cliente.
- Facilita o rastreamento de serviços e o monitoramento de equipes.
- Permite a geração de relatórios detalhados e análise de dados.

## Ferramentas Utilizadas

- **MySQL Workbench**: Para modelagem, criação e manipulação do banco de dados.

## Refinamentos

- Adicionar índices para consultas mais rápidas.
- Implementar triggers para automação.
- Garantir integridade referencial.
- Normalizar dados para evitar redundâncias.

## MySQL Workbench
O MySQL Workbench é uma ferramenta visual que permite a modelagem, criação e administração de bancos de dados MySQL. Oferece funcionalidades como design de diagramas ER, execução de consultas SQL, gerenciamento de usuários e configuração de backups. Essa modelagem é uma modelagem relacional, que organiza dados em tabelas relacionadas entre si por chaves estrangeiras.

projeto desenvolvido por cibele gomes domingos moraes lima 
