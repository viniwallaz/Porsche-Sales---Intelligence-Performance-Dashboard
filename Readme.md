# Porsche Sales Intelligence & Performance Dashboard
Link:https://viniwallaz.github.io/Porsche-Sales---Intelligence-Performance-Dashboard/

Dashboard de análise de vendas do setor automotivo de luxo, construído com **HTML, CSS, Excel e CursorAI**, com filtros interativos, geração automatizada de insights e tratamento de qualidade dos dados.

## Visão Geral

Este projeto simula uma plataforma de inteligência de vendas premium, voltada para concessionárias Porsche e gestores regionais de vendas.

O dashboard transforma registros de transações brutas em insights de negócios acionáveis, permitindo o acompanhamento do desempenho de vendas, comportamento do cliente e operações de entrega.

A interface foi inspirada na identidade visual da Porsche, combinando um tema minimalista em preto com detalhes em dourado.

## Funcionalidades

### KPIs Executivos

- Receita Total
- Ticket Médio
- Modelos Únicos Vendidos
- Taxa de Entrega

### Filtros Interativos

O usuário pode filtrar dinamicamente o dashboard por:

- Ano do Modelo
- Cidade
- Método de Pagamento

### Análises de Vendas

#### Top Modelos por Receita
Mostra os modelos de Porsche que mais geram receita.

#### Distribuição por Método de Pagamento
Gráfico do tipo rosquinha mostrando a preferência de pagamento dos clientes.

#### Distribuição por Ano do Modelo
Análise de veículos vendidos por ano.

#### Monitoramento do Status de Entrega
Acompanha as etapas de fulfillment, como:

- Entregue
- Pendente
- Em Trânsito
- Aguardando Entrega
- Cancelado
- Enviado

### Análise Geográfica

Comparação de desempenho por cidade, incluindo:

- Modelo mais vendido
- Unidades vendidas
- Receita total
- Ticket médio

### Insights Automatizados

O dashboard gera automaticamente insights como:

> "911 Turbo S lidera as vendas em Seattle com ticket médio de $242 mil. O método de pagamento preferido é Wire Transfer."

## Conjunto de Dados

O projeto utiliza um conjunto de dados sintético com **100 transações de vendas da Porsche nos EUA**.

Exemplos de atributos:

| Coluna                    | Descrição                          |
|----------------------------|------------------------------------|
| SaleDateSanitized           | Data da venda sanitizada         |
| PorscheModelSanitized     | Modelo do veículo                 |
| ModelYearSanitized           | Ano do modelo                       |
| SalesPriceSanitized          | Preço do veículo                  |
| PayMethodSanitized         | Método de pagamento               |
| CitySanitized              | Cidade do cliente                    |
| StateSanitized             | Estado do cliente                    |
| DeliveryStatusSanitized         | Status da entrega                     |

