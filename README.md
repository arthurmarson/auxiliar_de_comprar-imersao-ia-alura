# 🛒 Assistente de Decisão de Compras

> *Tomando decisões de compra mais inteligentes através de análise de IA multi-agente*

## Problema Alvo

A compra compulsiva tem se intensificado no Brasil, impulsionada por diversos fatores interligados.  Estudos recentes indicam que 73% dos brasileiros já adquiriram produtos ou serviços influenciados pela mídia. Esse comportamento é amplificado pela Teoria da Comparação Social, onde indivíduos avaliam seu valor pessoal comparando-se aos outros, muitas vezes resultando em compras para manter um padrão percebido. Além disso, o uso excessivo do cartão de crédito é notável, com os brasileiros gastando em média R$ 1.400 por mês, sendo que 83% das dívidas estão relacionadas a esse meio de pagamento. Contribuindo para esse cenário, algoritmos de publicidade personalizada analisam o comportamento online dos usuários para exibir anúncios altamente direcionados, incentivando o consumo impulsivo e o ciclo de endividamento. Esse panorama evidencia a necessidade de soluções para mitigar o impacto do consumo impulsivo na saúde financeira dos indivíduos. 


## Visão Geral da Solução 

. O Assistente de Decisão de Compras ajuda com esses problemas, pois é um sistema de IA que auxilia consumidores a tomarem decisões de compra informadas, analisando múltiplos aspectos de potenciais aquisições. Em vez de fornecer uma simples comparação de produtos, este assistente inteligente avalia sua situação pessoal, considerações financeiras, condições de mercado e experiências de usuários para entregar uma recomendação abrangente e personalizada.

## Como Funciona

Este sistema utiliza uma arquitetura de IA multi-agente onde cinco agentes especializados trabalham juntos sequencialmente, cada um construindo sobre a análise dos agentes anteriores:

### 1. Agente Coletor de Informações 📋

Este agente inicia o processo coletando informações relevantes através de perguntas direcionadas:

- Especificações do produto (marca, modelo, características)
- Preço e orçamento disponível
- Motivação da compra (necessidade vs. desejo)
- Expectativas de frequência de uso
- Alternativas existentes já possuídas
- Prioridades de compra (qualidade, preço, durabilidade, funcionalidades)
- Urgência da compra

### 2. Agente Pesquisador de Mercado 🔍

Usando as informações coletadas, este agente conduz uma análise completa de mercado:

- Identifica produtos similares em diferentes faixas de preço
- Compara especificações técnicas entre o produto desejado e alternativas
- Analisa a relação custo-benefício inicial das principais alternativas
- Investiga tendências e histórico de preços
- Avalia o ciclo de vida da tecnologia e potencial obsolescência

### 3. Agente Analista de Reviews e Reputação ⭐

Este agente sintetiza informações qualitativas sobre experiências de usuários:

- Coleta e analisa avaliações de usuários de plataformas de e-commerce e fóruns
- Avalia a reputação da marca e do vendedor
- Identifica padrões recorrentes de feedback positivo e negativo
- Compara níveis de satisfação de usuários entre alternativas
- Gera um resumo conciso da "voz do consumidor" para cada produto

### 4. Agente de Análise Financeira 💰

Este agente avalia o impacto financeiro da compra:

- Calcula o impacto proporcional no orçamento mensal do usuário
- Determina o custo total de propriedade (manutenção, energia, acessórios)
- Estima a depreciação do produto com base em dados de mercado e insights de durabilidade
- Analisa opções de pagamento e impactos de parcelamento
- Avalia se o momento financeiro atual é apropriado
- Sugere métodos alternativos de aquisição (alugar, compartilhar, esperar)

### 5. Agente de Decisão Final ✅

Este agente integra todas as análises anteriores para fornecer uma recomendação clara:

- Entrega um veredito definitivo: RECOMENDADO, NÃO RECOMENDADO ou RECOMENDADO COM RESSALVAS
- Fornece uma justificativa concisa para a recomendação
- Lista fatores decisivos de todas as dimensões analíticas
- Destaca pontos importantes a considerar com base em avaliações e análises
- Oferece recomendações adicionais sobre como, quando ou onde comprar
- Sugere alternativas, se aplicável
- Descreve precauções baseadas em problemas identificados

## Principais Características

- **Análise Multidimensional**: Avalia compras a partir de perspectivas de uso, mercado, reputação e financeira
- **Abordagem Centrada no Usuário**: Recomendações são adaptadas às circunstâncias e prioridades individuais
- **Decisões Baseadas em Dados**: Utiliza pesquisa de mercado e experiências de usuários para fornecer insights objetivos
- **Sabedoria Financeira**: Vai além da comparação de produtos para avaliar o verdadeiro impacto financeiro
- **Recomendações Claras**: Fornece orientação definitiva respeitando a autonomia do usuário

## Casos de Uso

- Avaliação de compras importantes (eletrônicos, eletrodomésticos, veículos)
- Comparação de produtos similares em diferentes faixas de preço
- Tomada de decisões de compra financeiramente responsáveis
- Compreensão do verdadeiro valor de opções premium versus econômicas
- Identificação de potenciais armadilhas ou custos ocultos antes da compra

## 📋 Exemplo de Uso

```python
# Entrada do usuário:
"PlayStation 5 slim, R$ 3800, orçamento R$ 4000, desejo, uso semanal"

# Saída do Agente 5:
✅ **RECOMENDADO COM RESSALVAS**  
- Impacto orçamentário: 95% do total  
- Alternativa sugerida: Xbox Series X (Game Pass incluso)  
- Alerta: Relatos de superaquecimento em 15% dos reviews  
- Sugestão: Aguardar Black Friday para economia média de 20%
```


## Contato

- Email: arthurmarson2006@gmail.com
- LinkedIn: https://www.linkedin.com/in/arthur-oliveira-marson/
- GitHub: https://github.com/arthurmarson

---

*O Assistente de Decisão de Compras ajuda você a comprar de forma mais inteligente, não mais difícil.*
