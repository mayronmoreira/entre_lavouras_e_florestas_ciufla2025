## 🌲 Dinâmica 2 — Qual floresta cortar?

🎯 *Objetivo:*  
Escolher 3 talhões para corte, equilibrando lucro e impacto ambiental.

## 📋 Cenário

Você é o gestor de uma área florestal com 6 talhões disponíveis para corte. Cada talhão possui diferentes volumes de madeira, lucros potenciais e níveis de risco ambiental associados ao seu corte. Seu desafio é escolher 3 talhões para corte, buscando um equilíbrio entre maximizar o lucro e minimizar o impacto ambiental.

Dados sugeridos (6 talhões):

| Talhão | Volume (m³) | Lucro (R$ mil) | Risco ambiental (0–10) |
|--------|-------------|----------------|------------------------|
| 1      | 90          | 45             | 8                      |
| 2      | 120         | 55             | 9                      |
| 3      | 70          | 35             | 3                      |
| 4      | 110         | 50             | 5                      |
| 5      | 100         | 47             | 6                      |
| 6      | 80          | 38             | 2                      |

Função ponderada sugerida:

Z = 0,7 × (Lucro) − 0,3 × (Risco)

### 💬 Discussão:

1. Encontre a combinação de 3 talhões que maximize Z.
2. Como definir o "peso" do impacto ambiental? Quais critérios usar?
3. O que muda se o risco médio permitido for ≤ 5?