📈 Análise Comparativa de Ações Brasileiras

Projeto de análise financeira utilizando Python para avaliar o desempenho de grandes empresas brasileiras listadas na B3, com dados históricos obtidos via Yahoo Finance.

📌 Objetivo

Este projeto tem como objetivo demonstrar técnicas de:

Coleta de dados financeiros
Manipulação de dados com Pandas
Visualização gráfica com Matplotlib e Seaborn
Análise comparativa de ações
Cálculo de métricas financeiras básicas

As análises foram realizadas utilizando dados históricos entre Janeiro de 2023 e Maio de 2026.

🏢 Empresas Analisadas
Empresa	Ticker
Petrobrás	PETR4.SA
Vale S.A.	VALE3.SA
Ambev S.A.	ABEV3.SA
Itaú Unibanco	ITUB4.SA
Banco do Brasil	BBAS3.SA
🛠️ Tecnologias Utilizadas
Python 3
Pandas
Matplotlib
Seaborn
yFinance
Google Colab / Jupyter Notebook
📂 Estrutura do Projeto
.
├── AdminAnáliseAções.ipynb
├── README.md
⚙️ Instalação das Dependências

Execute o comando abaixo:

!pip install yfinance pandas matplotlib seaborn

Ou via terminal:

pip install yfinance pandas matplotlib seaborn
▶️ Como Executar
Google Colab
Acesse o Google Colab
Faça upload do notebook
Execute as células sequencialmente
Jupyter Notebook
jupyter notebook

Depois abra o arquivo:

AdminAnáliseAções.ipynb
📊 Funcionalidades Implementadas
✔️ Coleta de Dados

Os dados são baixados automaticamente através da biblioteca yfinance.

Exemplo:

import yfinance as yf


ticker = "PETR4.SA"
dados = yf.download(ticker, start="2023-01-01", end="2026-05-14")
✔️ Tratamento de Dados
Ajuste de datas
Limpeza de valores nulos
Organização temporal
Conversão de tipos
✔️ Visualizações Gráficas

O projeto inclui:

Evolução do preço das ações
Volume negociado
Médias móveis
Comparações históricas
Tendências de mercado
✔️ Indicadores Financeiros

Algumas análises realizadas:

Retorno percentual
Variação acumulada
Comparação de desempenho
Tendência de valorização
📈 Exemplo de Gráfico
plt.plot(dados['Close'])
plt.title('Preço de Fechamento')
plt.show()
🎯 Aprendizados

Este projeto demonstra conhecimentos em:

Ciência de Dados
Análise Financeira
Visualização de Dados
Programação em Python
Manipulação de séries temporais
🚀 Possíveis Melhorias Futuras
Inclusão de indicadores técnicos
Dashboard interativo
Comparação automática entre ativos
Exportação de relatórios em PDF
Integração com APIs financeiras
Machine Learning para previsão de preços
📚 Referências
Yahoo Finance
Documentação do Pandas
Documentação do Matplotlib
Documentação do Seaborn
Documentação do yFinance
👨‍💻 Autor

Projeto desenvolvido para estudos de análise de dados financeiros utilizando Python.

⭐ Contribuições

Sinta-se à vontade para abrir:

Issues
Pull Requests
Sugestões de melhoria
📄 Licença

Este projeto é destinado para fins educacionais e de aprendizado.
