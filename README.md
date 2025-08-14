# HR_Turnover_Analysis

## Descrição
Este projeto apresenta um **painel do Power BI** que analisa as principais métricas de RH para entender e monitorar a **rotatividade de funcionários**. O dashboard fornece insights sobre departamentos, cargos, faixas salariais, satisfação, engajamento e tempo de empresa, ajudando o RH a tomar decisões estratégicas de retenção.

## Características do Painel
- **Visão geral do turnover:** visualiza a taxa de desligamentos e tendências ao longo do tempo.  
- **Análise demográfica:** mostra distribuição por gênero, idade, estado civil e outros atributos.  
- **Análise de cargo e faixa salarial:** avalia impacto do cargo e salário na rotatividade.  
- **Satisfação e engajamento:** analisa métricas de satisfação no trabalho e engajamento.  
- **Desempenho e estabilidade:** avalia tempo de empresa, histórico de promoções e avaliações de desempenho.  
- **Filtros interativos:** permitem detalhar departamentos, cargos, faixas salariais ou períodos específicos.

## Colunas de Dados
A base utilizada inclui os principais atributos de funcionários:

**Detalhes do funcionário:**  
`EmpID`, `Gender`, `MaritalStatus`, `Age`, `AgeGroup`  

**Trabalho e compensação:**  
`Department`, `Position`, `Salary`, `Faixa_Salarial`  

**Engajamento e satisfação:**  
`EmpSatisfaction`, `EngagementSurvey`, `WorkLifeBalance`  

**Desempenho e estabilidade:**  
`PerformanceScore`, `YearsAtCompany`, `YearsInCurrentRole`, `YearsWithCurrManager`  

**Fatores adicionais:**  
`DaysLateLast30`, `Absences`, `RecruitmentSource`, `OverTime`

## Medidas DAX Criadas
- **Total de Funcionários:** contagem de todos os funcionários.  
- **Total de Desligados:** contagem de funcionários desligados.  
- **Taxa de Turnover (%):** desligados / total.  
- **Médias de Satisfação e Engajamento:** separadas por ativos e desligados.  
- **Tempo de Empresa (anos):** cálculo baseado na data de contratação e desligamento (ou data atual).  
- **Quantidade por Faixa Salarial, Departamento e Cargo.**

## Uso
1. Clone o repositório e abra o arquivo `.pbix` no **Power BI Desktop**.  
2. Atualize a conexão com a sua base de dados de RH, se necessário.  
3. Explore os gráficos interativos para analisar tendências de rotatividade e identificar os principais fatores que influenciam o turnover.  
4. Use filtros para focar em departamentos, cargos, faixa salarial ou períodos específicos para insights mais detalhados.  

## Propósito
O painel serve como ferramenta de suporte para equipes de RH, permitindo:  
- Monitorar tendências de turnover.  
- Identificar grupos de funcionários com maior risco de desligamento.  
- Tomar decisões estratégicas para aumentar a retenção e engajamento.  

---

