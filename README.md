# 📊 Análise de Dados sobre Violência Doméstica em Pernambuco

## 📌 Sobre o Projeto
Este projeto foi desenvolvido com o objetivo de analisar dados sobre **violência doméstica contra mulheres no estado de Pernambuco**, utilizando técnicas de **Data Science e Análise Exploratória de Dados (EDA)**. A pesquisa busca compreender padrões, fatores sazonais e lacunas nos dados, contribuindo para uma visão mais ampla do problema e incentivando políticas públicas mais eficazes.

## 📂 Dataset
O conjunto de dados utilizado foi obtido no site da **Secretaria de Defesa Social de Pernambuco (SDS-PE)**, contendo informações de **janeiro de 2015 a setembro de 2023** sobre ocorrências de violência doméstica no estado.

🔗 **Fonte dos dados**: [SDS-PE](https://www.sds.pe.gov.br/images/indicadores/violecia-domestica/MICRODADOS_DE_VIOL%C3%8ANCIA_DOM%C3%89STICA_JAN_2015_A_SET_2023.xlsx)

## 🛠️ Tecnologias Utilizadas
- **Python** 🐍
- **Pandas** (Manipulação de dados)
- **NumPy** (Cálculos estatísticos)
- **Matplotlib** (Visualização de dados)

## 🏗️ Etapas do Projeto
### 📖 1. Coleta e Pré-processamento
- Leitura dos dados em formato Excel.
- Verificação de colunas e estrutura do dataset.
- Filtragem para focar em vítimas do sexo feminino.

### 🔍 2. Limpeza e Tratamento dos Dados
- Renomeação de colunas para padronização.
- Tratamento de valores nulos, especialmente na coluna **idade**.
- Ajuste dos dados temporais para facilitar análises sazonais.

### 📊 3. Análise Exploratória (EDA)
- Identificação das regiões com maior incidência de casos.
- Estudo das categorias de violência mais comuns.
- Investigação sobre lacunas nos dados e possíveis razões para a ausência de informações.

### 📈 4. Visualização de Dados
- Gráficos de **barras** e **linhas** para distribuição de ocorrências por **ano, natureza da violência e região**.
- Comparação entre denúncias registradas e fatores sazonais que podem influenciar os casos.

## 🔎 Principais Descobertas
- **Padrões sazonais:** Aumento nos primeiros meses do ano, possivelmente relacionado a pressões financeiras e eventos sociais.
- **Ausência de dados de idade:** Fator possivelmente ligado a denúncias anônimas ou falta de suporte adequado às vítimas.
- **Tipos mais comuns de violência:** Ameaça, lesão corporal e maus-tratos.
- **Fatores que impedem denúncias:** Medo de retaliação, dependência financeira e estigma social.

## 🎯 Conclusão e Próximos Passos
A análise revelou importantes **lacunas de dados** e padrões de recorrência da violência doméstica. Os insights gerados podem contribuir para o desenvolvimento de **políticas públicas mais assertivas**. Futuramente, pretendemos:
- Enriquecer o estudo com dados complementares de outras fontes.
- Criar um **dashboard interativo** para visualização dos resultados.
- Explorar técnicas de **Machine Learning** para prever padrões de recorrência.

## 🚀 Como Executar o Projeto
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/projeto-violencia-domestica.git
   ```
2. Instale as dependências necessárias:
   ```bash
   pip install pandas numpy matplotlib
   ```
3. Execute o script principal:
   ```bash
   python analise_violencia.py
   ```

📢 **Este projeto visa contribuir para o debate sobre violência doméstica e fornecer insights que possam auxiliar na construção de um ambiente mais seguro para as mulheres.**

