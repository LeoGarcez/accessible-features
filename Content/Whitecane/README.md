# Bengala

## Descrição

 Um sistema no qual o personagem usa uma simulação de uma bengala para identificar a posição dos objetos, podendo ser utilizados sons e vibração para identificação do espaço em que o jogador está se locomovendo, permitindo uma percepção espacial precisa o suficiente para navegar em ambientes tridimensionais.
Para solucionar esse problema são propostas duas soluções: Raycast e detecção de colisões. As funções de Raycast retornam os objetos colididos por uma reta dada uma origem, direção e distância [1] [2] . Na Unity, o script [8] tem como parâmetros a distância máxima para a emissão de raios, o ângulo de varredura em graus, o número de raios a serem lançados e o número de ações por segundo. Já na Unreal 4, ele ganha o nome de LineTrace [6], e tem como parâmetros a posição inicial, posição final, os canais, opções para traçar a linha quando é uma versão de debug, e opções para ignorar o emissor.
Já a detecção de colisão é gerada de acordo com a sobreposição de dois objetos que podem colidir [4]. A Unity utiliza a classe “Collider” [9] , enquanto a Unreal 4 utiliza  a classe “Collision” [7], e ambas podem suportar uma função de personalização do corpo em colisão, o que ajuda os atores a colidir com mais precisão. Para a detecção de colisão, foi desenvolvida uma simulação de uma bengala em movimento, que possui três colisores, na ponta e nos cantos inferiores direito e esquerdo. Essa demonstração pode ser observada na Demo Acessível (Redirecionar).

### Gêneros

Para os gêneros que não possuem lutas ativas como: Casual, Educacional, Plataforma, Puzzle, Role Playing (RPG) e Simuladores a “Bengala” funciona para posicionar o jogador em relação ao mundo, por ser um objeto no qual ele tem familiaridade, auxiliaria na integração do jogador para com o mundo.
Já em jogos que possuem ação, como Ação e Aventura, RPGs de Ação, Plataforma, essa prática, além de posicionar o jogador, funcionaria como ferramenta de combate, aproveitando da usabilidade para golpear inimigos. 

### Intenção

A intenção com esse sistema é trazer uma ferramenta comumente utilizada por pessoas com deficiência visual para dentro do jogo. Com isso, espera-se que a adaptabilidade seja mais rápida e de forma mais dinâmica. Essa abordagem envolve o fornecimento de efeitos sonoros e/ou vibrações para todos os objetos que o jogador possa se deparar. Isso pode ser feito utilizando um receptor de informações que parte do jogador e dispoẽ de um sensor a partir de uma determinada distância.
Com essa colisão espera-se retornar sons de diferentes materiais, por exemplo, sons metálicos para quando colidir com ferros. Juntamente com os diferentes sons através dos materiais distintos, é possível também utilizar o som espacial para quando os colisores laterais forem atingidos, emitir sons em apenas partes específicas do fone de ouvido, o que facilita na identificação do contexto geral dentro do jogo.

### Código

A imagem representa o código em Blueprints feito na Unreal 4.

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Whitecane/md1.png)

A imagem mostra o cálculo específico para tocar sons mais altos conforme a distância diminui.

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Whitecane/md2.png)

A imagem representa o código em Blueprints feito na Unreal 4, onde são detectadas as colisões.

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Whitecane/md3.png)

A imagem mostra o exemplo da bengala em funcionamento.

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Whitecane/md4.png)


### Casos de Uso

Como não foram encontrados casos de uso existentes para essa prática, eles serão desenvolvidos ao longo da realização do projeto.

### Referências

1.	An Arduino-based device for visually impaired people to play videogames 
2.	Using the Unity Game Engine to Develop SARGE: A Case Study
3.	Desenvolvimento rápido de ambientes para realidade virtual em Unity utilizando PhotoSphere e CubeMap
4.	Research and Development of Virtual Reality Game Based on Unreal Engine 4
5.	Comparison of Unity and Unreal Engine
6.	https://docs.unrealengine.com/en-US/BlueprintAPI/Collision/LineTraceByChannel/index.html 
7.	https://docs.unrealengine.com/en-US/Engine/Physics/Collision/Overview/index.html 
8.	https://docs.unity3d.com/ScriptReference/Physics.Raycast.html 
9.	https://docs.unity3d.com/ScriptReference/Collider.html

### Dados dos testes

Nessa sessão serão colocados como foram as avaliações feitas com o público-alvo, e mostrar os feedbacks recolhidos. As avaliações serão desenvolvidas para metrificar os seguintes dados: Adaptabilidade, Progresso, Dificuldade, Conforto, Instintividade, Eficiência. Os testes serão realizados no primeiro semestre de 2021.

### Demo acessível

Acesse [Bengala](https://1drv.ms/u/s!AunOkXxY_m_EgdpxBMPCE7YVpW3xlg?e=a2uhiT)

