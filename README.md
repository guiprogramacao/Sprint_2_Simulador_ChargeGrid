# Sprint_2_Simulador_ChargeGrid

# ChargeGrid Intelligence

### Gestão Inteligente de Energia para Recarga de Veículos Elétricos

---

## Descrição do Projeto

O **ChargeGrid Intelligence** é uma solução voltada para o gerenciamento inteligente da distribuição de energia em ambientes comerciais com múltiplos pontos de recarga para veículos elétricos.

O projeto tem como objetivo otimizar o uso da energia disponível, evitar sobrecargas no sistema e garantir uma distribuição eficiente entre os veículos conectados, além de implementar um sistema de tarifação automatizado.

---

## Objetivo da Sprint 2

Nesta etapa do projeto, foi desenvolvida uma **prova de conceito funcional**, baseada na proposta da Sprint 1, com foco em:

* Simular um ambiente comercial com múltiplos carregadores
* Implementar controle inteligente de distribuição de energia
* Aplicar cálculo de tarifação automática
* Demonstrar a lógica do sistema de forma prática

---

## Funcionamento do Sistema

O sistema simula:

* Um número definido de veículos conectados
* Uma quantidade limitada de energia disponível
* Demandas diferentes para cada veículo

### Lógica de Distribuição

1. Cada veículo possui uma demanda de energia
2. O sistema prioriza veículos com maior necessidade
3. A energia é distribuída de forma controlada
4. O sistema evita ultrapassar o limite total disponível

---

## Tecnologias Utilizadas

* Python
* Biblioteca `random` (simulação de demanda)
* Biblioteca `matplotlib` (visualização gráfica)

---

## Principais Funcionalidades

### Controle Inteligente de Demanda

Distribuição automática de energia entre os veículos, evitando sobrecarga e garantindo eficiência.

### Sistema de Tarifação

Cálculo automático do custo de recarga com base na energia consumida.

### Simulação de Ambiente Comercial

Múltiplos veículos sendo atendidos simultaneamente.

### Visualização de Dados

Geração de gráficos para análise da distribuição de energia.

---

## Exemplo de Execução

O sistema apresenta:

* Energia solicitada por cada veículo
* Energia efetivamente distribuída
* Custo da recarga
* Energia restante no sistema

---

## Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone <link-do-repositorio>
```

---

### 2. Acesse a pasta

```bash
cd chargegrid-intelligence
```

---

### 3. Execute o código

```bash
python main.py
```

---

## Estrutura do Projeto

```
chargegrid-intelligence
 ├── main.py
 ├── README.md
 └── /assets (opcional - imagens e gráficos)
```

---

## Evolução em Relação à Sprint 1

Na Sprint 1, foram analisados os principais desafios do ChargeGrid, incluindo:

* Sobrecarga de energia
* Ineficiência na distribuição
* Problemas de tarifação
* Falta de otimização inteligente

Na Sprint 2, esses conceitos foram aplicados na prática através de uma simulação funcional, demonstrando:

* Distribuição inteligente de energia
* Controle de demanda em tempo real
* Cálculo automatizado de custos

---

## Metodologia de Projeto

O desenvolvimento foi organizado utilizando a metodologia **Kanban**, permitindo:

* Melhor divisão de tarefas
* Acompanhamento da evolução do projeto
* Organização das etapas de desenvolvimento

---

## Integrantes

* Guilherme Miranda - 573107
* Rafael Gandolfi - 569036
* Rafael Lins - 570588
* Carlos Eduardo - 572949
* Cauã Paes - 569906
* João Pedro - 569725

---

## Conclusão

A prova de conceito desenvolvida demonstra que é possível aplicar técnicas de controle inteligente para otimizar a distribuição de energia em ambientes comerciais.

O sistema contribui para:

* Redução de sobrecarga
* Melhor aproveitamento energético
* Automação da cobrança
* Maior eficiência operacional

---

## Futuras Melhorias

* Implementação de Inteligência Artificial mais avançada
* Integração com sistemas reais de recarga
* Interface gráfica interativa
* Monitoramento em tempo real

---
