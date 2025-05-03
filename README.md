# Projeto - Colpocitologia Oncótica (2015)

![Saúde Pública](https://img.shields.io/badge/Área-Saúde_Pública-blue) ![Análise de Dados](https://img.shields.io/badge/Tipo-Análise_de_Dados-orange) ![Python](https://img.shields.io/badge/Linguagem-Python_SQL_DAX-yellow)

Estudo de caso sobre exames de Colpocitologia Oncótica (Papanicolau) realizados entre **maio e junho de 2015** na cidade de São Paulo.

## 📌 Contexto do Projeto

Os dados brutos foram extraídos do [Relatório Anual de Gestão - Saúde - Resultado e Indicadores PMS](https://dados.prefeitura.sp.gov.br/) (Repositório de Dados Abertos de São Paulo). 

⚠️ **Nota importante sobre a qualidade dos dados**:
- Os dados **não foram tratados ou limpos** intencionalmente para refletir fielmente a realidade do dataset original
- Existem discrepâncias naturais (ex.: coluna "Escolaridade" tem alta taxa de não-respostas)
- IDs foram gerados artificialmente apenas para fins de análise

## 🛠 Metodologia Técnica

### Fontes de Dados
- Dados crus em PDF/relatórios convertidos para formato estruturado com auxílio de IA (DeepSeek)
- Dataset final contém:
  - 5.214 registros de exames
  - Período: maio-junho/2015
  - Variáveis: Idade, Faixa Etária, Resultado (HSIL, LSIL, Normal, etc.), Escolaridade, Adequabilidade

### Abordagem Multitool

A[Dados Brutos] --> B(SQL: Modelagem e Consultas)
A --> C(Python: Análise Estatística)
A --> D(Power BI: Visualização)

/


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
