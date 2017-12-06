# Labirinto
Jogo de Programação 2

Jogar o jogo é simples; você é o ponto vermelho, e seu objetivo é se deslocar até o ponto azul.

Para mover o ponto vermelho, você pode usar as teclas direcionais (que farão com que ele se mova numa velocidade normal, se não um pouco lenta) ou as teclas A D W S (farão com que o ponto se mova muito mais rapidamente), que representam as direções esquerda, direita, cima e baixo, respectivamente.
Toda vez que o ponto vermelho encostar no azul, o ponto azul vai mudar de localização. Isso se repetirá infinitamente.

Se o ponto vermelho encostar em uma parede (linha branca), ele irá voltar para sua posição inicial. Se isso acontecer 3 vezes, o jogo acaba (a janela do pygame fecha).

Há uma música de fundo. Se você quiser mudar a música, adicione um arquivo .wav à pasta ‘Labirinto’, então procure pygame.mixer.music.load(‘Deja Vu.wav’) no código, e substitua ‘Deja Vu.wav’ com o arquivo .wav que você adicionou à pasta (lembre-se de colocar o arquivo entre parênteses e incluir a extensão).

Ou, se você não quiser nenhuma música, você pode apagar as linhas de código:


if music == False:

    music = True
		
    pygame.mixer.music.load(‘Deja Vu.wav’)
		
    pygame.mixer.music.play(-1)
		

Para ter mais facilidade em achar os códigos, você pode apertar Ctrl + F e digitar ‘mixer’.
