# Automação de Gestão de Hora Extra

## Visão Geral

Este projeto foi desenvolvido durante meu período de estágio com o objetivo de melhorar um processo já existente de gestão de Hora Extra.

A solução integra formulários, planilhas, tratamento de dados, regras de negócio e dashboards operacionais em um único fluxo de trabalho.

O foco principal foi reduzir atividades manuais, padronizar informações e aumentar a confiabilidade do processo operacional.

## Problema

O processo original já existia, porém dependia de múltiplas planilhas, atualizações manuais e consolidação de informações realizadas pelos usuários.

Os principais desafios identificados eram:

- Consolidação manual de informações;
- Repetição de lançamentos;
- Cálculos realizados manualmente;
- Possibilidade de dados duplicados;
- Falta de padronização das informações;
- Dependência de conhecimento operacional para manutenção das planilhas;
- Baixa visibilidade dos indicadores.

O objetivo do projeto foi reestruturar esse fluxo e automatizar as principais atividades operacionais.

## Solução

A solução foi desenvolvida utilizando Microsoft Forms, Excel, Power Query e VBA.

O projeto foi dividido em três partes principais.

### Coleta de Dados

- Formulário de Disponibilidade;
- Formulário de Solicitação de Hora Extra.

### Tratamento e Integração

- Banco auxiliar de colaboradores;
- Tratamento de dados com Power Query;
- Consolidação das informações;
- Padronização dos dados.

### Automação Operacional

- Processamento automático de IPNs;
- Aplicação de regras de negócio;
- Identificação automática de colaboradores;
- Geração automática de indicadores;
- Sincronização de solicitações;
- Recuperação automática da planilha operacional.

## Tecnologias Utilizadas

- Microsoft Excel
- VBA
- Power Query
- Microsoft Forms
- Tabelas Dinâmicas
- Segmentações de Dados
- Análise de Dados

## Arquitetura do Processo

### Base Auxiliar

Banco de Colaboradores

↓

Utilizado pelas planilhas para:

- Identificação de colaboradores;
- Busca de IPN;
- Turno;
- Supervisor;
- Classificação MOD/MOS.

### Fluxo Operacional

Microsoft Forms - Disponibilidade

↓

Planilha de Disponibilidade

↓

Microsoft Forms - Solicitação de Hora Extra

↓

Planilha de Solicitações

↓

SEGUIMENTO DAS ATIVIDADES HE

↓

Power Query

↓

Tabela SOLICITAÇÕES

↓

Processamento VBA

↓

Tabela HORA EXTRA

↓

Dashboards e Indicadores Operacionais

## Capturas do Projeto

### Banco de Dados de Colaboradores

IMAGES/01%20-%20Banco%20de%20Dados.png

### Processo ETL com Power Query

IMAGES/03%20-%20Power%20Query.png

### Consolidação de Dados

IMAGES/05%20-%20Mesclagem%20de%20Semana%20atual%20e%20fluxo%20Power%20Query.png

### Atualização das Solicitações

IMAGES/07%20-%20Atualização%20Solicitações.png

### Processamento Automático com VBA

IMAGES/09%20-%20Dados%20Atualizados%20agora%20por%20VBA.png

### Identificação Automática por IPN

IMAGES/10%20-%20IPN%20Puxa%20dados.png

### Recuperação da Planilha Operacional

IMAGES/11%20-%20Redefinir%20Aba.png

### Planilha Restaurada

IMAGES/12%20-%20Aba%20Redefinida.png

## Principais Funcionalidades

- Banco auxiliar de colaboradores;
- Integração entre formulários e planilhas;
- Processo ETL utilizando Power Query;
- Processamento automático de IPNs;
- Aplicação automática de regras de negócio;
- Controle de solicitações;
- Dashboards gerenciais;
- Indicadores operacionais;
- Recuperação automática da planilha operacional;
- Padronização das informações.

## Aprendizados

Durante o desenvolvimento deste projeto aprimorei conhecimentos em:

- VBA;
- Power Query;
- ETL;
- Modelagem de Dados;
- Automação de Processos;
- Dashboards Operacionais;
- Integração Microsoft Forms;
- Estruturação de Regras de Negócio;
- Padronização de Fluxos Operacionais.

## Estrutura do Repositório

```text
IMAGES/
TEMPLATES/
VBA/
README.md
```
## Autor

Gabriel Pereira

Estudante de Engenharia de Software

Automação | Power Query | VBA | Análise de Dados

Desenvolvendo soluções para automação de processos utilizando ferramentas do ecossistema Microsoft.
