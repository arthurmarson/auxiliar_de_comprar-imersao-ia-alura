# Assistente de Decisão de Compras Inteligente

## Agente 1: Coletor de Informações

Este agente inicia o processo coletando todas as informações relevantes do usuário através de perguntas objetivas e práticas.

**Exemplo de diálogo:**

"Olá! Sou o primeiro agente do seu assistente de decisão de compras. Vou fazer algumas perguntas objetivas para entender melhor sua situação e o produto que está considerando comprar.

1.  Qual é o produto específico que você está pensando em adquirir? (modelo, marca, especificações)
2.  Qual é o preço deste produto?
3.  Qual é o seu orçamento disponível para esta compra?
4.  Esta compra é uma necessidade ou um desejo?
5.  Com que frequência você usaria este produto?
6.  Você já possui algo similar que ainda funciona?
7.  Qual é sua maior prioridade nesta compra? (qualidade, preço, durabilidade, funcionalidades)
8.  Existe alguma urgência para realizar esta compra?"

## Agente 2: Pesquisador de Mercado

Este agente analisa as alternativas disponíveis no mercado e compara o produto desejado com outras opções. Ele utiliza as informações do Agente 1 como ponto de partida.

**Exemplo de processo:**

-   Identificar produtos similares em diferentes faixas de preço e com especificações variadas, baseado nas prioridades e orçamento do usuário.
-   Comparar especificações técnicas e recursos entre o produto desejado e as alternativas encontradas.
-   Analisar custo-benefício inicial das principais alternativas identificadas.
-   Verificar tendências de preço (se está em promoção ou prestes a baixar) e histórico de preços.
-   Identificar novos lançamentos ou tecnologias que podem tornar o produto atual ou as alternativas obsoletas.

## Agente 3: Análise de Reviews e Reputação

Este novo agente recebe as informações sobre o produto desejado e as alternativas identificadas pelo Agente 2. Ele busca e sintetiza informações qualitativas sobre a experiência de outros consumidores.

**Exemplo de processo:**

-   Coletar reviews e avaliações de usuários em plataformas de e-commerce, sites especializados e fóruns de discussão.
-   Analisar a reputação da marca e do vendedor (se aplicável).
-   Identificar pontos positivos e negativos recorrentes mencionados nos reviews.
-   Comparar a satisfação geral dos usuários com o produto desejado versus as alternativas.
-   Sintetizar as principais reclamações e elogios encontrados.
-   Gerar um resumo conciso da "voz do consumidor" para cada produto analisado.

## Agente 4: Analista Financeiro

Este agente recebe as informações do Agente 1 (orçamento e situação financeira), Agente 2 (preços e alternativas) e Agente 3 (custo de propriedade implícito em reviews, como durabilidade e problemas recorrentes que geram gastos). Ele avalia o impacto financeiro da compra na situação particular do usuário.

**Exemplo de análise:**

-   Calcular o impacto percentual da compra no orçamento mensal do usuário, considerando o preço atual ou otimizado (se o Agente 2 ou um futuro agente de otimização identificar uma oportunidade).
-   Avaliar o custo total de propriedade (incluindo manutenção, energia, acessórios e possíveis custos identificados nos reviews como problemas frequentes).
-   Estimar a depreciação do produto com base em dados de mercado e na percepção de durabilidade dos usuários (insights do Agente 3).
-   Analisar formas de pagamento, possíveis juros e o impacto de parcelamentos.
-   Verificar se o momento financeiro é adequado para a compra, considerando os objetivos financeiros do usuário.
-   Sugerir alternativas financeiras como alugar, compartilhar ou aguardar por melhores condições.

## Agente 5: Tomador de Decisão Final

Este agente integra todas as informações e análises dos agentes anteriores (Agente 1: dados do usuário, Agente 2: pesquisa de mercado, Agente 3: insights de reviews e reputação, Agente 4: análise financeira) e fornece um veredito claro sobre a recomendação de compra.

**Exemplo de veredito:**

"Com base em todas as informações coletadas e análises realizadas, meu veredito sobre a compra do [produto] é:

**RECOMENDADO** (ou NÃO RECOMENDADO / RECOMENDADO COM RESSALVAS)

Justificativa principal:
-   [Resumo conciso da principal razão para a recomendação, integrando insights de mercado, financeiros e de reputação]

Fatores decisivos:
1.  [Fator financeiro relevante - baseado na análise do Agente 4]
2.  [Fator de utilidade/necessidade - baseado nas informações do Agente 1]
3.  [Fator de mercado/timing - baseado na análise do Agente 2]
4.  [Fator de experiência do usuário/reputação - baseado na análise do Agente 3]

Pontos de atenção (baseado nos reviews e análises):
-   [Mencionar um ou dois pontos negativos recorrentes ou ressalvas importantes identificadas pelo Agente 3 e 4]

Recomendações adicionais:
-   [Sugestão específica sobre como, quando ou onde realizar a compra, considerando os insights de todos os agentes]
-   [Alternativa a considerar, se aplicável e alinhada com as análises]
-   [Precauções a tomar, especialmente com base nos problemas identificados nos reviews]

Esta recomendação foi personalizada considerando seu perfil, necessidades, situação financeira atual e a experiência de outros consumidores. A decisão final, naturalmente, cabe a você."

O sistema completo funciona de forma integrada, com cada agente utilizando as informações coletadas pelos agentes anteriores e complementando a análise até chegar ao veredito final personalizado que realmente auxilia o usuário a tomar uma decisão informada e completa de compra, considerando não apenas dados técnicos e financeiros, mas também a experiência real de outros usuários.