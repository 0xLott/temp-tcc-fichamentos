# An initial investigation of ChatGPT unit test generation capability

Vitor Guilherme and Auri Vincenzi. 2023. An initial investigation of ChatGPT unit test generation capability. In Proceedings of the 8th Brazilian Symposium on Systematic and Automated Software Testing (SAST '23). Association for Computing Machinery, New York, NY, USA, 15–24. (https://doi.org/10.1145/3624032.3624035)

## 1. Fichamento de Conteúdo

O artigo explora o potencial do ChatGPT, um _Large Language Model_ (LLM) da OpenAI, na geração automatizada de testes unitários para a linguagem Java. Para isso, realiza um estudo comparativo entre testes gerados pelo ChatGPT, seguindo o framework JUnit, e testes produzidos por ferramentas tradicionais de geração automatizada, como EvoSuite, Palus, JTExpert e Randoop. A análise é conduzida com base em três métricas principais: cobertura de código, score de mutação e taxa de sucesso da _build_ e execução dos testes. Os autores utilizam a ferramenta JavaNCSS7 para realizar uma Análise Estática de Código (AES), avaliando aspectos como complexidade ciclomática e número de comandos, entre outros, a fim de mensurar a qualidade dos testes gerados. Os resultados deste estudo são relevantes pois demonstram que, embora os LLMs possuam grande potencial de ação na automação de testes, seu uso isolado ainda apresenta fragilidades persistentes. O artigo reforça que a verificação e o refinamento humano continuam sendo essenciais para garantir a qualidade e confiabilidade dos testes gerados. Além disso, destaca-se a possibilidade promissora de combinar LLMs com ferramentas tradicionais de geração de testes, criando uma estratégia híbrida mais eficaz.

## 2. Fichamento Bibliográfico

- **Testes de mutação** avaliam a qualidade de testes unitários ao introduzir alterações pontuais (mutações) no código e verificando se os testes detectam essas modificações, ajudando a medir sua eficácia e resiliência na detecção de bugs.

- **O ajuste de temperatura** (de LLMs) configura a aleatoriedade das respostas de um modelo de linguagem, onde uma temperatura mais baixa torna os resultados mais previsíveis e uma temperatura mais alta aumenta a criatividade das respostas geradas.

- **Análise Estática de Código (AES)** é o processo de examinar o código-fonte sem executá-lo a fim de identificar possíveis problemas relacionados a vulnerabilidades de segurança ou complexidade do código, usando ferramentas automatizadas para extração de métricas.

## 3. Fichamento de Citações

- _"[...] manually generating comprehensive unit tests can be a challenging and time-consuming task, often requiring significant effort and expertise."_
- _"[...] these prompts have a very good potential, if not to be used as a single way for unit testing generation, its
  combination in a coordinated way with traditional automatic testing generators can be very promising"_
- _"We do not think LLMs will solve all testing problems automatically. We believe a good automated testing strategy now gained important support from LLMs."_
- "[...] it is possible to develop specialized prompts to solve and generate specific test cases with human support to check and correct possible mistakes."
