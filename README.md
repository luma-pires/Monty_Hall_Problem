# Título
## Simulando o Problema de Monty Hall

![monty](https://github.com/user-attachments/assets/ff7c90b7-345e-435a-97d4-f1ce3d53e318)

# Introdução
Imagine que você está em um programa de televisão e deve escolher uma entre três portas idênticas. Atrás de uma delas possui um belo prêmio, um carro; e em cada uma das outras, nada (para ser mais exata, existe uma cabra atrás de cada uma das outras portas, o que, convenhamos, pode não ser tããão interessante como o carro). Você escolhe uma das portas. O apresentador, então, abre uma das portas não escolhidas, revelando uma cabra. Ele, então, te faz a seguinte pergunta: *você deseja trocar de porta?* 

*Vale a pena trocar de porta na busca pelo grande prêmio?* Esse dilema é conhecido como o Problema de Monty Hall e este projeto tem como objetivo simular a situação 1 milhão de vezes e obter a resposta de forma experimental. O projeto também demonstra a Lei dos Grandes Números na prática, isto é, mostra que, à medida que o número de simulações aumenta, as probabilidades dos eventos converge para o valor esperado.

# A resposta
*Sim, vale a pena trocar de porta.* Isso porque o apresentador tem uma informação essencial: qual das três portas esconde o grande prêmio. Se você escolher a porta correta (1/3 de chance), ele abrirá qualquer uma das duas restantes para te mostrar a cabra, de forma aleatória. Todavia, não existe aleatoriedade após você escolher a porta errada (2/3 de chance) porque restarão apenas duas das portas: uma com o prêmio (porta A) e outra sem o prêmio (porta B). Assim, ele abrirá, necessariamente, a porta B. Sendo assim, trocar a porta será vantajoso pois a probabilidade de você ter escolhido a porta errada é duas vezes maior do que a de ter escolhido a correta. Em outras palavras, caso troque a porta, você sairá de 1/3 de chances de vitória para 2/3. Conforme o número de simulações aumenta, é possível ver a probabilidade de vitórias convergir para 66,6% (33,3%) caso você (não) troque de porta.

# Outra forma de pensar no problema
Para um melhor entendimento, uma forma alternativa de se pensar no problema é imaginar uma maior quantidade de portas no jogo: 50, por exemplo. Nessa situação, sua probabilidade de ter escolhido a porta correta inicialmente é de 1/50, ou seja, apenas 2%. Agora imagine que o apresentador, que sabe o que cada porta esconde, abra 48 portas sem prêmios (a menos que você seja fã de cabras, é claro), deixando apenas 2 delas ocultas: a sua escolha inicial e mais uma. Dada essa situação, qual a chance de que a única porta que o apresentador deixou de abrir (desconsiderando sua escolha inicial) contenha o grande prêmio? A resposta é 98%, e, nesse cenário, trocar de porta se revela como uma estratégia óbvia para você voltar para casa de carro novo. 

Com base nisso, você trocaria a sua escolha? *Ou confiaria na sua sorte em meio a uma situação em que os números não estão ao seu favor?*

# Referências
MLODINOW, Leonard. O andar do bêbado: como o acaso influencia nossas vidas. Tradução de Diego Alfaro. Rio de Janeiro: Jorge Zahar, 2009.
