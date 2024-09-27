# Cálculo de Horário de Saída - API em Java com Spring Boot

Esta API foi construída com Spring Boot para calcular o horário de saída com base no horário de entrada, almoço, retorno e minutos adicionais (como de reuniões). Além disso, converte os minutos adicionais para o formato decimal de horas.

## Funcionalidades

- Recebe um JSON com horário de entrada, almoço, retorno e minutos adicionais.
- Calcula o horário de saída baseado nesses valores.
- Converte os minutos extras para o formato decimal de horas.

## Exemplo de Requisição

### Endpoint


### Corpo da Requisição (JSON)

```json
{
  "entrada": "08:00",
  "almoco": "12:00",
  "retorno": "13:00",
  "minutosExtra": 50
}

{
  "horarioSaida": "17:50",
  "minutosConvertidos": 0.83
}
