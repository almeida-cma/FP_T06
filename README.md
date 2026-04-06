#**📚 COMPORTAMENTO DO BUBBLE SORT**
##O Bubble Sort (ordenação por bolha) funciona da seguinte forma:

Comparações consecutivas: Percorre o vetor várias vezes, comparando elementos adjacentes (vizinhos)

Trocas: Se um elemento for maior que o próximo, eles trocam de posição

Elementos flutuam: Os maiores valores vão "flutuando" para o final do vetor a cada passagem

Passagens: São necessárias (tamanho - 1) passagens para garantir que todos os elementos estejam ordenados

Redução a cada passagem: A cada passagem, o próximo maior elemento se fixa no final, reduzindo a necessidade de comparações

Exemplo prático com os números:

1ª passagem: 54,23,22,20,9 → 23,22,20,9,54

2ª passagem: 23,22,20,9,54 → 22,20,9,23,54

3ª passagem: 22,20,9,23,54 → 20,9,22,23,54

4ª passagem: 20,9,22,23,54 → 9,20,22,23,54

Resultado final: Vetor ordenado de forma crescente.
