# Global-Solution-SERS
- Pedro Henrique dos Santos Cardoso,RM563268
- Rafael do Nascimento Silva,RM566263

# Análise de Eficiência Energética em Escritórios Híbridos
## Smart Office 2025 - Projeto de Otimização Energética

### Sobre o Projeto

Este projeto investiga como os escritórios modernos podem otimizar o consumo energético em um contexto de trabalho híbrido. Através da simulação de um ambiente corporativo real, foram identificados os principais pontos de desperdício energético e desenvolvidas soluções práticas e viáveis para implementação.

### O Problema

A migração para o trabalho híbrido reduziu significativamente a ocupação dos escritórios, porém os sistemas energéticos continuam operando como se houvesse ocupação total. Esta desconexão entre presença real e consumo energético representa uma oportunidade significativa de otimização tanto econômica quanto ambiental.

### Metodologia

#### 3.1 Ambiente Simulado
O estudo baseia-se na simulação de um escritório corporativo moderno com as seguintes características:
- **Capacidade:** 200 funcionários distribuídos em 5 andares
- **Modelo de Trabalho:** Híbrido com 60-80% de ocupação presencial
- **Período de Análise:** 12 meses completos (8.760 registros horários)
- **Setores Analisados:** Servidores de TI, Segurança, Elevadores, Ventilação, Iluminação, Ar Condicionado, Equipamentos e Salas de Reunião

#### 3.2 Base de Dados
A simulação foi construída utilizando:
- Padrões de consumo energético corporativo documentados
- Tendências de ocupação híbrida observadas em 2024-2025
- Parâmetros técnicos de equipamentos comerciais
- Variações sazonais e comportamentais típicas do ambiente corporativo

#### 3.3 Parâmetros Técnicos
- **Tarifa energética:** R$ 0,65/kWh (média nacional comercial)
- **Fator de emissão:** 0,084 kg CO₂/kWh (matriz brasileira)
- **Horário comercial:** 8h às 18h, segunda a sexta-feira
- **Taxa de desconto:** 8% a.a. para análise de viabilidade

### Principais Descobertas

A análise revelou padrões significativos de desperdício energético:

**Consumo por período:**
- 45% do consumo total ocorre fora do horário comercial
- 25% acontece durante fins de semana com apenas 2% de ocupação
- Correlação fraca (r=0.23) entre ocupação e consumo no período noturno

**Desperdícios identificados por setor:**
- **Ar condicionado:** 43.464 kWh/ano em operação com baixa ocupação (<30%)
- **Iluminação:** 70.448 kWh/ano com luzes acesas em ambientes desocupados
- **Equipamentos:** Modo standby desnecessário em 30% das salas de reunião

**Impacto financeiro atual:**
- Custo energético anual: R$ 673.419
- Desperdício fora do horário: R$ 303.702/ano
- Desperdício em fins de semana: R$ 170.754/ano

### Propostas de Otimização

**Proposta 1: Sistema de Automação Inteligente**

Implementação de sensores de ocupação integrados com sistema de IA para predição de padrões de uso e automação responsiva.

*Especificações técnicas:*
- Sensores de presença por zona com conectividade IoT
- Algoritmos de machine learning para predição ocupacional
- Integração com sistemas HVAC e iluminação existentes
- Interface de monitoramento em tempo real

*Resultados projetados:*
- Economia energética: 127.592 kWh/ano
- Economia financeira: R$ 82.935/ano
- Redução CO₂: 10.718 kg/ano
- Investimento: R$ 150.000 | ROI: 55,3% a.a. | Payback: 1,8 anos

**Proposta 2: Otimização de Horários Não-Comerciais**

Sistema de gestão temporal com desligamento programado e standby inteligente para equipamentos não-críticos.

*Estratégias de implementação:*
- Programação automática 19h-7h para sistemas não-essenciais
- Modo standby adaptativo baseado em calendário corporativo
- Manutenção de sistemas críticos (segurança, servidores)
- Ativação sob demanda via aplicativo móvel

