# Drivers da Satisfação de Passageiros Aéreos

Análise exploratória de dados para identificar os principais fatores que influenciam a satisfação de passageiros de uma companhia aérea, utilizando um dataset público do Kaggle com mais de 100.000 avaliações.

---

### ➡️ [Veja a Análise Interativa e Completa no Kaggle](https://www.kaggle.com/code/dafnemoraes/drivers-da-satisfa-o-de-passageiros)
---

## Contexto e Objetivo do Projeto

A satisfação do cliente é uma métrica crucial para o sucesso de qualquer companhia aérea, impactando diretamente a fidelidade e a receita. Este projeto vai além das métricas superficiais para descobrir as causas-raiz da satisfação e insatisfação, focando em como o propósito da viagem e a percepção de valor do cliente influenciam sua avaliação.

## Principais Descobertas

A análise revelou que o driver mais poderoso da satisfação é o **alinhamento entre a expectativa do cliente e o valor percebido**, muitas vezes superando a qualidade isolada dos serviços.

* **O Paradoxo da Classe Executiva:** Passageiros em viagem pessoal, mesmo na classe premium, são mais críticos e insatisfeitos do que os passageiros a negócio. A hipótese é que o alto custo pessoal da passagem eleva as expectativas a um nível de perfeição, tornando-os mais sensíveis a qualquer falha.
* **A Inversão na Classe Econômica:** Neste segmento, passageiros em viagem pessoal são ligeiramente *mais satisfeitos* que os de negócio. O baixo custo parece alinhar as expectativas a um serviço funcional, enquanto as necessidades de trabalho do viajante de negócios podem ser frustradas no ambiente econômico.
* **A Importância da Primeira Experiência:** Clientes não fidelizados apresentam um nível de insatisfação drasticamente maior, destacando a jornada do primeiro voo como um momento crítico para a retenção.

## Recomendações Estratégicas

Com base nos insights, as seguintes ações poderiam ser exploradas:

1.  **Para o Segmento "Lazer Premium":** Focar em criar "momentos de encanto" e um serviço mais personalizado para justificar o alto investimento emocional e financeiro do cliente.
2.  **Para o Segmento "Negócios Econômico":** Oferecer produtos e serviços focados em produtividade, como pacotes de Wi-Fi e assentos com mais espaço para trabalho.
3.  **Para Novos Clientes:** Mapear e otimizar a jornada do primeiro voo, simplificando processos e melhorando a comunicação proativa para construir um "histórico de confiança".

## Como Executar a Análise

O projeto foi desenvolvido em Python 3. As principais bibliotecas utilizadas são:
* Pandas
* Matplotlib
* Seaborn

O notebook `drivers-da-satisfa-o-de-passageiros.ipynb` contém toda a análise, e o dataset utilizado é o `train.csv`.
