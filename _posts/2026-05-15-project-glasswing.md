---
layout: post
title: "Project Glasswing: defesa cibernética ou a maior jogada de marketing da era da IA?"
description: "A Anthropic dominou o ciclo de notícias global com o Claude Mythos e o Project Glasswing. Mas por trás da narrativa de segurança nacional, há benchmarks não verificáveis, US$ 100 milhões em créditos estratégicos e um modelo que ninguém pode avaliar."
keywords: "Project Glasswing, Claude Mythos, Anthropic marketing, cibersegurança IA, benchmarks IA, soberania digital, segurança nacional IA, IA e vulnerabilidades, model hype, inteligência artificial"
published: true
lang: pt-br
date: 2026-05-15
permalink: "/project-glasswing-marketing-ou-defesa-cibernetica/"
categories: ["IA & Inovação", "Segurança Digital", "Reflexões & Ensaios"]
image: "/img/"
og_image: "/img/"
---

![](/img/)

# Project Glasswing: defesa cibernética ou a maior jogada de marketing da era da IA?

*Por trás da narrativa de segurança nacional e do medo de vulnerabilidades catastróficas, existe um modelo que ninguém pode avaliar — e um orçamento de US$ 100 milhões em créditos que não é caridade.*

---

Na primeira semana de abril de 2026, a Anthropic conseguiu algo que nenhuma outra empresa de inteligência artificial havia logrado com tanta eficácia: dominar completamente o ciclo de notícias global sem sequer lançar um produto ao público. O veículo? O Claude Mythos Preview — um modelo de linguagem que a empresa descreve como o mais poderoso que já criou — e o Project Glasswing, uma coalizão de gigantes como Microsoft, Google, Amazon, Apple e NVIDIA, reunidos sob a bandeira urgente da cibersegurança. A mensagem transmitida ao mundo foi clara: "nosso modelo é tão perigoso que não podemos liberá-lo". Mas, se formos honestos, essa frase deveria ser lida de outra forma: "nosso modelo é tão bom que vocês precisam nos pagar mais e mais para usá-lo".

## O espetáculo do medo controlado

A narrativa construída pela Anthropic segue um roteiro quase cinematográfico. Primeiro, um vazamento "acidental" de documentos internos foi descoberto pela Fortune no final de março, revelando a existência de um modelo batizado com um nome mitológico — Mythos — descrito internamente como "de longe o modelo de IA mais poderoso que já desenvolvemos". O vazamento, convenientemente encontrado em um repositório público de dados não protegido, gerou uma onda de expectativa na imprensa tecnológica. Depois, veio o anúncio oficial: o modelo era tão capaz em cibersegurança que precisava ser restrito, liberado apenas para parceiros selecionados em um programa chamado Project Glasswing. O resultado? Manchetes em todos os grandes veículos de comunicação do mundo. Tom Friedman entrou em pânico no New York Times. O presidente do Federal Reserve se reuniu com CEOs de bancos para discutir as implicações. A narrativa "este modelo é perigoso demais" funcionou perfeitamente como o melhor anúncio publicitário que dinheiro nenhum poderia comprar.

## Os números que não fecham

Vamos aos fatos concretos. A Anthropic afirma que o Mythos encontrou "milhares de vulnerabilidades de alta severidade" em todos os principais sistemas operacionais e navegadores. Impressionante — até você olhar mais de perto.

Dos milhares de vulnerabilidades alegadas, apenas 198 foram manualmente revisadas por especialistas contratados. É a partir dessa amostra minúscula que a Anthropic extrapola a confiabilidade das restantes, afirmando que, em 89% dos casos, seus auditores concordaram com a avaliação de severidade do modelo. Ou seja, a grande maioria dos "milhares" de bugs nunca foi verificada por humanos. Estamos diante de uma projeção estatística sendo vendida como fato consumado.

E entre os casos que a própria Anthropic detalhou publicamente, as contradições saltam aos olhos. A famosa vulnerabilidade no FFmpeg, que existia há 16 anos? A própria análise técnica da empresa admite que "este bug não é uma vulnerabilidade de severidade crítica" e que "seria desafiador transformar esta vulnerabilidade em um exploit funcional". A exploração no Firefox? Foi feita com o sandboxing desativado — ou seja, em condições que não refletem o uso real do navegador. É como testar a resistência de uma porta blindada depois de retirar a fechadura.

Nos testes de estilo OSS-Fuzz em mais de 7.000 repositórios de código aberto, o Mythos encontrou crashes exploráveis em cerca de 600 casos e apenas 10 vulnerabilidades realmente severas. Isso é melhor do que o Opus 4.6 e o Sonnet 4.6? Sem dúvida. Mas está longe dos "milhares de vulnerabilidades devastadoras" que a cobertura jornalística sugere.

## Mythos vs. Sonnet: a comparação que você não pode fazer

