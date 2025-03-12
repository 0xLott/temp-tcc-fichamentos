# Benchmarking Automated Program Repair: An Extensive Study on Both Real-World and Artificial Bugs

Yicheng Ouyang, Jun Yang, and Lingming Zhang. 2024. Benchmarking Automated Program Repair: An Extensive Study on Both Real-World and Artificial Bugs. In Proceedings of the 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA 2024). Association for Computing Machinery, New York, NY, USA, 440–452. (https://doi.org/10.1145/3650212.3652140)

## 1. Fichamento de Conteúdo

O artigo apresenta a questão da falta de padronização e _benchmarks_ confiáveis na avaliação da eficiência de técnicas de _Automated Program Repair_ (APR), o que compromete a confiança nos resultados obtidos. Para enfrentar esse desafio, os autores conduzem um experimento ao executar nove técnicas baseadas em Machine Learning em um ambiente padronizado. Esse trabalho não só estabelece uma referência mais confiável para a avaliação de APR, mas também demonstra que a automação na correção de bugs é viável e eficaz, reduzindo a necessidade de intervenção humana no processo. Os resultados comprovam que as técnicas de APR baseadas em Large Language Models (LLMs) superam as demais em termos de eficácia na reparação de bugs, demonstrando o valor em se empregar IA (Inteligência Artificial) na automação de processos nesse contexto. Além disso, o artigo propõe melhorias para APR, destacando desafios como "_Unresolvable Symbol Compilability_" e "_Duplicate/no-op patches_", descritas na seção abaixo deste fichamento, fornecendo orientações para tornar essas técnicas ainda mais aplicáveis na prática.

## 2. Fichamento Bibliográfico

- APR (_Automated Program Repair_) técnica aplicada a sistemas para automaticamente corrigir defeitos, visando reduzir o esforço manual de _debugging_.
- _Unresolvable Symbol Compilability Issues_ ocorrem quando um patch gerado automaticamente faz referência a uma variável, função ou classe que não existe ou está fora do escopo, impedindo a compilação do código.
- _Duplicate/no-op patches_ são correções que não fazem alterações significativas ou são idênticos aos patches gerados anteriormente, levando ao desperdício de recursos computacionais e atraso o processo de reparo.

## 3. Fichamento de Citações

- _"[...] the study suggests a promising future for combining traditional and learning-based APR techniques, as they exhibit complementary advantages in fixing different types of bugs."_
- _"The patch compilability rate is highly correlated to the number of bugs being correctly fixed, suggesting that enhancing the patch compilability may lead to more valid fix attempts and potentially more fixed bugs."_
- _"LLM-based APR is generally less prone to overftting compared to NMT-based and traditional techniques."_
