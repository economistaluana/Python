# 📊 Projeto de Econometria com Python
Olá, pessoal! Tudo bem? 👋

Este projeto foi desenvolvido durante a aula de Econometria do curso Econometria Day. Aqui, eu modelei um conjunto de dados para analisar a influência da educação, experiência, gênero e cor da pele sobre os salários, utilizando uma amostra de 526 indivíduos. Vamos juntos explorar os resultados? 🚀

### 📝 Definição das Variáveis:
Educação (educ): Anos de escolaridade da pessoa.
Experiência (exper): Anos de experiência profissional.
Gênero (female): Se a pessoa é do gênero feminino (1 = sim, 0 = não).
Cor da pele (nonwhite): Se a pessoa se identifica como não branca (1 = sim, 0 = não).
Salário (wage): Salário (em dólares)

![image](https://github.com/user-attachments/assets/bee2e77e-be98-4f87-80cd-609b3bb1795a)


### 🔍 Testes T dos Coeficientes:

![image](https://github.com/user-attachments/assets/97efb6b3-5979-4c18-baff-1c0bbabf6c1d)


🧠 Os coeficientes são estatisticamente significantes a 1%, exceto nonwhite. Isso significa que não podemos afirmar algo sobre esse coeficiente, e não que ele não infere no salário. 

### 📈 Novo Modelo (Sem a variável nonwhite):

![image](https://github.com/user-attachments/assets/bb5a5d9c-c310-40de-b626-d26fb39a9a9f)


𝑤𝑎𝑔𝑒=−1,73 +0,60∗𝑒𝑑𝑢𝑐 +0,06∗𝑒𝑥𝑝𝑒𝑟 −2,15∗𝑓𝑒𝑚𝑎𝑙𝑒 +𝑒

Cada ano de educação está associado a um aumento de 0,60 dólares de salário.
Cada ano de experiência está associado a um aumento de 0,06 dólares de salário.
Ser mulher está associado a 2,15 dólares a menos de salário.

### Cenários hipotéticos

#### Quanto uma uma mulher ganharia de salário caso tivesse 15 anos de educação e 10 anos de experiência comparado a um homem com o mesmo tempo de educação e experiência?

𝑤𝑎𝑔𝑒_mulher=−1,73 +0,60∗15 +0,06∗10 −2,51∗1 
-1,90 + 9 + 0,6 - 2,51
salário que tende a receber é de = 5,19

wage_homem= −1,71 +0,60∗15 +0,06∗10 −2,51∗0
-1,90 + 9 + 0,6 
salário que tende a receber é de = 7,7

Mulheres com a mesma escolaridade e experiência recebem, em média, um salário aproximadamente 32,5% menor do que dos homens, para esta amostra.

### 📊 R² (Coeficiente de Determinação):

![image](https://github.com/user-attachments/assets/3e88dc3f-b188-426e-a5a2-152e368cedd0)

30% dos salários podem ser explicados pela escolaridade, experiência e gênero.


