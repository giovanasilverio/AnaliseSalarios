# 📊 Análise de Salários de Desenvolvedores

Projeto desenvolvido para a disciplina de **Métodos Matemáticos para Análise de Dados**. Este projeto realiza uma análise exploratória dos salários de desenvolvedores utilizando dados extraídos de um arquivo CSV, aplicando métodos matemáticos e estatísticos para extrair insights relevantes.

## 📑 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Objetivos](#objetivos)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Análise Realizada](#análise-realizada)
- [Contribuição](#contribuição)

## Sobre o Projeto

O projeto visa estudar e compreender a distribuição salarial de desenvolvedores, identificando tendências, possíveis variáveis influentes e comparando métricas como média, mediana e variância dos salários.

Os dados analisados estão em um arquivo **CSV**, contendo informações como:

- Nível de experiência (junior, pleno, sênior)
- Localização
- Tipo de emprego (remoto, presencial, híbrido)
- Faixa salarial

## Objetivos

1. **Explorar e limpar os dados**: Garantir a qualidade dos dados, tratando valores nulos ou inconsistentes.
2. **Analisar a distribuição salarial**: Observar estatísticas como média, mediana, desvio padrão e variância dos salários.
3. **Encontrar correlações**: Examinar a relação entre salário e variáveis como experiência e localização.
4. **Visualizar os dados**: Utilizar gráficos para ilustrar as principais tendências e insights.

## Tecnologias Utilizadas

- **Python 3.8+**
- **Pandas**: Para manipulação e análise de dados.
- **NumPy**: Para cálculos matemáticos e estatísticos.
- **Matplotlib / Seaborn**: Para visualização de dados.
- **Kaggle**: Fonte dos datasets em formato CSV utilizados no projeto.

## Como Executar o Projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/analise-salarios-desenvolvedores.git
   ```
2. **Navegue até o diretório do projeto**:
   ```bash
   cd analise-salarios-desenvolvedores
   ```
3. **Instale as dependências**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Execute o script de análise**:
   ```bash
   python analise_salarios.py
   ```

## Análise Realizada

- **Distribuição Salarial**: Visualização de histogramas e boxplots para diferentes níveis de experiência.
- **Análise Comparativa**: Comparação salarial entre desenvolvedores remotos, presenciais e híbridos.
- **Correlação entre Variáveis**: Cálculo e visualização de correlações entre salário e variáveis como experiência e localização.
- **Insights Principais**: Resumo das principais conclusões da análise.

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto.
2. Crie uma nova branch: `git checkout -b minha-feature`
3. Commit suas mudanças: `git commit -m 'Adiciona nova análise'`
4. Push a branch: `git push origin minha-feature`
5. Abra um Pull Request.
