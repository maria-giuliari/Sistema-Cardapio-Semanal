# Sistema-Cardapio-Semanal
## Aplicação Web para Planejamento Semanal de Refeições 

### PAC – Projeto de Aprendizagem Colaborativa Extensionista do Curso de Engenharia de Software da Católica de Santa Catarina

Aluna: Maria Alice Teles Giuliari 

Integrantes do Grupo: Alexandre Sebastian Basso Muller, Gabriel Henrique Ferreira  e Mariele Vieira da Silva 

Professor Orientador: Diogo Vinícius Winck 

---
### Descrição Geral: 

O projeto propõe uma aplicação web voltada ao planejamento alimentar inteligente, com foco em auxiliar usuários na organização de refeições, redução de desperdício e otimização do tempo no dia a dia. 

A plataforma permite que os usuários: 

* Informem seus ingredientes disponíveis, preferências e restrições.
* Recebam sugestões de cardápios semanais personalizados.
* Visualizem receitas simples e rápidas para o dia a dia.
* Organizem suas refeições com base no orçamento disponível.
* Evitem compras desnecessárias e desperdício de alimentos.

O sistema busca facilitar o processo de decisão sobre o que cozinhar, promovendo maior organização, economia e praticidade, com uma interface acessível e adaptada ao cotidiano dos usuários. 

---
### Objetivo da Aplicação: 

Permitir que o usuário organize sua alimentação semanal de forma automatizada, otimizando o uso de ingredientes e respeitando seus limites de tempo e orçamento. 
A aplicação visa: 
* Montar automaticamente cardápios semanais, com base em: 
     * Tempo disponível.
     * Orçamento.
     * Nível de esforço necessário. 
     * Ingredientes disponíveis em casa.
* Reduzir desperdício de alimentos, priorizado o reaproveitamento de ingredientes.
* Evitar repetição excessiva de refeições ao longo da semana.
* Tornar a ida ao mercado mais organizada com a geração automática de listas de compras.
* Oferecer sugestões adicionais de refeições utilizando IA, quando solicitado pelo usuário. 

---
### Funcionalidades Principais: 

1. Entrada de Dados e Preferências do Usuário: 
O usuário informa suas condições e preferências por meio de um formulário, incluindo: 
* **Perfil de Custo:** escolha entre níveis (econômico, moderado ou caro), utilizado para filtrar as receitas compatíveis com o orçamento.
* **Tempo Disponível:** tempo médio para preparo de cada refeição.
* **Nível de Esforço:** escala de 1 a 5, representando a complexidade do preparo (onde 1 é algo muito simples, e 5 exige técnicas mais elaboradas).
* **Inventário Local:** lista de ingredientes já disponíveis em casa, utilizada para priorização e redução de desperdício.

2. Geração do Cardápio Semanal: 
O sistema processa as informações informadas e gera automaticamente um cardápio semanal, utilizando uma lógica baseada em regras e heurísticas. 
Esta etapa contempla:  
* **Seleção Inteligente:** filtragem de receitas compatíveis com os critérios de tempo, custo e esforço definidos.
* **Diversidade de Refeições:** tentativa de evitar repetição de pratos ao longo da semana.
* **Aproveitamento de Ingredientes:** priorização de receitas que utilizem itens já disponíveis no inventário do usuário.
* **Logística de Sobras (Marmitas):** opção de reutilizar o jantar como almoço do dia seguinte, facilitando a rotina.
* **Troca Dinâmica:** possibilidade de substituir uma refeição sugerida por outra opção válida dentro dos mesmos critérios. 

3. Lista de Compras Automática: 
Após a definição do cardápio semanal: 
* O sistema consolida todos os itens necessários para as receitas selecionadas.
* **Subtração de Inventário:** ingredientes que o usuário informou já ter em casa são removidos da lista.
* **Agrupamento:** organiza os itens por categoria para facilitar a experiência de compra no supermercado. 
