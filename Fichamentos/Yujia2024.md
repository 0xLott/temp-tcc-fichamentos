# Security Weaknesses of Copilot-Generated Code in GitHub Projects: An Empirical Study

Yujia Fu, Peng Liang, Amjed Tahir, Zengyang Li, Mojtaba Shahin, Jiaxin Yu, and Jinfu Chen. 2025. Security Weaknesses of Copilot-Generated Code in GitHub Projects: An Empirical Study. ACM Trans. Softw. Eng. Methodol. Just Accepted (February 2025). https://doi.org/10.1145/3716848

## 1. Fichamento de Conteúdo

O artigo aborda os desafios de segurança associados ao uso de ferramentas de geração de código baseadas em modelos de linguagem de grande escala (LLMs), como o GitHub Copilot, CodeWhisperer e Codeium. Essas ferramentas, embora populares por sua capacidade de gerar código funcional, frequentemente produzem código inseguro que pode ser integrado em bases de código reais. O estudo empírico realizado pelos autores analisou 733 trechos de código gerados por essas ferramentas em projetos do GitHub, identificando que 29,5% dos trechos em Python e 24,2% em JavaScript possuem vulnerabilidades de segurança. Essas vulnerabilidades abrangem 43 categorias da Common Weakness Enumeration (CWE), incluindo problemas graves como CWE-330 (Uso de valores aleatórios insuficientes), CWE-94 (Controle impróprio de geração de código) e CWE-79 (Cross-site Scripting). O estudo também explorou o uso do Copilot Chat para corrigir problemas de segurança no código gerado pelo Copilot, mostrando que até 55,5% das vulnerabilidades podem ser corrigidas quando o Copilot Chat é fornecido com mensagens de alerta de ferramentas de análise estática. Por fim, o artigo oferece sugestões para mitigar problemas de segurança em código gerado por IA.

## 2. Fichamento Bibliográfico

- _CWE (Common Weakness Enumeration)_: Uma lista de vulnerabilidades de software conhecidas e comuns, usada no estudo para classificar e identificar fraquezas de segurança.
- _GitHub Copilot_: Ferramenta de geração de código baseada em IA, desenvolvida pela GitHub em colaboração com a OpenAI, que sugere trechos de código com base em comentários ou código existente.
- _Code Injection_: Vulnerabilidade onde código malicioso é injetado e executado em um sistema, frequentemente devido à falta de validação de entrada.
- _Cross-site Scripting_: Vulnerabilidade de segurança que permite a injeção de scripts maliciosos em páginas web visualizadas por outros usuários.

## 3. Fichamento de Citações

- "_[...] AI models like Large Language Models (LLMs) have gained increased popularity due to their ability to produce functional code. However, their usage presents security challenges, often resulting in insecure code merging into the code base_"
- "_around 30% of code snippets have security weaknesses_"
- "_It is possible to use Copilot Chat to fix security issues in Copilot-generated code_"
