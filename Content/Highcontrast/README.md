# Exibição em alto contraste

## Descrição

Uma opção na qual o ambiente fica com cores neutras, e se utiliza cores com diferentes contrastes para o jogador, inimigos e itens coletáveis. Isso permite com que jogadores com baixa visão possam ter melhor aproveitamento do jogo. O uso de combinações de cores adequadas para pessoas com baixa visão devem ter altos valores de contraste [1]. A combinação de cores comumente usada é preto-branco, vermelho-branco ou azul-branco. Existem deficiências visuais comuns que resultam especificamente em uma perda de sensibilidade ao contraste e outras, como daltonismo, que também podem ser afetados pelo contraste [2].

Com isso, as taxas de detecção aumentaram com o aumento do contraste, variando de desempenho ruim em baixo contraste a desempenho quase perfeito em valores de alto contraste [3]. Para desenvolver essa prática é necessário criar parametrização para a cor do objeto, na Unreal 4 ela pode ser colocada dentro dos nós de “Material”, já na Unity é possível o mesmo resultado utilizando o “Shader Graph”, sendo possível alterar as propriedades programaticamente.

### Gêneros

Para esta prática, todos os gêneros se enquadram. Com isso, pode ser observado diferentes comportamentos para direcionar o foco do jogador. Tendo em vista o caso de uso do Last of Us 2, no qual o jogo destaca o jogador e aliados na cor azul, objetos coletáveis na cor amarela, e inimigos na cor vermelha. Podendo trazer esse padrão para qualquer jogo, incluindo puzzles, onde é possível aumentar o contraste dos objetos que serão utilizados.

### Intenção

A intenção com esse sistema é trazer uma maior adaptabilidade de jogos para pessoas com baixa visão. Com isso, espera-se que os jogos tragam esse elemento para uma maior inclusão das pessoas com deficiência visual. Essa abordagem envolve a mudança de texturas do jogo. Isso pode ser feito utilizando um parâmetro que possa alterar a coloração das texturas.

### Código

A imagem mostra como fazer a multiplicação da cor de contraste e a cor do material.

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Highcontrast/md1.png)

A imagem mostra alterar a parametrização da cor de contraste, de maneira que possa ser alterada nas configurações de jogo.

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Highcontrast/md2.png)

A demonstra o resultado na aplicação em funcionamento.

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Highcontrast/md3.png)

### Casos de Uso

![plot](https://github.com/LeoGarcez/accessible-features/blob/main/Content/Highcontrast/md4.png)

O Last of Us 2 utiliza um sistema de alto contraste, como pode ser observado na imagem. Mais informações no link https://www.youtube.com/watch?v=fBOOIY71PRU 

### Referências

1.	Computer games for children with visual impairments
2.	Mobile games interaction design for people with visual impairment using participatory design approach 
3.	Improvement of visual contrast detection by a simultaneous sound
4.	Comparison of Unity and Unreal Engine
5.	https://docs.unrealengine.com/en-US/Engine/Rendering/Materials/index.html 
6.	https://docs.unity3d.com/ScriptReference/Material.html
7.	https://unity.com/pt/shader-graph 

### Dados dos testes

Nessa sessão serão colocados como foram as avaliações feitas com o público-alvo, e mostrar os feedbacks recolhidos. As avaliações serão desenvolvidas para metrificar os seguintes dados: Adaptabilidade, Progresso, Dificuldade, Conforto, Instintividade, Eficiência. Os testes serão realizados no primeiro semestre de 2021.

### Demo acessível

Acesse [Highcontrast](https://1drv.ms/u/s!AunOkXxY_m_EgdpxBMPCE7YVpW3xlg?e=a2uhiT)

