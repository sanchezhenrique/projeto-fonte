# Fonte de Tensão Ajustável — 3V a 12V / 100mA

Projeto desenvolvido na disciplina de Eletrônica para Computação (SSC0180) do ICMC-USP.

O circuito implementa uma fonte de tensão DC ajustável utilizando o regulador linear LM317T, capaz de fornecer tensões entre 3V e 12V com corrente máxima de 100mA.

---

## Simulação no Falstad

Acesse a simulação completa do circuito:  
🔗 [Abrir no Falstad Circuit Simulator](https://www.falstad.com/circuit/circuitjs.html?ctz=DwYwlgTgBAZgvAIgAwKgFwM6KQOif-AVlTBEQGYAOAJhwHYA2awmgRgBZyBOLpB91CABGiaq1QAHEQk6oAbhETEoAW0xKApgFpW4gHwAoKFGAAVKAA9EW8uQZRySdlC3V2SKOy4NU8ZCQA7RAEoCABDbBwOakpCOmjY+PYY5RAAe0ieLlQAdzBEVi5qQSRrXDpCfjo6bh5HfAZyQVZIx2o6amonGl5CJzsEAHpDY2Acy2tOak9vF1t7Lx9YbCGRkwwJhC13D0dnGwZKBydfFeGjE3GrLZ3j-am70-9z0avrOyO9ubtH5ee10CbViMByHKDAhbkYp-FBQMjIPANOhZFGongkOSRfDiKAYRQInFyAAmBQYOAYDEIvCSfX4HCaL0uQJBH3BLK6TxQjLGzPsUI8uw5MNWFx51whUDi9n4ksYnJFr15Di6d2VsL8XIBbwQEqloKOUvl3O17FYfJVt35Rq1my+-M8+DV1tFck22yhqvd00WTzNuT8OJg+IYsJUYQsmJ17QVJiJbolVH2rBiDgGwtUGR1ADkdgJuXHrlpKLtKEmU-N5RmCjn8HmAQXrMmjg8dCzS5WVJnWDWTvn4ymW8WHO3053q7mY8AAOZuroGkGuJBHfjqs42wtuXZOFyb4chDWT7Wudx7lwJkcH42zk+LFwyn3Cq+F++zLQyxPOxXP5yJlxDj+Puujblj8OjlkKl5AVsTZqlAgqrv8opHjBLYwYagFIUq7BDrqMSfky4ogoQKa6nKGGjCAICbKa5oeMRnyHL6qBjggAB+AAyACy5DAlocjFGsFFQMSZT0NhS5IFwyLuMmlJ0CQ1zFIyQkiQiBCsJQhS6NUXB2EwwLRlAYDXAygkmGgwlCBoWLYppXDacieliB08mWfCWjlOJxZSVwMnUHJCnBDGKkkgiNTkHQ7CMEwnC6e0yjGYgPjKSYVGqToUT2fglCJlQjQ0E0RnXPJKXABZchWY2mWsNluWUPl1CFRV8LlLYkXRW43BQhUgUIJQwWpcJoUeWJdCUFJ5CEBwfDAoQhWJTqmoXCFBSZZJ7TxHwNRmqwCXiuIpXlZVOprUU1Q1Qw20MLt8hCO5nljRNU3uNdFTzeKSlmYCqmeawdjxPEVBIOQnA4gtHADd9oW4EijAcM9VI0Ic0Lg8Qh2WdZalbXD7AI1wSM0LdLViX9l3An9xYgzxvV+qVaXDb9hyEOwySLDwZHg-1dNDZENRRbYS50EgxFzddNPZOjFWY61-OOJQQsi3YhJ3aJkVmrELNuN47NLAtHLcz95JcFN3i7YQxGbn9vWdJD9OiTFEX1V02E1YUuuKaZy3mRj9udWNTDdK73hE5EDDG27ZsWzJ72iHWXtQ6r7CNMLZrm10fTjdbyVfXbCK4-pjQ6TxUUc4pJVfUd0s4PnYiF45HDVEszWJ8nU2UsRwtLtkRWiFzOc81suDaX01TJMWW2NTHCCOLbA+sDgk3jTVjBIJFnRiL11OS8d8+L1lK9r50yv3VEs2r2v4+XZPm+ffHucjRUjVTbYGcsHNU8g7Phs8ZJIZIMw9UQzjRCAtSakNK6tBqt4fAACKRdxCM3Qe9BiKTT+pNJcb9bCb2znfAetBLrA0amHZmUk3DM20P1Hu08+64PSvPfS8RjbFjGu-eqm8JYVx9tBckzlCgsFXrEWwbC3KiHJELKEdhjZeA6LjdgFDeruC-gzeglB6rA2NkfdWwMFG32MCtBEOUeK7UaFJQxasFGez0d7KWkRDG6EqNwMabVTQhyQWNNR3BLoFXqkUBRccrEJzChSDRMR5bMELgonBAT77z0ko4IoAif4sCwVQqK4CuEZTietRJNVklNRVkE4hnRVEdAca5Ba2ElH23xiDKafA4jMJcVQvoVSES2CfoUVeLMWCN16lNdJNi2kSJNl03G8syKIJGmHHKuMLoNK6WDa4xFWlTKKKaQhEUigaSnszVpuBqQdF8u0SOac+lo04YM-Z59qBHPiObe50JJm4DDm4GqEjkRiByn0qJejAkPw0jEYE1QppjScIspQNDokDxGrWdoTgXLnT4CDbuC0qQDOOjCpwcKoobU2o0Lwrj-k0E0vXG5PA0lUJDHs+gAKaDm0uo-RgKLrhMBWVclhhRVE7XlhDSlljfkQKQdSWInLNLXR5Qggp5RaXMEqMC9oYder8DZTS4lQLH5JzTAtCk1KCDC3aqopgjRHAVDGkq8u8dBUwwIHEKKhr-IC1NZQp5qrAX1w+G4Sh2rIW-Nzs8qkFQoo8DpMwYWvUhYqt4LYDRhrVHmw6OGg6FyMVXOjfReqca4iPKleSANzNkTeFNKGvaiAE0G2UcmLZ9UHFiqXLjcN-jfVz2rkUPocTKh-RZu7Ut5zLVcPnl4UN7brogyToSoeNzPlkzqMicK4afn6OlZNResR8Z9GLuGn1+iH6PUpE4KSY0YhNIWsidFmMd3jT3dIw9pZj68z+nNFgq7YjA15QtYsKqajeXxhpfokkKXvt0U2w26kiGAzNFMf93a+r8tGFaxESBkz-T+hB-kvkm4FIfkDHgmliycH-eU647Zy2q2wz+lyRQj69TYSRoZbgw58DDhwCkEVqMWoCfB9pSdeDBOYxEkRbiyMkvaJRjeVDVHUpqGdKkLNV74s-lQ3gKr2kUkvcDQNnzer2TPaJFThxoERWZppgTrVpO+XcIwKmIDri+No+UY5nasU3KTv0xTjbF14BiPwLoJqhZCyiqvLTvaONcJhl55IwNz6r3hYFkz9AHMgyc+h1zC1g52foBIrpTBJH-zmlprdg0QMpCkoxzgHaqBfMUxwvtlzPOrqFhSMrI7VH5OJjURqWWiG8GYFPGqS0oWG2qC18aY1woFRRuKf+KzYnBuNtwElcn8Y020dvc9M3tZzXI4t51Oahs5RG-LIRjUJsFF7P3QbpjV5Ug4DyyKJbFoLsK8NeeXL+Cg3NvLN70Hl46e4a9lmPEPuMC7a48ol2Kj2WwgDetVCaoFcCeyoWxLSllYJbDqgrTaBdGTKPHrcKbmEYKNwST7jZERaKCDQoNNFG0fnnFFz9TkjREJzqFxtOcBSPqTAlmZp-7WYKMkalUagYvxDEN3ZsPZDckGJRKCt49TiVlEsSCooJAWWuIrlmzYhzoQDMxCICA22wgkJmfZxs9UW-UqgDAAAbRAAAlDQGAwAYDQGEAIIANCHk2PRSUyZJQpnovhMUShA9h-nMrtcmElmB5BPLsiKuvxJWcHqMCEfg-IVj-YRc6fyImGgEs-39oprTAAgeUIsd+sESUEXlUeorR5+AOxAAogAEU2DUPkpYoCd5mJH-wVYEBEg0DAMIABXG3aAtA240ESQQ+IcQgCnCsOE0hQw5sQ5OAvpafj2l72XlfC+CDe+Kj8W8vfddR6TwgffKocql4glf6vN+fh6nv0r4P2+YOl5+O-h85eF99YAQABBFQFQDQNADQL-IBJXAPXPPwQqcAlfDAFqE-HfewPUQ4eAp-EPb-WA9-EvDPTYAg-3P-YORvbUd-eYKAKgx-RCa-evFULAp0CgzYZgvfXfOgqvXA5gzApcD-VgwiSEaYCUcST-aiD0GiTwD0ZmfcQ-YIHYNAmQGQlmaQ6YS-eg5-B4BXHXBPHAk0GQlkMEDQ7gk0WYEvOAv3aERPZ-Cw38CwxQwQmvb0R0TXfAIgjXf8bvNwhCUw6iIcW4TXP0JwmQAIs0NQzwYImw3AoIhYAIypRvNIKADQIIBAbuDACQZPJ4CwQqTI-wL6CQYSZA+EGnAooo6ea3YmIDYAQYNIAEJIlI0ta3PI5VP4HIyQAoBAMoyMWEFA4IKvUYQoyMQqPo6eHAao2o+o5I1I9IlouQhAdoqAPIgSeOIY4o-oyGNYio3EKoycSY0UBo1I5MZorIto3IigLo1Y8o3okogYkwLYkY3Y6XOog46YigShDI04vwRYvIgQbo9YhAIAq44YyoyICYl4mo8ACAQwIAA)

---

## Componentes

| REF.     | Componente             | Especificação                     | Qtd.  |
| -------- | ---------------------- | --------------------------------- | ----- |
| BR1      | Ponte Retificadora     | 4x 1N4001                         | 1     |
| C1       | Capacitor Eletrolítico | 680µF / 25V                       | 1     |
| U1       | Regulador Ajustável    | LM317T                            | 1     |
| R1       | Resistor               | 240Ω / 1%                         | 1     |
| P1       | Potenciômetro          | 5kΩ Linear                        | 1     |
| R2a, R2b | Resistores em série    | 2x 2,2kΩ (em paralelo com P1)     | 2     |
| R3       | Resistor               | 1kΩ                               | 1     |
| LED1     | LED                    | Vermelho 5mm                      | 1     |
| —        | Protoboard             | T2PB89 830P (2 barras dist. 100P) | 1     |
| —        | Cabos Jumper           | Macho-Macho 20cm                  | 1 kit |

---

## Custo do Projeto

| Categoria               | Valor        |
| ----------------------- | ------------ |
| Componentes eletrônicos | R$ 47,10     |
| Protoboard + jumpers    | R$ 45,00     |
| **Total**               | **R$ 92,10** |

---

## Cálculos

### Etapa de retificação e filtragem

A tensão de pico após a ponte retificadora (queda de ~1,4V nas duas junções):

$$V_{pico} = V_{RMS} \cdot \sqrt{2} = 15 \cdot 1{,}414 = 21{,}21 \text{ V}$$

$$V_{2pico} = 21{,}21 - 1{,}4 = 19{,}81 \text{ V}$$

Com ripple de 10%:

$$V_{ond} = V_{2pico} \cdot ripple = 19{,}81 \cdot 0{,}10 = 1{,}98 \text{ V}$$

$$V_{2médio} \approx V_{2pico} \cdot (1 - ripple/2) = 19{,}81 \cdot 0{,}95 = 18{,}82 \text{ V}$$

$$V_{2mínimo} = V_{2pico} - V_{ond} = 19{,}81 - 1{,}98 = \mathbf{17{,}83 \text{ V}}$$

### Capacitor de filtragem

Corrente total de carga:

$$I_{total} = I_{carga} + I_{R1} = 0{,}100 + \frac{1{,}25}{240} \approx 0{,}105 \text{ A}$$

Capacitância mínima necessária (onda completa, $f = 120$ Hz):

$$C = \frac{I_{total}}{f \cdot V_{ond}} = \frac{0{,}105}{120 \cdot 1{,}98} \approx 442 \text{ µF} \implies \text{usa-se } \mathbf{680 \text{ µF}}$$

### Regulador LM317T

A tensão de saída é definida por:

$$V_{out} = 1{,}25 \cdot \left(1 + \frac{R2}{R1}\right)$$

com $R1 = 240\Omega$ fixo e $R2$ variável (potenciômetro + resistores em paralelo).

### Ajuste do potenciômetro

O potenciômetro disponível era de 5kΩ. Para adequar a faixa de variação ao intervalo desejado (3V–12V), foram colocados dois resistores de 2,2kΩ em série entre si, e esse conjunto em paralelo com o potenciômetro:

$$R_{série} = 2{,}2 + 2{,}2 = 4{,}4 \text{ k}\Omega$$

$$R_{eq}(máx) = \frac{5000 \cdot 4400}{5000 + 4400} \approx 2{,}34 \text{ k}\Omega$$

Tensão máxima de saída (potenciômetro no máximo):

$$V_{out}(máx) = 1{,}25 \cdot \left(1 + \frac{2340}{240}\right) \approx \mathbf{13{,}4 \text{ V}}$$

Tensão mínima de saída (potenciômetro em 0Ω):

$$V_{out}(mín) = 1{,}25 \cdot \left(1 + \frac{0}{240}\right) = \mathbf{1{,}25 \text{ V}}$$

A faixa operacional prática, considerando as limitações do circuito, ficou entre **~3V e ~12V**.

### Dissipação do LM317 (pior caso)

$$P = (V_{in} - V_{out}) \cdot I = (17{,}83 - 3) \cdot 0{,}1 = \mathbf{1{,}48 \text{ W}}$$

> ⚠️ Recomenda-se o uso de um pequeno dissipador de calor no LM317T.

---

## PCB

O layout da placa foi desenvolvido no EasyEDA.
![PCB](Imagens/pcb.png)

---

## Integrantes

- Henrique Alcici Sanchez - 17895852
- João Matheus Frota Girão - 17899582
- João Pedro Cremasco Luiz — 17899853
- Thomas Riki Hashima — 15580336
