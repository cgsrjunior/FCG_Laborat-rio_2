# FCG_Laboratório_2
Este laboratório trabalha com os conceitos de Field Of View e implementa uma Free Camera que pode ser usada para observar três objetos dispostos numa cena

# Ideia
A atividade realiza uma implementação de uma free camera que pode ser usada para a visualização de três cubos numa cena

# Lista de comandos de interação com a camera
A camera pode ser movimentada para frente, esquerda, trás e direita usando as teclas W,A,S,D
Para olhar em outras direções, basta clicar com o botão esquerdo do mouse
Para dar um zoom na camera, basta usar o scroll do mouse

# Lista de comandos de interação com os objetos exibidos na cena
H -> exibe/esconde o texto com as informações sobre as transformações matriciais realizadas pelo programa
X,Y e Z -> controlam os respectivos ângulos de Euler dos eixos X,Y e Z de um dos cubos
Espaço -> Reseta os ângulos
O -> troca a visualização dos objetos para uma projeção ortogonal (esta projeção é a que é carregada com o programa
P -> troca a visualização dos objetos para uma projeção perspectiva

# Como editar e executar o código
Recomendo usar o Codeblocks para compilar esse código (pois a GLFW já se encontra configurada para uso no Codeblocks - caso contrário você terá que procurar um tutorial para configurar a IDE de seu gosto a GLFW). Compile o código e clique em run na IDE