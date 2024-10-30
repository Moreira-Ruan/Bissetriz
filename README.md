# Atividade 2: Teorema da Bissetriz Interna e Externa

Este projeto explora os conceitos das bissetrizes interna e externa em triângulos, aplicando lógica matemática e programação. O código em JavaScript permite calcular as proporções dos segmentos divididos pelas bissetrizes interna e externa de um triângulo.

## Conteúdo

- **Parte A**: Teorema da Bissetriz Interna
- **Parte B**: Teorema da Bissetriz Externa
- **Parte C**: Análise das Condições para Intersecção da Bissetriz Externa
- **Esboço Geométrico no GeoGebra**

## Como Rodar o Código

1. **Clone o repositório** ou copie o código em um arquivo `index.html`.
2. Abra o arquivo `index.html` em um navegador da web (Chrome, Firefox, etc).
3. O navegador solicitará a entrada dos comprimentos dos lados do triângulo:
   - Lado AB
   - Lado AC
   - Lado BC
4. Insira os valores conforme solicitado e pressione "OK".
5. O resultado será exibido no console do navegador, mostrando:
   - A razão dos segmentos divididos pela **bissetriz interna**.
   - A razão dos segmentos divididos pela **bissetriz externa**.

Para ver o console no navegador, pressione `F12` ou `Ctrl+Shift+I` (em alguns navegadores), vá para a aba "Console".

## Exemplo de Teste

Aqui estão alguns exemplos de comprimentos para você testar o código e verificar os resultados.

### Exemplo 1: Triângulo com Bissetriz Interna

- **Entrada**:
  - Lado AB = 5
  - Lado AC = 8
  - Lado BC = 7
- **Resultado Esperado**:
  - Razão da Bissetriz Interna: \( \frac{AB}{BC} = 5 / 7 \approx 0.71 \)
  - Razão da Bissetriz Externa: \( -\frac{AB}{BC} = -5 / 7 \approx -0.71 \)

### Exemplo 2: Triângulo com Lados Proporcionais

- **Entrada**:
  - Lado AB = 6
  - Lado AC = 9
  - Lado BC = 12
- **Resultado Esperado**:
  - Razão da Bissetriz Interna: \( \frac{AB}{BC} = 6 / 12 = 0.5 \)
  - Razão da Bissetriz Externa: \( -\frac{AB}{BC} = -6 / 12 = -0.5 \)

### Exemplo 3: Outro Triângulo com Lados Arbitrários

- **Entrada**:
  - Lado AB = 3
  - Lado AC = 4
  - Lado BC = 5
- **Resultado Esperado**:
  - Razão da Bissetriz Interna: \( \frac{AB}{BC} = 3 / 5 = 0.6 \)
  - Razão da Bissetriz Externa: \( -\frac{AB}{BC} = -3 / 5 = -0.6 \)

Esses exemplos permitem testar a precisão do código e confirmar que as divisões são calculadas corretamente.

## Créditos

Esta atividade foi desenvolvida para a disciplina de Matemática Computacional do curso de Engenharia de Software. O código foi implementado em JavaScript, com conceitos geométricos aplicados no GeoGebra para visualização e validação dos teoremas.
