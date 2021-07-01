# Opções de cores

## Descrição

As deficiências para as cores são também chamadas de discromatopsias ou de daltonismo [1]. Estudos estatísticos demonstram que aproximadamente 8% da população masculina e 0,4% da população feminina possuem algum tipo de deficiência em relação à percepção das cores. A maioria dos indivíduos é tricromata, porém, tratando-se dos distúrbios de cores, como o daltonismo, é possível classificá-los em [1]: 
    ⦁ O Tricromatismo: irregularidade nas proporções de vermelho, verde e azul. Existem três tipos de tricomatismo anômalo classificados: Protanomalia: menor sensibilidade ao vermelho; Deuteranomalia: menor sensibilidade ao verde; Tritanomalia: menor sensibilidade às cores na faixa do azul-amarelo. 
    ⦁ O Dicromatismo: devido à ausência de um tipo de cone, e apresenta-se na forma de: Protanopia: ausência de foto pigmentos sensíveis à luz vermelha; Deuteranopia: ausência de foto pigmentos sensíveis à luz verde; Tritanopia: ausência de foto pigmentos sensíveis à luz azul [2]. 
    ⦁ E o Monocromático: dos três cones que existem na retina, apenas um deles é sensível, portanto, aqueles que sofrem com ela verão em intensidades diferentes, mas da mesma cor e não distinguem nenhum outro [3]. 
Para solucionar esse problema, é possível simular como essas pessoas enxergam e com isso solucionar problemas de game design, como os contrastes são vistos, e por consequência se o jogo apresenta um visual claro. A adição dessa opção facilita o  jogador a visualizar os contrastes no mapa.

### Gêneros

Essa prática pode ser utilizada para todos os tipos de jogos.

### Intenção

A intenção com esse sistema é trazer uma opção para jogadores com daltonismo enxergarem com maior facilidade o contraste proposto pelo jogo. Com isso, espera-se uma adaptabilidade maior dos cenários. Essa abordagem envolve uma interface para selecionar qual o tipo de daltonismo o jogador possuí. Isso pode ser feito utilizando uma função da própria alterando a ‘Color Grading’ [5] [6], ou utilizar opções nativas da UE4, porém a função nativa abrange apenas três tipos de daltonismo [4].

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Daltonism/md1.png)


### Código

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Daltonism/md2.png)

### Casos de Uso

Muitos jogos já utilizam essas opções de daltonismo

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Daltonism/md3.png)
(Dead by Daylight - Behaviour Interactive)

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Daltonism/md4.png)
(League of Legends - Riot Games)

### Referências

1. Chromatic sense: types of defects and clinical evaluation test
2. Uma ferramenta adaptativa para facilitar a visualização de imagens para pessoas portadoras de daltonismo 
3. Fuzzy-Based Simulation of Real Color Blindness
4. https://docs.unrealengine.com/en-US/BlueprintAPI/Widget/Accessibility/SetColorVisionDeficiencyType/index.html
5. https://docs.unity3d.com/Manual/PostProcessingOverview.html 
6. https://docs.unrealengine.com/en-US/RenderingAndGraphics/PostProcessEffects/index.html 

### Dados dos testes

Nessa sessão serão colocados como foram as avaliações feitas com o público-alvo, e mostrar os feedbacks recolhidos. As avaliações serão desenvolvidas para metrificar os seguintes dados: Adaptabilidade, Progresso, Dificuldade, Conforto, Instintividade, Eficiência. Os testes serão realizados no primeiro semestre de 2021.

### Demo acessível

Acesse [Daltonism](https://1drv.ms/u/s!AunOkXxY_m_EgdpxBMPCE7YVpW3xlg?e=a2uhiT)

