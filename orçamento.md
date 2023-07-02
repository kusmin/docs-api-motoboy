# Orçamento do Projeto: API NodeJs Socket Microservices

## Descrição do Trabalho

Aprimorar a atual API em Node.js do aplicativo de motoboy, implementando um modelo de microservices serverless e corrigindo bugs existentes. Além disso, incluir uma nova funcionalidade que permite a cada motoboy aceitar até 4 corridas simultâneas e desenvolver uma robusta estratégia de testes e validação.

## Detalhamento do Orçamento

O preço estabelecido é de **R$ 40/hora**. Aqui está o detalhamento das horas necessárias para cada etapa do projeto:

### 1. Documentação da API atual

- Montagem do Swagger atual e modelo de dados: **2h**

### 2. Análise da API Atual

- Análise da API atual: **2h**
- Revisão de cada endpoint (16 endpoints): **16h**

### 3. Novas Features

#### Desenvolvimento e Implementação das corridas

- Correção, validação e implementação das corridas, podendo pedir, aceitar e finalizar as corridas solicitadas: **8h**
- Implementação da condição de poder aceitar ate 4 corridas simultanea: **4h**
- Implementação da logica de prioridades das corridas, verificando primeiro pelo trajeto, depois por proximidades e favoritos: **6h**

#### Implementação de favoritos

- Criação de funcionalidade para que a loja posso favoritar os motoristas: **3h**

### 4. Testes e Validação

- Validação e criação de testes unitários: **4h**

### 5. Criação do CI/CD e deploy

- Criação do modelo para implantação automatica via github actions: **2h**
- Criação do servidor EC2 ou LambdaFuncition e implantação: **2h**

### 6. Migração para NestJS

- Migração do projeto para NestJS: **8h**

## Total de Horas e Custo

O total de horas estimado para o projeto é de **50 horas**. Portanto, o custo total do projeto, a um preço de R$ 40/hora, seria de **R$ 2.000**. Com a migração para o NestJs seria mais **R$ 320**.

## Cronograma Previsto

- Montagem do Swagger atual e modelo de dados: 2h
- Análise da API atual: 2h
- Revisão de cada endpoint: 16h
- Implementação da lógica das novas funcionalidades: 16h
- Validação e criação de testes unitários: 4h

**Total: 44 horas**

Por favor, note que estes custos e prazos são estimados com base nas informações fornecidas e podem sofrer alterações dependendo de mais detalhes do projeto.

