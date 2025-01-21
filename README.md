# Título
## Simulando o Problema de Monty Hall

![montyyy](https://github.com/user-attachments/assets/ec90fd20-7ec0-4b81-af60-6eed9893857a)

# Sumário

1. [Título](#título)
2. [Introdução](#introdução)
3. [Trocar ou não trocar: eis a questão](#trocar-ou-não-trocar-eis-a-questão)
4. [Outra forma de pensar no problema](#outra-forma-de-pensar-no-problema)
5. [Referências](#referências)

# Introdução
Imagine que você está em um programa de televisão e deve escolher uma entre três portas idênticas. Atrás de uma delas há um belo prêmio, um carro novinho; e em cada uma das outras, nada (para ser mais exata, existe uma cabra atrás de cada uma das outras portas, o que, convenhamos, pode não ser tão interessante como o carro). Você escolhe uma das portas. O apresentador, então, abre uma das portas não escolhidas, revelando uma cabra. Ele, então, te faz a seguinte pergunta: *você deseja trocar de porta?* 

*Vale a pena trocar de porta na busca pelo grande prêmio?* Esse dilema é conhecido como o Problema de Monty Hall e este projeto tem como objetivo simular a situação 10 mil vezes e obter a resposta de forma experimental. O projeto também demonstra a Lei dos Grandes Números na prática, isto é, mostra que, à medida que o número de simulações aumenta, a probabilidade média de cada um dos eventos converge para o valor esperado.

# Trocar ou não trocar: eis a questão
*Sim, vale a pena trocar de porta.* Isso porque o apresentador sabe de algo essencial: qual das três portas esconde o grande prêmio. Se você escolher a porta correta (com 1/3 de chance), ele abrirá aleatoriamente qualquer uma das duas portas restantes para e te mostrará a cabra. Todavia, não existe aleatoriedade após você escolher a porta errada (com 2/3 de chance). Nessa situação, restará uma das portas com o prêmio (porta A) e outra sem o prêmio (porta B). Assim, ele abrirá, necessariamente, a porta B, sem o prêmio. Sendo assim, trocar de porta será vantajoso pois a probabilidade de você ter escolhido inicialmente uma porta com uma cabra é duas vezes maior do que a de ter escolhido a porta com o carro. Dessa forma, caso troque a porta, você sairá de 1/3 de chances de vitória (escolha da porta inicial) para 2/3. É possível verificar isso através de uma simulação: conforme o número de realizações do jogo aumenta (n), a média das probabilidades de vitória converge para 66,6% (33,3%) caso você (não) mude de porta.

![grafico_monty_hall_10mil](https://github.com/user-attachments/assets/380b9836-90a7-474e-812d-fe6176e9a030)

# Outra forma de pensar no problema
Para facilitar o entendimento, uma forma alternativa de se pensar no problema é imaginar uma maior quantidade de portas no jogo: 100, por exemplo. Nessa situação, sua probabilidade de ter escolhido a porta correta inicialmente é de 1/100, ou seja, apenas 1%. Agora imagine que o apresentador, que sabe o que cada porta esconde, abra 98 portas sem prêmios (a menos que você seja fã de cabras, é claro), deixando apenas 2 delas ocultas: a sua escolha inicial (porta A) e mais uma (porta B). Dada essa situação, qual a chance de que a única porta que o apresentador deixou de abrir (desconsiderando sua escolha inicial), isto é, a porta B, contenha o grande prêmio? A resposta é 99%. Nesse cenário, trocar de porta torna-se a escolha mais óbvia para maximizar suas chances de voltar para casa de carro novo. 

E aí? Você trocaria a sua escolha? *Ou se agarraria à sorte do primeiro palpite, torcendo para não acabar com uma cabra?*

# Referências
MLODINOW, Leonard. O andar do bêbado: como o acaso influencia nossas vidas. Tradução de Diego Alfaro. Rio de Janeiro: Jorge Zahar, 2009.
