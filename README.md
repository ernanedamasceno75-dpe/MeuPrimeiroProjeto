# Sistema de Gestão de Contratos e Cálculo de Salário Mensal (C# / OOP)

Este projeto é uma aplicação de consola desenvolvida em C# para praticar Programação Orientada a Objetos (OOP).  
O sistema permite registar os dados de um trabalhador, incluindo o seu **salário base**, bem como os seus contratos por hora.  
Com base num mês/ano fornecido pelo utilizador, o programa calcula o **salário total**, que corresponde ao salário base **mais** a soma dos valores dos contratos realizados naquele período.

## 🧩 Funcionalidades

- Registo dos dados do trabalhador: nome, nível, departamento e **salário base**
- Registo de múltiplos contratos (valor por hora e duração)
- Cálculo do rendimento mensal com base:
  - no **salário base**
  - + contratos realizados no mês indicado
- Filtragem de contratos com base no mês/ano fornecido pelo utilizador
- Exibição do salário final do trabalhador no período selecionado

## 🏗️ Estrutura do Projeto (OOP)

O projeto utiliza vários conceitos de Programação Orientada a Objetos:

- **Worker** → Representa o trabalhador e armazena o salário base
- **WorkerLevel** → Enum com o nível do trabalhador (Junior, MidLevel, Senior)
- **HourContract** → Representa contratos com valor/hora e duração
- **Department** → Departamento ao qual o trabalhador pertence
- **Program.cs** → Ponto de entrada da aplicação

Conceitos reforçados:
- Composição de objetos  
- Enumerações  
- Listas de contratos  
- Métodos encapsulados para cálculo de rendimento  
- Separação de responsabilidades  

## 🛠️ Tecnologias utilizadas

- C#
- .NET
- Programação Orientada a Objetos (OOP)

## 🚀 Objetivo do projeto

Este projeto foi criado para consolidar conhecimentos em:
- Modelação de classes e objetos
- Composição e relacionamentos entre entidades
- Estruturação de lógica de negócio
- Manipulação de datas
- Interação com o utilizador por consola

## 📚 Aprendizagens principais

- Como calcular um salário baseado em múltiplas fontes (salário base + contratos)
- Como filtrar contratos por mês e ano
- Como organizar um sistema utilizando OOP de forma clara e modular
- Como estruturar um pequeno projeto realista de back-end em C#
