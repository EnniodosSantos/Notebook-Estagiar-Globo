# Análise de Dados de Marca, Saúde e Reputação
Objetivo da Análise

Este estudo busca compreender a reputação e saúde de marca com base em critérios de percepção do consumidor — como sabor, preço, popularidade, disponibilidade no mercado e variedade de sabores. O objetivo é identificar fatores determinantes da popularidade, semelhanças entre marcas e o equilíbrio interno de atributos que sustentam a força competitiva de cada marca no mercado de bebidas.

## Radar Chart — Comparação Multidimensional de Desempenho

O gráfico radar apresenta uma visão multivariada do desempenho de cada marca em relação aos critérios avaliados.

No contexto de reputação, cada critério pode representar um indicador de saúde:

**Sabor** -> Qualidade do produto percebida.

**Preço** -> Acessibilidade e percepção de custo-benefício.

**Popularidade** -> Força da marca e identificação emocional.

**Disponibilidade** -> Alcance de distribuição e presença no mercado.

**Variedade de sabores** -> Inovação e diversificação de portfólio.


Esses indicadores ajudam a responder perguntas como:

- “Onde a marca está se desconectando do público?”

- “O que o consumidor valoriza mais?”

- “Qual marca está mais vulnerável ou mais sólida?”

### Interpretação:

Coca-Cola mantém alta performance em praticamente todos os critérios, destacando-se em Popularidade e Disponibilidade.

Pepsi exibe perfil equilibrado, com boa pontuação em Preço e Popularidade.

Guaraná Antarctica mostra força em Disponibilidade e Sabor.

Dolly e Sukita destacam-se apenas em Preço, refletindo uma estratégia de valor acessível.

<img width="877" height="722" alt="image" src="https://github.com/user-attachments/assets/8ddf287f-2cac-474c-bcba-1317e34de303" />

## Reputação Geral — Média de Desempenho por Marca

A pontuação média sintetiza o desempenho global de cada marca.

Ranking de reputação:

Coca-Cola — 8.4

Pepsi — 7.8

Guaraná Antarctica — 7.6

Dolly — 6.6

Sukita — 6.4

Insight: Coca-Cola lidera com ampla vantagem, consolidando-se como referência de qualidade e lembrança

<img width="693" height="384" alt="image" src="https://github.com/user-attachments/assets/900e6918-b21b-4bab-9aa8-c26d2f2bef36" />

## Correlação entre Critérios e Popularidade

Foram calculadas as correlações de Pearson entre Popularidade e os demais critérios.
O objetivo é entender quais atributos mais impactam a popularidade de cada marca.

| Critério                 | Correlação (r) com Popularidade | Interpretação                                                                                |
| ------------------------ | ------------------------------- | -------------------------------------------------------------------------------------------- |
| **Sabor**                | +0.87                           | Forte correlação positiva — sabor é altamente determinante.                                  |
| **Preço**                | +0.91                           | Forte correlação positiva — percepção de valor e preço equilibrado impulsionam popularidade. |
| **Disponibilidade**      | +0.38                           | Correlação muito forte — marcas amplamente disponíveis são também as mais populares.|
| **Variedade de sabores** | +0.72                           | Correlação moderada — diversificação contribui para maior apelo de marca.                    |


Síntese: o público associa popularidade a sabor e valor percebido (preço) — dois pilares-chave da decisão de compra.

<img width="1583" height="452" alt="image" src="https://github.com/user-attachments/assets/5da8afff-c3dd-4600-a903-3e22a3c7eabf" />

Dendrograma
O dendrograma mostra o grau de semelhança entre as marcas, agrupando aquelas que têm características mais próximas.

Interpretação
Coca-Cola e Pepsi formam o primeiro grupo (menor distância): → Marcas líderes, com perfis muito parecidos em popularidade e distribuição, sendo percebidas como premium.

Guaraná Antarctica se une a esse grupo em seguida: → Mantém proximidade com as líderes, mas tem perfil levemente diferenciado (sabor e identidade nacional).

Dolly e Sukita formam outro grupo mais distante: → Ambas têm preço mais baixo e menor popularidade, voltadas para um público mais sensível a preço.

O mercado se divide claramente em dois blocos: (1) Marcas de alto prestígio e reconhecimento (Coca-Cola, Pepsi, Guaraná Antarctica) (2) Marcas econômicas (Dolly, Sukita).

<img width="1176" height="726" alt="image" src="https://github.com/user-attachments/assets/b944dc02-9afc-458c-9dbf-1cd35895b365" />

## Índice Composto de Saúde de Marca (Brand Health Score)

O índice foi calculado a partir da média normalizada dos critérios:
**Sabor**, **Preço**, **Popularidade**, **Disponibilidade no mercado** e **Variedade de sabores**.

- **Coca-Cola** lidera amplamente, refletindo força global e consistência de marca.
- **Pepsi** e **Guaraná Antarctica** apresentam boa saúde, com equilíbrio entre percepção e presença de mercado.
- **Dolly** e **Sukita** mostram baixo desempenho relativo, concentrando força apenas em preço.

Esse índice resume a *saúde geral da marca*, permitindo comparar estratégias competitivas.

<img width="1176" height="651" alt="image" src="https://github.com/user-attachments/assets/b6b4701a-9521-466e-bd4d-c683d5cc318d" />

## Conclusão 

A análise evidencia que a saúde de marca está diretamente ligada ao equilíbrio entre qualidade percebida e distribuição.
Marcas líderes, como Coca-Cola e Guaraná Antarctica, mantêm vantagem competitiva por conseguir combinar consistência de produto, presença de mercado e vínculo afetivo com o consumidor.

Já Pepsi ocupa um espaço intermediário, competitiva, porém menos dominante no imaginário coletivo.
Dolly e Sukita, embora relevantes em preço, enfrentam desafios de percepção e diferenciação, necessitando estratégias de reposicionamento para elevar o valor simbólico de suas marcas.

Em síntese, a força de uma marca não depende apenas de preço ou sabor, mas do conjunto equilibrado de atributos que sustentam relevância, confiança e desejo no consumidor.

## Resumo — Saúde e Reputação de Marca
🔹 1. Liderança Sustentada

A Coca-Cola mantém liderança absoluta em todos os critérios, demonstrando alta coerência de marca e força emocional consolidada.

Estratégia: manter inovação contínua e reforço de branding global.

🔹 2. Espaço de Diferenciação

Guaraná Antarctica e Pepsi ocupam posições intermediárias com potencial de expansão.

Estratégia: investir em identidade local (Guaraná) e comunicação experiencial (Pepsi) para fortalecer diferenciação frente à líder.

🔹 3. Nicho de Valor Acessível

Dolly e Sukita competem em um segmento sensível a preço, mas com baixa percepção de valor simbólico.

Estratégia: reposicionar imagem, reforçar autenticidade e buscar melhor distribuição e portfólio.

🔹 4. Correlação de Fatores

A popularidade correlaciona-se fortemente com sabor e disponibilidade, sugerindo que melhorias nesses atributos têm impacto direto na força de marca.

🔹 5. Oportunidade Estratégica

O mercado mostra polarização entre marcas premium e econômicas, abrindo espaço para novos posicionamentos intermediários, que combinem valor acessível e identidade de marca forte.