*Resultados projetados:*
- Economia energética: 129.071 kWh/ano
- Economia financeira: R$ 83.896/ano
- Redução CO₂: 10.842 kg/ano
- Investimento: R$ 50.000 | ROI: 167,8% a.a. | Payback: 0,6 anos

**Proposta 3: Integração Fotovoltaica**

Sistema solar de 200kWp com armazenamento e conexão à rede elétrica.

*Especificações do sistema:*
- Painéis fotovoltaicos policristalinos 200kWp
- Sistema de armazenamento em baterias de lítio
- Inversor grid-tie com monitoramento remoto
- Geração estimada: 109.500 kWh/ano

*Resultados projetados:*
- Autoconsumo: 18.310 kWh/ano (70% da geração)
- Economia financeira: R$ 11.902/ano
- Redução CO₂: 1.538 kg/ano
- Investimento: R$ 800.000 | ROI: 1,5% a.a. | Payback: 67,2 anos

### Análise Consolidada

**Impacto energético integrado:**
- Economia total: 274.973 kWh/ano (26,5% do consumo atual)
- Consumo final projetado: 761.056 kWh/ano
- Eficiência per capita: Redução de 14,2 para 10,4 kWh/funcionário/dia

**Viabilidade econômica:**
- Investimento total recomendado: R$ 200.000 (Propostas 1+2)
- Retorno anual: R$ 166.831/ano
- ROI consolidado: 83,4% ao ano
- Payback: 1,2 anos
- VPL (10 anos, 8% a.a.): R$ 918.507

**Impacto ambiental:**
- Redução de emissões: 21.560 kg CO₂/ano
- Equivalência: Plantio de 980 árvores ou remoção de 4,7 veículos de circulação
- Contribuição para metas corporativas de carbono neutro

### Aplicabilidade no Futuro do Trabalho

**Adaptabilidade aos modelos híbridos:**
O sistema proposto oferece flexibilidade operacional essencial para ambientes com ocupação variável, ajustando automaticamente o consumo energético à demanda real de espaço e recursos.

**Benefícios competitivos:**
- Redução de 25% nos custos operacionais energéticos
- Diferencial ESG para atração de talentos
- Compliance com regulamentações ambientais emergentes
- Melhoria na classificação energética predial

**Escalabilidade setorial:**
As soluções desenvolvidas são aplicáveis a diversos segmentos: escritórios corporativos, instituições educacionais, espaços de coworking e complexos comerciais com adaptações específicas.

### Implementação Recomendada

**Fase 1 (Meses 1-6): Projeto Piloto**
- Implementação da automação em um andar
- Instalação de sensores e sistema de controle
- Coleta de dados e calibração de algoritmos
- Validação de economia energética

**Fase 2 (Meses 7-12): Expansão Controlada**
- Extensão para todo o edifício
- Implementação da gestão de horários
- Treinamento de equipes operacionais
- Desenvolvimento de KPIs de acompanhamento

**Fase 3 (Meses 13-24): Otimização Avançada**
- Refinamento de algoritmos de IA
- Integração com sistemas corporativos
- Avaliação de viabilidade solar
- Estabelecimento de benchmarks setoriais

### Ferramentas e Tecnologias

**Desenvolvimento e análise:**
- Python para simulação de dados e modelagem estatística
- Pandas/NumPy para manipulação de grandes volumes de dados
- Matplotlib/Plotly para visualização de resultados

### Conclusão

A análise demonstrou que a otimização energética em ambientes de trabalho híbridos representa uma oportunidade excepcional tanto do ponto de vista econômico quanto ambiental. Os resultados nos surpreenderam pela magnitude do potencial de economia identificado: um ROI de 83% ao ano com payback inferior a 1,5 anos raramente é encontrado em projetos de infraestrutura.

Mais do que números, este projeto evidencia que a transição para o futuro do trabalho requer uma rethinking completo dos sistemas prediais. Não se trata apenas de economia de energia, mas de criar ambientes verdadeiramente adaptativos que respondem às necessidades reais dos usuários.
