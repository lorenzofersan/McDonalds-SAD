# 🍔 McDonalds-SAD

Sistema de Apoio à Decisão para análise estratégica e otimização de operações em fast-food, utilizando dados reais do McDonald's.

## 📋 Descrição

McDonalds-SAD é um projeto acadêmico que aplica conceitos de **Sistema de Apoio à Decisão (SAD)** para resolver problemas operacionais reais do setor de fast-food. Através de análise de dados, consultas SQL estruturadas e visualizações interativas, o sistema responde perguntas críticas sobre:

- **Filas e tempos de espera**: Onde e por que se formam gargalos?
- **Otimização do cardápio**: Quais itens devem ser priorizados ou removidos?
- **Eficiência operacional**: Como reduzir custos sem comprometer qualidade?
- **Padrões de consumo**: Quando e o que os clientes mais pedem?

O projeto demonstra que **bons dados só apoiam decisões quando partem das perguntas certas**.

## 🎯 Problema Resolvido

**Desafio:** Filas grandes, operação lenta e cardápio complexo impactam satisfação do cliente e eficiência operacional.

**Solução:** Sistema baseado em dados que identifica:
- Produtos que mais impactam o tempo de preparo
- Horários de pico e necessidade de recursos
- Itens de baixo giro que podem ser removidos
- Oportunidades de otimização do fluxo de trabalho

## ✨ Funcionalidades

- **Análise de Cardápio**: Identificação de itens por categorias, valor nutricional e complexidade
- **Indicadores de Performance**: Cálculo de tempo médio de preparo e gargalos operacionais
- **Consultas SQL Estruturadas**: Queries prontas para responder perguntas de negócio
- **Dashboard Interativo**: Visualização dos principais KPIs e insights (se implementado)
- **Relatório Executivo**: Documentação completa com recomendações estratégicas

## 🚀 Tecnologias Utilizadas

- **SQL** - Consultas, tratamento e análise de dados
- **Python** - Scripts de processamento e análise (se aplicável)
- **Kaggle Dataset** - Base de dados real do McDonald's
- **Claude Code** - Assistente de desenvolvimento e análise

## 📊 Base de Dados

O projeto utiliza dados públicos do Kaggle:
- **Dataset**: McDonald's Menu Items
- **Fonte**: [Kaggle - McDonald's Menu](https://www.kaggle.com/)
- **Conteúdo**: Informações nutricionais, categorias, preços e composição de produtos

## 📦 Instalação

Clone o repositório:

```bash
git clone https://github.com/lorenzofersan/McDonalds-SAD.git
cd McDonalds-SAD
```

## 🏃 Como Executar

### 1. Preparar os Dados

Baixe o dataset do Kaggle e coloque na pasta `dados/`:

```bash
# Estrutura esperada:
dados/
└── mcdonalds_menu_items.csv
```

### 2. Executar Análises SQL

Execute as consultas disponíveis em `src/`:

```sql
-- Exemplo: Análise de itens por categoria
SELECT category, COUNT(*) as total_items
FROM menu_items
GROUP BY category
ORDER BY total_items DESC;
```

### 3. Visualizar Dashboard (se disponível)

Abra os arquivos em `dashboard/` no navegador ou ferramenta de BI compatível.

## 📁 Estrutura do Projeto

```
McDonalds-SAD/
├── dados/              # Datasets e bases de dados
│   └── LEIAME.txt
├── src/                # Consultas SQL e scripts de análise
│   └── LEIAME.txt
├── dashboard/          # Arquivos de dashboard e visualizações
│   └── LEIAME.txt
├── docs/               # Documentação e relatórios
│   ├── imagens/        # Gráficos e capturas de tela
│   └── LEIAME.txt
├── README.md           # Este arquivo
└── .gitignore          # Arquivos ignorados pelo Git
```

## 🎯 Principais Resultados

### Insights Obtidos:

1. **Identificação de gargalos**: Produtos que mais impactam tempo de fila
2. **Otimização de cardápio**: Sugestões de itens para promoção ou remoção
3. **Análise nutricional**: Padrões de calorias, gorduras e açúcares por categoria
4. **Recomendações estratégicas**: Ações baseadas em dados para melhorar operação

### Perguntas Respondidas:

- Quais categorias têm mais itens no cardápio?
- Qual a distribuição calórica dos produtos?
- Quais itens são mais complexos de preparar?
- Como otimizar o mix de produtos para reduzir filas?

## 📈 Metodologia

1. **Coleta de Dados**: Obtenção de dataset público e confiável
2. **Definição do Problema**: Mapeamento das perguntas de negócio
3. **Análise Exploratória**: Entendimento dos dados e padrões
4. **Consultas Estruturadas**: Desenvolvimento de queries SQL para responder perguntas
5. **Visualização**: Criação de dashboards e gráficos
6. **Recomendações**: Propostas baseadas nos insights encontrados

## 🔧 Tecnologias e Ferramentas

| Ferramenta | Uso |
|------------|-----|
| SQL | Consultas e análise de dados |
| Python | Scripts de processamento (opcional) |
| Excel/Power BI | Visualizações e dashboards |
| Git/GitHub | Controle de versão e documentação |
| Claude Code | Desenvolvimento assistido por IA |

## 📝 Contexto Acadêmico

Este projeto foi desenvolvido como parte da disciplina de **Sistemas de Informação e Decisão**, aplicando conceitos de:

- Sistemas de Apoio à Decisão (SAD)
- Business Intelligence (BI)
- Análise de Dados
- Tomada de Decisão Baseada em Dados
- Otimização de Processos Operacionais

## 🎓 Aprendizados

- Formulação de perguntas estratégicas a partir de problemas de negócio
- Manipulação e análise de grandes volumes de dados
- Desenvolvimento de consultas SQL complexas
- Tradução de insights em recomendações acionáveis
- Documentação técnica e apresentação de resultados

## 🤝 Contribuições

Contribuições, sugestões e melhorias são bem-vindas! Sinta-se à vontade para:

- Abrir issues com sugestões
- Enviar pull requests com melhorias
- Compartilhar feedback sobre as análises
- Propor novas perguntas de negócio

## 📧 Contato

**Lorenzo Ferreira**

- LinkedIn: [lorenzo-ferreira-37695a249](https://www.linkedin.com/in/lorenzo-ferreira-37695a249/)
- GitHub: [@lorenzofersan](https://github.com/lorenzofersan)
- Projeto: [McDonalds-SAD](https://github.com/lorenzofersan/McDonalds-SAD)

## 📄 Licença

Este projeto é desenvolvido para fins acadêmicos e de portfólio. Livre para uso educacional e referência.

---

**Desenvolvido com 🧠 dados e 🎯 foco em decisões estratégicas**

*Projeto acadêmico demonstrando aplicação prática de Sistemas de Apoio à Decisão no setor de fast-food* • 2024-2026
