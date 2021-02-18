---
title: "acórdãos tribunal de contas da união"
categories: [dados abertos, governo, crawler]
description: "base de dados dos acórdãos do TCU."
layout: post
toc: true
comments: true
hide: false
---

Os acórdãos do Tribunal de Contas da União (**[TCU](https://portal.tcu.gov.br/inicio/)**) são as decisões do órgão colegiado do tribunal. Assim, devido a repercusão geral desses acórdãos, decidi programar um crawler para coletar esses dados a partir do portal do **[TCU](https://portal.tcu.gov.br/inicio/)**. O conteúdo do dataset diz respeito aos acórdãos entre os anos de 1992 até 30/08/2019.

Ao contrário da base original onde são apresentados os números de [CPF](https://pt.wikipedia.org/wiki/Cadastro_de_pessoas_f%C3%ADsicas) em sua íntegra, o presente trabalho decidiu inserir uma máscara em toda ocorrência de CPF. Assim, estes possuem os 3 primeiros e os dois últimos dígitos mascarados, tratamento idêntico ao adotado pelo [Portal da Transparência do Executivo Federal](http://www.portaltransparencia.gov.br/).

O dataset está publicado no **kaggle** :

<a href="https://www.kaggle.com/ferraz/acordaos-tcu"><center><img src="{{ site.baseurl }}/images/posts/acordaos_tcu_1/kaggle_acordaos.png"/></center></a>

Além disso, caso tenham interesse no código de coleta dos dados o repositório é o:

<a href="https://github.com/netoferraz/acordaos-tcu"><center><img src="{{ site.baseurl }}/images/posts/acordaos_tcu_1/github_acordaos.png"/></center></a>

E aí gostaram? Comente aí ou deixe alguma sugestão!