Aqui reside o ponto central desta crítica: ninguém fora da Anthropic e de seus parceiros selecionados pode avaliar independentemente o Claude Mythos Preview. O modelo não foi disponibilizado ao público. Não há API aberta. Não há benchmarks reprodutíveis por terceiros. O único dado comparativo oferecido é o benchmark CyberGym, onde o Mythos alcançou 83,1% contra 66,6% do Opus 4.6. Uma diferença relevante, mas em um único benchmark, controlado pela própria empresa que desenvolveu o modelo.

Como observou a especialista em segurança de sistemas críticos Heidy Khlaaf: não há benchmarks comparativos com ferramentas tradicionais de análise estática, verificação formal ou outros modelos concorrentes. A empresa Aisle, de segurança em IA, testou modelos menores e mais baratos nas mesmas vulnerabilidades destacadas pela Anthropic e descobriu que eles conseguiam realizar boa parte da mesma análise. O pesquisador Ramez Naam demonstrou que, ao normalizar as métricas internas da Anthropic com o ECI público da Epoch AI Research, o Mythos está "praticamente na tendência, apenas ligeiramente acima do GPT 5.4" — ou seja, é evolução incremental, não revolução.

Quando alguém diz "confie em mim, é incrível, mas você não pode verificar", a resposta adequada não é entusiasmo — é ceticismo.

## Os US$ 100 milhões que não são caridade

A Anthropic comprometeu até US$ 100 milhões em créditos de uso do Mythos Preview para os parceiros do Project Glasswing, além de US$ 4 milhões em doações diretas a organizações de segurança open source. À primeira vista, parece generosidade. Na prática, é uma estratégia clássica de aquisição de clientes corporativos.

Ao oferecer créditos generosos para que Microsoft, Google, AWS, NVIDIA e mais de 40 outras organizações integrem o Mythos em seus fluxos de trabalho de segurança, a Anthropic está criando dependência. Uma vez que essas empresas treinem seus processos em torno do modelo, a migração será custosa e improvável. É o modelo de negócio das drogas — a primeira dose é de graça. O dado revelador é que o documento vazado pela Fortune mencionava não apenas o Mythos, mas também um encontro de CEOs na Europa, parte do esforço da Anthropic para vender seus modelos a grandes clientes corporativos. O Project Glasswing não é filantropia: é prospecção comercial vestida de responsabilidade social.

## A empresa que lucra com o medo que ela mesma criou

Há uma ironia estrutural no posicionamento da Anthropic. A empresa que se autoproclama como a mais preocupada com segurança em IA é a mesma que está criando e amplificando o medo sobre as capacidades de seus próprios modelos. Como bem observou David Sacks, ex-czar de IA da Casa Branca: "O mundo não tem escolha senão levar a ameaça cibernética associada ao Mythos a sério. Mas é difícil ignorar que a Anthropic tem um histórico de táticas de alarmismo."

O artigo da Communications of the ACM capturou o paradoxo com precisão: é impossível separar preocupações reais de alarmismo usado como estratégia de marketing e, por isso, é impossível separar pânico justificado de mera publicidade. A Anthropic criou um cenário onde questionar suas afirmações parece irresponsável — afinal, e se o modelo realmente for tão perigoso? — mas aceitá-las sem verificação é igualmente irresponsável.

## O que realmente sabemos

Separando o sinal do ruído, o que podemos afirmar com razoável confiança é que o Mythos é, sim, um modelo superior ao Opus 4.6 em tarefas de cibersegurança. Ele encontrou vulnerabilidades reais, algumas das quais já foram corrigidas. A iniciativa de reportar bugs a mantenedores de software é genuinamente positiva. Mas a magnitude do avanço, a escala real da ameaça e a suposta impossibilidade de liberar o modelo ao público — tudo isso permanece no domínio das afirmações não verificáveis. Modelos de código aberto já conseguem realizar parte do que o Mythos faz. A diferença pode ser de grau, não de natureza.

E convenhamos: se o modelo fosse verdadeiramente tão perigoso que não pudesse ser liberado, a decisão responsável seria não anunciá-lo com uma campanha de relações públicas de escala global. O fato de que a Anthropic escolheu transformar a restrição em espetáculo — com logotipos de parceiros, depoimentos de CISOs e uma página dedicada digna de um lançamento de produto da Apple — diz mais sobre suas intenções comerciais do que sobre suas preocupações com segurança.

## Conclusão: entre o legítimo e o oportunismo

Não se trata de negar que modelos de IA estão ficando melhores em encontrar vulnerabilidades. Estão. Não se trata de negar que isso tem implicações sérias para a cibersegurança global. Tem. O problema é que a Anthropic está instrumentalizando uma preocupação legítima para construir uma narrativa de marketing impossível de verificar independentemente, fechando contratos bilionários com as maiores empresas do mundo enquanto o público aplaude o que acredita ser um gesto de responsabilidade.

Quando você não pode testar o modelo, não pode reproduzir os benchmarks, não pode verificar as alegações, e a única fonte de informação é a própria empresa que lucra com o alarmismo — você não está diante de ciência, está diante de publicidade. Uma publicidade muito bem feita, é verdade. Tão bem feita que conseguiu fazer o mundo inteiro discutir um produto que ninguém pode usar.
