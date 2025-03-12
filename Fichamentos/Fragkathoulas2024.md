# Local Explanations and Self-Explanations for Assessing Faithfulness in black-box LLMs

Christos Fragkathoulas and Odysseas Spyridon Chlapanis. 2024. Local Explanations and Self-Explanations for Assessing Faithfulness in black-box LLMs. In Proceedings of the 13th Hellenic Conference on Artificial Intelligence (SETN '24). Association for Computing Machinery, New York, NY, USA, Article 56, 1–5. https://doi.org/10.1145/3688671.3688775

## 1. Fichamento de Conteúdo

O estudo propõe uma nova abordagem para avaliar a fidelidade (faithfulness) de modelos de linguagem de grande escala (LLMs) em cenários de caixa preta (black-box), onde o acesso à arquitetura interna do modelo é limitado. Os autores introduzem uma técnica de explicabilidade baseada em perturbações locais e autoexplicações (self-explanations) para identificar as partes do contexto que são suficientes e necessárias para que o modelo gere respostas corretas. A metodologia proposta é inspirada na abordagem leave-one-out (LOO), que omite partes do contexto para determinar quais palavras ou trechos são essenciais para a geração de respostas corretas. A fidelidade do modelo é avaliada comparando essas partes críticas com as autoexplicações geradas pelo próprio modelo. O experimento é validado usando o conjunto de dados "Natural Questions", que contém perguntas de usuários reais e trechos de artigos da Wikipedia como contexto. Os resultados preliminares mostram que a técnica proposta é eficaz para explicar decisões do modelo e avaliar sua fidelidade, com o GPT-4o demonstrando maior fidelidade em comparação ao GPT-3.5.

## 2. Fichamento Bibliográfico

- _Explicabilidade (Explainability)_: A capacidade de um modelo de descrever seu processo de decisão de forma compreensível para humanos, crucial para aumentar a confiança e a transparência em sistemas de IA (ex.: DeepThink, do modelo DeepSeek)
- _Faithfulness (Fidelidade)_: A medida de quão bem as explicações geradas por um modelo refletem seu processo real de tomada de decisão.
- Leave-One-_ut (LOO)_: Técnica de perturbação que omite partes do contexto para identificar elementos essenciais para a geração de respostas corretas.
- _Natural Questions Dataset_: Conjunto de dados usado para avaliar sistemas de questionamento e resposta (QA), contendo perguntas reais e trechos de contexto da Wikipedia

## 3. Fichamento de Citações

- "_Explainable AI is crucial in helping users trust and effectively utilize AI systems, enabling developers to debug and improve models, ensuring compliance with regulatory standards, and mitigating biases within models_"
- "_By systematically omitting parts of the provided context, we can determine specific important words that, without them, the model is unable to respond correctly_"
- "_Unlike previous work, who are using only the exact-match accuracy metric for evaluation, we have designed a hybrid metric that combines the results of exact-match, normalized exact-match, fuzzy exact-match, [...] date transformations [...]. Exact matchoften fails due to natural language variability, such as different formatting of names or dates._"
