# Rock in Rio Ticket System

Este repositório contém o design e a arquitetura de um sistema de login e vendas de ingressos para um show extremamente concorrido, como o Rock in Rio. O sistema é projetado para lidar com uma alta demanda de usuários, garantindo que apenas os clientes que realmente consigam finalizar a compra recebam os ingressos, evitando problemas de overbooking e preferências de conexões mais rápidas.

## Visão Geral

O diagrama abaixo descreve a arquitetura completa do sistema, incluindo:

- Autenticação de usuários
- Sistema de fila virtual para garantir a ordem justa de acesso
- Verificação de disponibilidade de ingressos
- Reserva temporária de ingressos
- Processamento de pagamento e confirmação de compra
- Infraestrutura de escalabilidade com balanceamento de carga

![Diagrama de Arquitetura](https://raw.githubusercontent.com/shenriquess/rock-in-rio-ticket-system/main/Diagrama%20Venda%20de%20Ingressos.png)

## Tecnologias Envolvidas

- **Frontend**: Interface web para interação com o cliente
- **Backend**: Servidores de login, fila e vendas
- **Banco de Dados**: Para usuários, ingressos e transações
- **Sistema de Filas**: Para gerenciar o tráfego intenso de usuários
- **Gateway de Pagamento**: Integração para processar pagamentos
- **Escalabilidade**: Load balancing e servidores redundantes


