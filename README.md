# Labirinto
Jogo de Programação 2

Jogar o jogo é simples; você é o ponto vermelho, e seu objetivo é se deslocar até o ponto azul.

Para mover o ponto vermelho, você pode usar as teclas direcionais (que farão com que ele se mova numa velocidade normal, se não um pouco lenta) ou as teclas A D W S (farão com que o ponto se mova muito mais rapidamente), que representam as direções esquerda, direita, cima e baixo, respectivamente.
Toda vez que o ponto vermelho encostar no azul, o ponto azul vai mudar de localização. Isso se repetirá infinitamente.

Se o ponto vermelho encostar em uma parede (linha branca), ele irá voltar para sua posição inicial. Se isso acontecer 3 vezes, o jogo acaba (a janela do pygame fecha).

Deveria haver uma música de fundo, mas eu não consegui fazer o upload do arquivo no GitHub. O arquivo de música prcisa estar no mesmo diretório que o arquivo de Python para funcionar, e precisa ser um arquivo .wav para que o Pygame possa lê-lo. Então, se você quiser adicionar uma música, você primeiro deve adicionar um arquivo .wav à pasta ‘Labirinto’ (ou onde quer que seja que você mantem o arquivo do jogo). Depois, procure pygame.mixer.music.load() no código do arquivo .py, e coloque o nome do arquivo dentro dos parenteses. Lembre-se de incluir a extensão de arquivo junta ao nome, e de colocá-lo entre aspas.

Ou, se você não quiser nenhuma música, você pode apagar as linhas de código:


if music == False:

    music = True
		
    pygame.mixer.music.load()
		
    pygame.mixer.music.play(-1)
		

Para ter mais facilidade em achar os códigos, você pode apertar Ctrl + F e digitar ‘mixer’.
