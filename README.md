# Automacao-De-Processo
### Objetivo:
- Automatizar um processo que leia, manipule, trate e relacione diferentes bases de dados; crie novas tabelas e indicadores; e, por fim, envie para o e-mail do setor responsável as análises e comparações pertinentes. 

### Desenvolvimento: 
- Ler, manipular e relacionar as bases de dados iniciais;

- Criar uma pasta (Backup Aquivos Lojas), local onde serão armazenadas as novas tabelas criadas;

- Exportar as informações do Python para arquivos xlsx, então salvá-los na pasta [Backup Arquivos Lojas];

- Obter o dia indicador, data mais atual da base de dados (dia em que serão calculados os indicadores)

- Calcular indicadores anual e diário (dia indicador) para cada loja, e compará-los com a meta;

- Enviar um e-mail para o responsável de cada loja (25 lojas - 25 responsáveis - 25 e-mails) com a base de dados da sua respectiva loja (tabela criada anteriormente)
e com a comparação entre os indicadores anual e diário em relação à meta;

- Calcular indicadores gerais e criar um ranking entre as lojas;

- Enviar um e-mail para diretoria com a base de dados pertinente e comparação dos indicadores referentes ao ranking das lojas.


### Observações:
- Projeto desenvolvido em Python -> Jupyter Notebook, disponibilizado em [02 - Automação de Processo.ipynb].
- Todos os arquivos iniciais estão disponibilizados na pasta [Base de Dados].
- Todos os arquivos gerados pelo código estão disponibilizados na pasta [Backup Aquivos Lojas].
- Um exemplo da tabela gerada pelo código em HTML está disponibilizado no arquivo [01 - Exemplo OnePage HTML.png]
