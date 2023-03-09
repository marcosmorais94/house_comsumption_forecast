![1024-lampadina](https://user-images.githubusercontent.com/91103250/223886504-c1508d64-0960-4dbe-a9ec-b3cdbdc50212.jpg)

# Análise Preditiva com Séries Temporais - Consumo de Energia Elétrica
Este repositório tem objetivo o uso de algoritmo com séries temporais para prever os próximos 365 dias de consumo de energia elétrica em uma residência na França. Os dados foram coletados entre Dez/2006 e Nov/2010 (total de 47 meses) de uma casa localizada em Sceaux, França.

Fonte dos dados: https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption

### Dicionário de Dados

| Atributo  | Descrição | Métrica |
| ------------- | ------------- | ------------- |
| date | Data que foi coletada a amostra  | dd/mm/yyyy |
| time |  Hora que foi coletada a amostra | hh:mm:ss |
| global_active_power |  potência ativa média global por minuto | Quilowatt |
| global_reactive_power | potência reativa média global por minuto  | Quilowatt |
| voltage | tensão média por minuto  | Volt |
| global_intensity | intensidade atual média global por minuto  | Ampere |
| sub_metering_1 |  Corresponde à cozinha, contendo principalmente uma máquina de lavar louça, um forno e um micro-ondas (as placas eléctricas não são eléctricas, mas sim a gás). | Quilowatt-hora |
| sub_metering_2 | Corresponde à lavanderia, contendo máquina de lavar, secadora, geladeira e luminária. | Quilowatt-hora |
| sub_metering_3 |  Corresponde a um aquecedor eléctrico e um ar-condicionado. | Quilowatt-hora |

| | |
| ------------- | ------------- |
| Total de Registros | 2.075.259  |
| Total de Atributos | 9  |
