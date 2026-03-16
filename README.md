# Exercicio-CompDistribuida



Caio Victor - 2010224
Brenno Damiany - 2315088
Diego Queiroz - 2315108

Exercicio 1.1

O que fazer: 
Deduza a fórmula matemática que calcula a disponibilidade de um serviço replicado em múltiplos servidores
A fórmula deve ser definida em termos dos seguintes parâmetros:
	n – número de servidores (n > 0)
	k – número mínimo de servidores disponíveis necessário para o serviço ser acessado de forma consistente (0 < k ≤ n)
	p – probabilidade de cada servidor estar disponível em um dado instante (0 ≤ p ≤ 1)
Para facilitar, tente primeiro derivar as fórmulas para os casos extremos, onde 
k = 1 (operação de consulta) e k = n (operação de atualização) 


Exercicio 1.2

O que fazer: 
1. Cálculo analítico
Implemente a(s) fórmula(s) derivada(s) no Exercício 1.1 na sua linguagem de preferência.
Mostre como a disponibilidade do serviço é afetada para diferentes valores de n, k e p.
Utilize casos específicos (k = 1, n/2, n) como base de comparação.
Organize os resultados em uma tabela ou planilha, e visualize-os em gráficos 2D.
2. Simulador estocástico
Implemente um simulador que, para cada valor de n, k e p, gere um grande número de "rodadas".
Em cada rodada, decida se cada servidor está disponível (gere um número aleatório entre 0 e 1 e verifique se o número gerado é igual ou menor que p) ou não, conte quantos servidores estão disponíveis e verifique se o serviço se manteve operacional (ou seja, se ao menos k estão disponíveis).
Calcule a frequência experimental de disponibilidade (proporção de rodadas bem-sucedidas) e compare-a com o valor obtido pela fórmula.
Apresente os valores analíticos e experimentais lado a lado em uma tabela ou planilha, e visualize-os em gráficos 2D para evidenciar a aproximação ou divergência entre teoria e prática.
