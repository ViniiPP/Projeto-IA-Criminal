# Projeto-IA-Criminal
Projeto de predição de crimes com base em fatores metereológicos.

## Apenas explicações

### etapa 2
- 3.218.268 linhas (estado inteiro)
- Depois do filtro: 67.274 linhas (Passo Fundo)
- detecção de colunas com nulos


### etapa 3
- nulos corrigidos, foi colocado uma palavra no local vazio condizente com a situação de cada coluna

### etapa 4
- merge dos dados, e 618 dias com dados combinados

### etapa 5
- leitura dos dados:
    - qtd_Crimes: 42.453809 == 42 crimes por dia
    - min de 19.000000 == 19 crimes por dia
    - max de 66.000000 == 66 crimes por dia

    --
    - preciptacao: 5.8... == 5.8mm
    - max 155... == 155mm chuva forte

    --
    - temperatura: 18... == 18C
    - max 27.5... == 27.5C


### Resultado
- As correlações encontradas são fracas, 
indicando que o clima não possui forte influência 
direta sobre a criminalidade nos dados analisados.