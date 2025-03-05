# Sistema de Controle de Ordens de Serviço - Oficina Mecânica

Este projeto implementa um sistema para gerenciar ordens de serviço em uma oficina mecânica. O sistema organiza as informações de clientes, veículos, ordens de serviço, mecânicos, serviços (mão de obra e peças), e o cálculo de valores baseado em uma tabela de referência de mão de obra.

## Entidades Principais

- **Cliente:** Representa o cliente da oficina.
- **Veículo:** Representa os veículos dos clientes que são levados para manutenção ou revisão.
- **Ordem de Serviço (OS):** Cada OS contém os serviços a serem realizados e é vinculada a um veículo e a uma equipe de mecânicos.
- **Mecânico:** Profissionais responsáveis pela execução dos serviços.
- **Serviço:** Define os serviços executados, que podem ser mão de obra ou peças.
- **Peça:** Refere-se a peças que são instaladas nos veículos durante a execução de serviços.
- **Tabela de Mão de Obra:** Contém valores e tempos estimados para os serviços de mão de obra.

## Funcionalidades

- Gerenciamento de clientes e veículos.
- Emissão de ordens de serviço com cálculo automático de valores.
- Atribuição de serviços (mão de obra e peças) às OS.
- Acompanhamento do status e conclusão das ordens de serviço.

## Objetivo

Este sistema visa otimizar a execução e o controle das ordens de serviço em uma oficina mecânica, melhorando a eficiência e organização do processo.
