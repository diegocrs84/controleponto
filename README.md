# ⏰ Controle de Ponto

Aplicação web simples para controle de ponto de trabalho, desenvolvida em HTML, CSS e JavaScript puro (sem dependências).

## Funcionalidades

- Registro de horário de entrada
- Registro de início do almoço
- Cálculo automático do fim do almoço (+1h15min)
- Cálculo automático da saída prevista (+8h45min de jornada)
- Registro de saída real
- Cálculo de tempo excedente
- Resumo do dia com:
  - Tempo trabalhado
  - Jornada prevista (8h45min)
  - Diferença (positiva ou negativa)

## Como usar

1. Abra o arquivo `index.html` em qualquer navegador moderno
2. Preencha os campos na seguinte ordem:
   - **1 - Hora de Entrada**: Horário que chegou ao trabalho
   - **2 - Início do Almoço**: Horário que saiu para almoço
   - **3 - Fim do Almoço**: Calculado automaticamente (+1h15min após o início)
   - **4 - Saída Prevista**: Calculada automaticamente (+8h45min após entrada)
   - **5 - Saída Real**: Horário que saiu do trabalho
   - **6 - Total Excedido**: Calculado automaticamente
3. O resumo na parte inferior mostra o balanço do dia

## Regras de Negócio

- Duração do almoço: **1h15min** (75 minutos)
- Jornada diária: **8h45min** (525 minutos)
- O cálculo considera o desconto do horário de almoço

## Tecnologias

- HTML5
- CSS3 (com gradientes e sombras modernas)
- JavaScript Vanilla (sem frameworks ou bibliotecas)

## Compatibilidade

Funciona em qualquer navegador moderno que suporte:
- Input type `time`
- CSS Grid/Flexbox
- ES6 JavaScript

## Licença

MIT
