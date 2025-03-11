### 📊 **Analisando a Campanha de Marketing do Banco**  

#### 📌 **Sobre o Projeto**  

Este projeto analisa uma campanha de marketing feita por um banco para promover depósitos a prazo. O banco usou ligações telefônicas para entrar em contato com os clientes, e nosso objetivo é entender quais fatores influenciaram a decisão de aderir ou não à campanha. A análise foi feita com o **Bank Marketing Dataset**, disponível no Kaggle. 

https://www.kaggle.com/datasets/janiobachmann/bankmarketing-dataset/data

![imagem](imagens/depósito_a_prazo.PNG).                                                                                                                       
Fonte: https://literciafinanceira.com/depositos-a-prazo-ou-certificados-de-aforro-em-2024-qual-compensa-mais/



Para conduzir essa análise, aplicamos a **metodologia dos seis passos da análise de dados**, estudada no curso do Google:  

1️⃣ **Ask (Perguntar):** Definição das principais questões a serem respondidas com base nos dados.                                                                                         
2️⃣ **Prepare (Preparar):** Coleta e organização do banco de dados **Bank Marketing Dataset**, disponível no Kaggle.  
3️⃣ **Process (Processar):** Limpeza e transformação dos dados para garantir sua qualidade.  
4️⃣ **Analyze (Analisar):** Exploração dos dados, aplicação de estatísticas e criação de visualizações para identificar padrões.  
5️⃣ **Share (Compartilhar):** Comunicação dos insights de forma clara e visual.  
6️⃣ **Act (Agir):** Interpretação dos resultados e recomendações para otimizar futuras campanhas.  

#### 🔎 **ASK - Perguntas Gerais Sobre a Campanha**  

📌 **Qual é a taxa de sucesso geral da campanha?**  

📌 **Qual é o perfil demográfico dos clientes que mais aderiram (idade, profissão, estado civil, nível de educação)?**  
 
## 📌 Objetivo
O objetivo deste projeto é identificar os principais fatores que influenciam os clientes a aderirem à campanha e depositarem dinheiro em uma conta a prazo.

## 🗂 Estrutura do Projeto

- `bank_marketing_analysis.Rmd`: Código e análise completa em RMarkdown.
- `bank_marketing_analysis.R`: Código principal em R.
- `data/`: Contém a base de dados original e tratada.
- `reports/`: Relatório em PDF com os resultados e insights.
- `visualizations/`: Gráficos gerados para a análise.

## 🛠 Ferramentas Utilizadas

- 📌 **R** (ggplot2, dplyr, caret)
- 📌 **RStudio**
- 📌 **Kaggle** (Fonte do dataset)
- 📌 **GitHub** (Compartilhamento do código)

### 📌 **Principais Insights Obtidos**  

Com base na análise dos dados, identificamos o perfil do cliente com maior probabilidade de aderir ao depósito a prazo. Esses insights podem ser usados para direcionar futuras campanhas de marketing, aumentando sua eficácia.  

📌 **📈 Perfil do Cliente Ideal para Depósito a Prazo:**  

✔ **Idade**: Clientes idosos (60 a 95 anos) e jovens (18 a 23 anos) demonstraram maior interesse na oferta.  

✔ **Profissão**: Estudantes e aposentados foram os grupos que mais aceitaram a proposta.  

✔ **Estado Civil**: Solteiros tiveram uma maior taxa de adesão em comparação com casados e divorciados.  

✔ **Escolaridade**: Pessoas com ensino superior demonstraram maior propensão a aceitar o depósito a prazo.  

✔ **Saldo Bancário**: Clientes com saldos mais altos tendem a aderir mais facilmente ao produto.  

✔ **Histórico Financeiro**: Clientes sem dívidas ou empréstimos (pessoais e imobiliários) foram os que mais aceitaram a oferta.  

🔎 **Conclusão:**  
A análise mostra que clientes **mais jovens e mais velhos**, com **bom histórico financeiro** e **nível educacional mais alto**, são os mais propensos a aderir ao produto. Com essas informações, o banco pode **personalizar as abordagens de marketing**, focando nesses grupos para aumentar a taxa de conversão. 


## Organização do projeto

```

├── .gitignore         <- Arquivos e diretórios a serem ignorados pelo Git
├── ambiente.yml       <- O arquivo de requisitos para reproduzir o ambiente de análise
├── LICENSE            <- Licença de código aberto (MIT)
├── README.md          <- README principal para desenvolvedores que usam este projeto.
|
├── dados              <- Arquivos de dados para o projeto.
|
|
├── notebooks          <- Jupyter Notebooks com tratamento e análise dos dados.
│
|   └──src             <- Código-fonte para uso neste projeto.
|      │
|      ├── __init__.py  <- Torna um módulo Python
|      └──config.py    <- Configurações básicas do projeto
|    
|
├── referencias        <- Dicionários de dados
|
├── relatorios         <- Análises geradas em HTML, PDF, LaTeX, etc.
│   └── imagens        <- Imagens usadas no projeto
```

## Configuração do ambiente

1. Faça o clone do repositório.

    ```bash
    git@github.com:DanFalcari/ETL_Pipeline_Azure_Databricks.git
    ```
