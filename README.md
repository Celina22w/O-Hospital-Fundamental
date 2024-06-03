# 🏥Sistema de Gerenciamento Hospitalar

Este projeto visa desenvolver um sistema de gerenciamento hospitalar para um hospital local, focando no controle de consultas, internações, receitas médicas, e o gerenciamento de médicos, enfermeiros e pacientes.

📋Visão Geral

O sistema hospitalar ajudará na organização e digitalização dos dados do hospital, que atualmente são mantidos em planilhas e arquivos físicos. Este sistema permitirá um melhor gerenciamento das informações e melhorará a eficiência operacional.
> ### Parte 1
> Modelo Conceitual

## Entidades e Relacionamentos


O sistema consiste nas seguintes entidades principais e seus relacionamentos:

### Entidades

- **Médico**
- **Especialidade**
- **Médico_Especialidade**
- **Paciente**
- **Convenio**
- **Consulta**
- **Receita**


### Relacionamentos

- **Médico** e **Consulta**: Um médico pode realizar várias consultas.
- **Paciente** e **Consulta**: Um paciente pode ter várias consultas.
- **Consulta** e **Receita**: Uma consulta pode gerar várias receitas.
- **Médico** e **Especialidade**: Muitos-para-muitos através da tabela intermediária **Médico_Especialidade**.
- **Paciente** e **Convenio**: Um paciente pode ter um convênio.

- ## 🌐 Diagrama Entidade-Relacionamento

![Modelagem-conceitual1](https://github.com/Celina22w/O-Hospital-Fundamental/assets/160240761/9a69309c-efbe-4424-bcc1-785ffac07622)



> ### Parte 2
> Atualização do Diagrama

## 📊 Entidades Atualizadas do sistema:

**Enfermeiro**
- **Enfermeiro_Paciente**
- **Consulta_Enfermeiro**
- **Internacao**
### Relacionamentos  Atualizados do sistema:
- **Enfermeiro** e **Paciente**: Muitos-para-muitos através da tabela intermediária **Enfermeiro_Paciente**.
- **Consulta** e **Enfermeiro**: Muitos-para-muitos através da tabela intermediária **Consulta_Enfermeiro**.
- **Paciente** e **Internacao**: Um paciente pode ter várias internações.
- **Médico** e **Internacao**: Um médico pode ser responsável por várias internações.
- **Enfermeiro** e **Internacao**: Muitos-para-muitos (um enfermeiro pode cuidar de vários pacientes internados, e um paciente internado pode ser cuidado por vários enfermeiros).

## 🌐 Diagrama Entidade-Relacionamento Atualizado
