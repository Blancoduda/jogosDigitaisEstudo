# Análise de Jogos Eletrônicos

Este projeto tem como objetivo realizar uma análise exploratória de um conjunto de dados de jogos eletrônicos utilizando a linguagem Python. O foco principal é aplicar conceitos de programação, como manipulação de arquivos CSV, estruturas de dados, e orientação a objetos, sem a utilização de bibliotecas externas como NumPy ou Pandas.

## Estrutura do Projeto

O projeto é dividido em dois scripts principais:

1. **criar_amostra.py**: Este script cria uma amostra aleatória de jogos a partir do arquivo CSV original (amostra contendo 20 linhas).
2. **contador_csv.py**: Este script contém as classes responsáveis por realizar a contagem de jogos e cálculos de percentuais.

### Funcionalidades

- **Amostragem**: Cria uma amostra aleatória de jogos a partir de um arquivo CSV.
- **Contagem de Linhas**: Conta o total de jogos no arquivo CSV.
- **Cálculo de Percentuais**: Calcula o percentual de jogos gratuitos e pagos.
- **Contagem de Jogos por Ano**: Identifica os anos com o maior número de novos jogos lançados.
- **Média de Lançamentos por Mês**: Calcula a média de lançamentos de jogos por mês.

## Como Usar

1. **Configuração do Ambiente**: Certifique-se de ter o Python instalado em seu sistema.
2. **Arquivo CSV**: Coloque o arquivo CSV de jogos (exemplo: `steam_games.csv`) no diretório apropriado.
3. **Execução**:
   - Para criar a amostra, execute:
     ```bash
     python criar_amostra.py
     ```
   - Para realizar a contagem e as análises, execute:
     ```bash
     python contador_csv.py
     ```

### Classes Principais

- **ContadorCSV**: Esta classe realiza a leitura do arquivo CSV e fornece métodos para contar linhas, calcular percentuais de jogos gratuitos e pagos, contar jogos por ano, e calcular a média de lançamentos por mês.

### Exemplo de Uso

No script `contador_csv.py`, a execução do código principal fornece uma saída com as informações analisadas, como:

- Total de linhas no arquivo.
- Percentuais de jogos gratuitos e pagos.
- Anos com o maior número de lançamentos.
- Média de lançamentos de jogos por mês.

## Testes

O código inclui métodos de teste para verificar se os percentuais e a média de lançamentos estão corretos. Esses testes são executados automaticamente ao rodar o script principal.

## Contribuições

Sinta-se à vontade para contribuir com melhorias ou correções. Para isso, você pode criar uma nova branch e enviar um pull request.

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

