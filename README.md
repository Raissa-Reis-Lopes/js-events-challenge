Desafios porpostos na aula de javascript da Alpha EdTech sobre *"Manipulação avançada de eventos"*

Descrição do exercício:
Desafio ! Lógica difícil ! Trabalhoso !

Faça uma página que tem uma div com borda preta e dentro dela uma div pequena colorida:

![image](https://github.com/Raissa-Reis-Lopes/js-events-challenge/assets/105091977/3571ee13-db10-4522-953a-cc4c25d2f27d)
 

Quando a div pequena é clicada, ela troca de cor, digamos que ela ficou “ativa”.

Enquanto ela está ativa, caso você aperte uma seta direcional do teclado (esquerda, baixo, direta, cima), a div pequena se move na direção que você apertou (pode ser um passo de ~10px, não importa exatamente).

Se você estiver segurando Shift quando apertar numa seta, o passo deve ser maior que o normal (~100px).

Mas caso um passo da div pequena a faria sair (total ou parcialmente) da borda da div externa, o passo não é dado em todo seu deslocamento, mas somente até a borda.

Quando você clica fora da div pequena, ela deixa de estar “ativa” e volta à cor original.

Enquanto ela não está ativa, apertar as setas do teclado não causa movimentação.

Sugestão: para saber a posição e tamanho de um elemento, pesquise sobre as propriedades offsetLeft, offsetTop, clientWidth, clientHeight.

Bônus: depois de fazer o exercício como descrito, faça ele funcionar com 5 divs pequenas independentes sem adicionar nenhuma nova função no seu código. Sugestão: activeMovable = this dentro de um ouvinte de evento de clique, onde activeMovable é uma variável global.



Versão 2 do exercício:

Refaça o exercício anterior (versão básica, não bônus), mas agora a div pequena é movimentada clicando e arrastando com o mouse, não mais com as setas do teclado.

Ou seja, ao clicar e segurar, a div pequena fica “ativa” (muda de cor) e passa a seguir a posição do mouse.

Ao soltar o mouse, ela fica “inativa” de novo, ou seja, volta à cor original e fica parada onde o mouse soltou.

Se, ao arrastar a div pequena, o mouse sair da borda da div externa, a div pequena não deve continuar, ele deve ficar “bloqueada” na parede.

Mas a div pequena ainda está “ativa” enquanto o mouse estiver sendo segurado, ou seja, se você continuar segurando o mouse e voltar a posicioná-lo dentro das bordas da div externa, a div pequena imediatamente volta a acompanhar a posição do mouse.

Sugestão: quando “mousedown”, registre a posição do mouse. Quando “mousemove”, calcule o deslocamento do mouse e aplique na div. Já quando o mouse sair para fora do container, pense aí !

Bônus: depois de fazer o exercício como descrito, faça ele funcionar com 5 divs pequenas independentes sem adicionar nenhuma nova função no seu código.
