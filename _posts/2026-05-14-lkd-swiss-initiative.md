---
layout: post
title: "A Suíça está construindo a IA que o Judiciário brasileiro deveria estar exigindo"
description: "A Swiss AI Initiative mostra que é possível construir IA auditável para uso público. Enquanto o Brasil usa modelos proprietários sem transparência, a fundamentação constitucional das decisões judiciais está em risco."
keywords: "soberania digital, IA open source, Swiss AI Initiative, judiciário brasileiro, CNJ resolução 615, LGPD decisões automatizadas, viés common law, IA advocacia, transparência judicial, modelo de linguagem"
published: true
lang: pt-br
date: 2026-05-14
permalink: "/suica-ia-judiciario-brasileiro/"
categories: ["IA & Inovação", "Direito Digital", "Privacidade & Vigilância"]
image: "/img/"
og_image: "/img/"
---

![](/img/)

# A Suíça está construindo a IA que o Judiciário brasileiro deveria estar exigindo

A Suíça colocou dinheiro público num supercomputador, reuniu duas universidades federais (ETH Zürich e EPFL) e começou a treinar modelos de linguagem com pesos abertos, corpus auditável e *cutoff* declarado. Chama-se Swiss AI Initiative. A motivação não é xenofobia tecnológica nem orgulho alpino — é uma leitura fria do que soberania digital significa quando se trata de instituições públicas.

Enquanto isso, no Brasil, magistrados resumem autos usando ChatGPT, Copilot, Gemini. Sem exigência de divulgação do modelo. Sem *cutoff* declarado. Sem controle sobre o que foi posto no treino. Sem reprodutibilidade da resposta.

Isso não é detalhe técnico. É um problema constitucional.

**Quatro perguntas que você não consegue responder sobre a IA que o juiz está usando**

Quando a Vara decide "com auxílio de IA", tente responder:

1. Qual é o modelo exato — versão, parâmetros, provedor?
2. Qual a data de corte do treinamento? A EC 103/2019 entrou? A Reforma Tributária de 2023 entrou? A Resolução CNJ 615/2025 entrou?
3. Qual a composição do corpus de treinamento? Quanto por cento é jurisprudência americana em inglês? Quanto por cento é doutrina portuguesa? Quanto por cento é texto de rede social? O quanto isso afeta a minha decisão e o meu processo? — Impossível saber.
4. A resposta é reprodutível? Se eu rodar o mesmo prompt daqui a três meses, obtenho o mesmo resultado, ou o modelo mudou por baixo dos panos?

Se você não consegue responder, o perito-máquina da decisão é invisível. E perito invisível, em processo, é nulidade esperando para ser arguida — pelo menos no mundo ideal.

**Por que isso importa: viés de *common law* contaminando decisão civilista**

Os grandes modelos comerciais foram treinados em corpora predominantemente anglófonos. Quando esse modelo "interpreta" um caso brasileiro, o inconsciente da máquina é o *stare decisis* — o princípio americano de que o precedente vincula. Nosso sistema é *civil law*: a lei vincula, o precedente orienta (com exceções específicas, art. 927 do CPC) — em tese seria assim; atualmente, a jurisprudência está sendo mais poderosa do que a legislação.

Exemplo concreto: peça ao modelo para analisar a aplicação de uma tese do STJ em caso de direito contratual. Ele tende a tratar o precedente como regra autoaplicável, no estilo *holding* americano. Nosso sistema tem nuances de equilíbrio contratual e imprevisibilidade que são difíceis de determinar. A resposta sai em português, com aparência de parecer técnico. Mas a espinha dorsal é *Marbury v. Madison*, não a doutrina nacional.

Um juiz pressionado por meta de produtividade lê, acha convincente, cola no voto. O advogado recebe uma decisão que soa fundamentada, mas cuja lógica subjacente nasceu em San Francisco.

**O que o art. 93, IX da Constituição tem a ver com isso**

Toda decisão judicial precisa ser fundamentada, sob pena de nulidade. Fundamentação, na leitura consolidada do STF, é o caminho cognitivo do juiz — não a mera transcrição de ementas.

Quando parte desse caminho cognitivo foi terceirizada para uma caixa-preta proprietária, o dever de fundamentação vira ficção. O juiz fundamenta o que entendeu. Mas o que ele entendeu foi filtrado por um modelo cujos vieses ele não conhece, cujos dados de treino ele não viu e cujo comportamento ele não pode reproduzir.

Some-se o art. 20 da LGPD, que dá ao cidadão o direito de revisão de decisões automatizadas. Como se revisa o que não se pode inspecionar?

**O que modelo open-source resolve (e o que não resolve)**

Open-source não é mágica. Há modelo aberto mal treinado. Há modelo aberto com viés grave. Há modelo aberto que nenhum órgão público consegue auditar porque falta pessoal técnico.

O que modelo aberto entrega:

- **Auditoria**: especialista independente pode inspecionar pesos, dados e arquitetura.
- **Reprodutibilidade**: mesma entrada, mesma versão, mesma saída — perícia passa a ser possível.
- **Responsabilização**: quando o erro aparece, há rastro técnico para atribuir causa.

O que modelo aberto não entrega:

- Garantia de que o corpus é juridicamente adequado.
- Substituto para validação humana de cada citação legal e jurisprudencial.
- Isenção do advogado ou do juiz quanto ao resultado.

Na hierarquia do Direito, open-source é pré-requisito, não conclusão. É o que permite a perícia. Sem pericialidade, não há contraditório técnico real.

**O que o CNJ já disse — e o que ainda não disse**

A Resolução CNJ 615/2025 tateia o tema. Exige documentação, avaliação de impacto e transparência sobre uso de IA no Judiciário. É avanço. Mas não exige abertura de modelo. Não proíbe o uso de IA proprietária para tarefas cognitivas. Não resolve o problema da jurisdição estrangeira dos provedores americanos (CLOUD Act x LGPD).

O texto da Resolução fala em "transparência". A prática, no gabinete, ainda é usar a ferramenta que chegou primeiro — geralmente a comercial.

**A Swiss AI não é modelo perfeito. É sinal.**

Não estou propondo copiar a Suíça. Nosso orçamento, nossa estrutura e nosso tamanho de Judiciário são outros. O que a Swiss AI mostra é que é tecnicamente possível um Estado construir IA auditável para uso público. Não é utopia. É questão de prioridade orçamentária e vontade institucional.

Enquanto isso não chega, o advogado que trabalha com IA tem obrigação: saber qual modelo está usando, declarar nas peças quando for o caso, conferir cada citação, nunca aceitar como definitivo o que o modelo escreveu. É o mínimo de higiene cognitiva que o dever de probidade exige.

**Pergunta aberta**

Você, advogado, se pedisse hoje à Vara uma certidão sobre qual modelo de IA foi usado no resumo dos autos do seu cliente — receberia resposta? Ou o pedido sequer seria processado? Me conta nos comentários o que você faria se essa caixa-preta entrasse como argumento no próximo recurso.
