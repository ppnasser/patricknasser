---
title: 'Como ler um número?'
subtitle: 'Uma reflexão sobre os números que você vê na TV ao tomar café.'
summary: Uma reflexão sobre os números que você vê na TV ao tomar café.
authors:
- admin
tags:
- Opinião
categories:
- Estatística

date: "2020-04-04T00:00:00Z"
lastmod: "2020-04-04T00:00:00Z"
featured: false
draft: false
---

Em 1998, a cidade do Vaticano registrou um taxa de homicídio de 256 mortes por 100.000 habitantes.

Para se ter um comparativo, no mesmo ano no Brasil, um país violento, esta taxa foi de aproximadamente 26 por 100.000.

Quem não percebeu o detalhe pode estar se perguntando nesse momento que tragédia ou atentado ocorreu na pequena Cidade-Estado para registar essa mortalidade de guerra. Na verdade, ocorreu apenas um evento: [um guarda local cometeu um crime passional, matando duas pessoas](https://www.irishtimes.com/news/vatican-closes-swiss-guard-case-1.150637).

A assustadora taxa de 256 por 100.000 foi alcançada  porque o Vaticano possuía somente 782 moradores na época: 2/782 $\approx$ 256/100.000.

### Números que nos confundem

[to do: adicionar referências dos números + gráfico]

O Vaticano é um excelente exemplo para mostrarmos como é preciso ter cuidado com a interpretação de indicadores.

De fato, enquanto a maioria dos países não possuí nenhum Papa, o Vaticano sozinho possuí a impressionante taxa de 2 Papas por quilômetro quadrado! Seu território, é claro, é de menos de 1 quilômetro, mas se você for um político querendo criticar o Vaticano por ter Papas demais poderia utilizar esse dado ao seu favor sem estar mentindo em sentindo estrito, mas, ao mesmo tempo, estaria promovendo uma interpretação equivocada ou desinformada da realidade.

[imagem vaticano?]

O uso político dos números já é antigo. Interpretações incorretas ou desinformavas sobre os números do cotidiano são espalhadas a todo o momento, seja por ingenuidade, desconhecimento ou desonestidade. 

Há uma infinidade de exemplos que descrevem o uso e a construção de narrativas políticas com o números por distopias autoritárias. Na literatura talvez a aparição mais emblemática se dê pela "propaganda do progresso" criada pelos porcos para enaltecer a fazenda em [A Revolução dos Bichos](https://en.wikipedia.org/wiki/Animal_Farm) de George Orwell. No mundo real o mesmo tipo de propaganda pode ser muito bem ilustrado pela extensiva e protocolar divulgação dos aumentos salariais de mais de 500% entre 1928 e 1940 pela comunicação soviética, acompanhada, é claro, da omissão das estatísticas de aumento nos custos de vida [Bergson, A. (1953)](https://www.tandfonline.com/doi/abs/10.1080/00031305.1953.10481990?journalCode=utas20). 

Apesar de diferenciados pela maior transparência, essas mesmas narrativas sustentadas por números estão presentes em praticamente todos os discursos do debate democrático, e são consideradas uma forma convincente de argumentação, pois números tem o peso de fatos [Habernal, I. e Iryna, G. (2016)](https://www.aclweb.org/anthology/P16-1150.pdf), transmitindo precisão e convencimento em arguições de maneira geral. 

O problema é que mesmo em democracias nem sempre temos segurança sobre a confiabilidade fonte dos números, e mesmo quando este problema não existe, estamos sujeitos à interpretação de quem nos apresenta o dado. Uma mesma fonte de informação de estatísticas pode muito bem  possibilitar diferentes interpretações das mesmas [Freeley e Steinberg, (p.198-199, 2008)](https://books.google.com.br/books?hl=en&lr=&id=1Y0WAAAAQBAJ&oi=fnd&pg=PP1&dq=(Freeley+And+Steinberg,+2008)&ots=saDCb6RMdV&sig=SNw4mACSYRotAQ35ZnWbvp0D4d4&redir_esc=y#v=onepage&q=number&f=false). 

Quem não se lembra da polêmica em março sobre o boletim publicado pelo ministério da economia separando [PIB Público e PIB Privado](https://economia.uol.com.br/noticias/redacao/2020/03/06/pib-privado-e-pib-publico-analise.htm)? Mesmo com especialistas divergindo sobre o uso da metodologia, a conta em si não foi feita com números fabricados: os números estão lá sendo apresentados de forma a corroborar uma narrativa.

Mas como saber se essa narrativa faz sentido? Essa é a pergunta relevante para o debate público que pode ou não ter uma resposta clara. 

É em cima disto que espero guiar o resto do texto. Estamos em uma época delicada em que crise econômica, crise sanitária e eclosão social se apresentam ao mesmo tempo em um efervescente debate público, e por essa razão vamos falar aqui sobre algumas formas de interpretar a leitura dos números que constituem as narrativas que nos são apresentados todos os dias.

### Indicadores e a pandemia

Indicadores são ferramentas de análise úteis para que possamos agregar e tentar compreender dados que refletem alguma situação social, mas ao mesmo tempo podem ser de difícil interpretação.

Entre 2000 e 2018 o Brasil conseguiu reduzir a [mortalidade neonatal](https://data.worldbank.org/indicator/SH.DYN.NMRT) (morte de crianças até 27 dia após nascerem divididas por 1.000 nascimentos) em 56%, para se ter uma comparação, a Noruega, o país conhecido por ter o [mais elevado grau de desenvolvimento humano em 2019](http://hdr.undp.org/en/content/2019-human-development-index-ranking) performou para o mesmo período uma taxa de 44%. Então não só conseguimos atingir um patamar de redução da mortalidade neonatal elevadíssimo, como também superamos em performance um país desenvolvido!

{{< plotly-chart 1_reducao_neonatal >}}

Incrível, não? Talvez nem tanto. A Noruega possuía em 2000 uma taxa de 2,7 mortos por 1.000 nascidos vivos. Em 2018 essa taxa era de 1,5, colocando o país em 6º no ranking de menor mortalidade, não tão distante dos primeiros colocados, Japão e São Marino, com o patamar de 0,9.

Ao mesmo tempo, o Brasil, que apresentava uma taxa de 18,3 recém nascidos mortos em 2000, reduziu-a 8,1 em 2018. Embora expressiva, a redução coloca o país na 62º posição do ranking, perto de Barbados e das Ilhas Salomão.

{{< plotly-chart 1_mortalidade_neonatal >}}




Imaginemos agora que estamos olhando três países com **populações totais diferentes**, mas que **todo o resto seja igual**:  como composição da população, riqueza, problemas sociais, e, principalmente, que um viajante trouxe o vírus o mesmo dia. em cada um desses lugares.

A população do **País A** é de 100 milhões de pessoas, a do **País B** 200 milhões e, por fim, do **País C** 800 milhões.

A conta do indicador de óbitos por milhão para cada instante no tempo é feita da seguinte forma: 

<p align=center>$\frac{ÓbitosAcumulados}{PopulaçãoTotal}. 1.000.000$</p>

{{< plotly-chart 1_obitos_pm >}} 

Ou seja, sabemos que o indicador para o **País A** será sempre  $\frac{ÓbitosAcumulados}{100}$ o do **País B** $\frac{ÓbitosAcumulados}{200}$ e o **País C** $\frac{ÓbitosAcumulados}{800}$. Isso significa que, como os óbitos são iguais em nosso exemplo, os Países **B** e **C** terão uma taxa respectivamente sempre 2x e 8x menor do que a do País A **simplesmente porque suas populações são maiores** apesar de terem a mesma regra de dispersão do vírus e, consequentemente o mesmo número de óbitos! 

O que isso nos diz sobre as taxas de morte por milhão na pandemia? Que são inúteis? De forma alguma! São uma forma indicador importante para sabermos o grau de devastação como proporção da população do país, mas não nos dizem necessariamente sobre o desempenho no controle da disseminação da doença uma vez que em todos os países de nosso exemplo foram mortos o mesmo número de indivíduos.

De fato, o esforço das medidas de contenção na pandemia são para reduzir a taxa de reprodutibilidade do vírus e frear a velocidade de disseminação da doença. Medidas de distanciamento social, por exemplo, buscam fazer com que um infectado atinja menos pessoas do que atingiria em média. Para frear o crescimento exponencial uma política eficiente de saúde teria de conseguir essa taxa inferior a 1 FONTE. 

### Causa,  correlação e a discriminação

### Somos naturalmente péssimos em entender números

### Fake news e dados errados

https://piaui.folha.uol.com.br/lupa/2019/11/27/ciro-gomes-canal-livre/

https://piaui.folha.uol.com.br/lupa/2020/04/01/osmar-terra-coronavirus-holanda/

### Em quem acreditar?

### Então, como ler um número?

### Referências

https://www.irishtimes.com/news/vatican-closes-swiss-guard-case-1.150637

https://en.wikipedia.org/wiki/Animal_Farm

https://economia.uol.com.br/noticias/redacao/2020/03/06/pib-privado-e-pib-publico-analise.htm

[Bergson, Abram. "Reliability and usability of Soviet statistics: A summary appraisal." *The American Statistician* 7, no. 3 (1953): 13-16.](https://www.tandfonline.com/doi/abs/10.1080/00031305.1953.10481990?journalCode=utas20)

[Habernal, Ivan, and Iryna Gurevych. "Which argument is more convincing?  analyzing and predicting convincingness of web arguments using  bidirectional lstm." In *Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)*, pp. 1589-1599. 2016.](https://www.aclweb.org/anthology/P16-1150.pdf)

http://hdr.undp.org/en/content/2019-human-development-index-ranking

[França, Elisabeth, and Sônia Lansky. "Mortalidade infantil neonatal no Brasil: situação, tendências e perspectivas." *Anais* (2016): 1-29.](http://www.abep.org.br/publicacoes/index.php/anais/article/download/1763/1723)

https://covid.saude.gov.br/