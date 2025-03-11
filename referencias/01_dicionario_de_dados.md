# Dicionário de dados bank.csv

## Colunas e Valores Presentes
O dataset contém várias colunas (atributos) que descrevem características dos clientes, detalhes da campanha de marketing e informações contextuais. Aqui estão as colunas e seus significados:

### Informações Demográficas dos Clientes: 
age: Idade do cliente (numérica).

- `age`: Idade do cliente (numérica)
- `job`: Tipo de emprego (categórica: admin, blue-collar, entrepreneur, housemaid, management, retired,
self-employed, services, student, technician, unemployed, unknown).
- `marital`: Estado civil (categórica: divorced, married, single).
- `education`: Nível de educação (categórica: primary, secondary, tertiary, unknown).
- `default`: Indica se o cliente tem crédito em inadimplência (categórica: no, yes, unknown).
- `balance`: Saldo médio anual em euros (numérica).
- `housing`: Indica se o cliente tem um empréstimo imobiliário (categórica: no, yes, unknown).
- `loan`: Indica se o cliente tem um empréstimo pessoal (categórica: no, yes, unknown).

### Informações Relacionadas à Campanha de Marketing:

- `contact`: Tipo de comunicação utilizada (categórica: cellular, telephone).
- `day`: Último dia do mês em que o cliente foi contatado (numérica: 1 a 31).
- `month`: Último mês em que o cliente foi contatado (categórica: jan, feb, mar, . . . , nov, dec).
- `duration`: Duração do último contato em segundos (numérica).
- `campaing`: Número de contatos realizados durante esta campanha para este cliente (numérica).
- `pdays`: Número de dias desde o último contato de uma campanha anterior (numérica: -1 indica que o cliente não foi contatado anteriormente).
- `previous`: Número de contatos realizados antes desta campanha (numérica).
- `pountcome`: Resultado da campanha de marketing anterior (categórica: failure, nonexistent, success).
- `pdays`: Quantidade de unidades compradas

### Variável Alvo (Target) 
  
- `deposit`: deposit: Indica se o cliente subscreveu o depósito a prazo (categórica: yes, no).



