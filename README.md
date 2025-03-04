# Projeto-Jogo  

## Caça a Matemática - Jogo Digital
  
Este é o jogo digital do trabalho "Projeto Jogo" junto com a turma de pedagogia.  
  
Para jogar, basta [clicar aqui.](https://felipemacchiz.github.io/Projeto-Jogo/)  
  
### Controles  
  
Jogador 1  
   - Andar para frente: [D]  
   - Andar para trás: [A]  
   - Pular: [W]  
   - Ação: [S]  
  
Jogador 2  
   - Andar para frente:	:arrow_right:
   - Andar para trás: :arrow_left: 
   - Pular: :arrow_up: 
   - Ação: :arrow_down:  
   
> Apertando duas vezes o botão "Pular" você consegue dar dois pulos! ***(Dica: para dar pulos maiores, pule e espere o jogador começar a cair para pular de novo para dar pulos maiores)***  
  
### Seleção de jogadores  
  
Você consegue escolher o número de jogadores no menu principal do jogo.  
Após isso, cada jogador poderá escolher seu nome e seu personagem para jogar!  
  
### Fases  
  
Cada fase tem missões e inimigos diferentes. O objetivo é recolher 4 chaves para libertar o Lobo no final da fase.  
  
#### - Fase 1: A Floresta  
O objetivo dessa fase é fazer as árvores crescerem, para isso, aperte o botão de "Ação" quando estiver perto dessas árvores. Cada árvore dará uma chave. Se estiver jogando com 2 jogadores, cada um deverá ter 2 chaves para passar.  
O obstáculo da fase são as armadilhas, o jogador que cair nela irá para o começo da fase, mas não perde as chaves.  
  
#### - Fase 2: A Praia  
O objetivo dessa fase é achar as placas de madeira e responder a pergunta, se acertarem, os dois ganham uma chave. Ao todo são 4 plaquinhas que os jogadores deverão encontrar.  
Os obstaculos dessa fase são os Krabs, os caranguejos, e ao ser pego por eles, você volta para o começo da fase.  
  
#### - Fase 3: A Cidade Tóxica  
O objetivo dessa fase é coletar todos os lixos que encontrar, cada lixo dará uma chave para salvar o lobo.  
Os obstáculos dessa fase são as nuvens tóxicas, e você deve evitá-los para não voltar para o começo da fase.  
  
#### - Fase 4: O Parque  
O objetivo dessa fase é recolher todos os lixos jogados pelo parque. Cada lixo recolhido dá uma chave para salvar o lobo.  
Os obstáculos dessa fase são os Krabs.  

## Produção 
  
O jogo foi feito na plataforma [Godot Engine](https://godotengine.org/), que tem uma linguagem própria chamada GDScript.  
As telas no Godot são feitas com conjuntos de _cenas_, e essas cenas são conjuntos de _nós_, que podem ser uma imagem, um texto, um boneco, uma caixa de colisão, um ponto que marca uma posição, etc.; e é com esse conjunto de nós que fazemos os personagens, o cenário, os objetos para o jogador pegar, inimigos; ou seja, tudo que aparece na tela é um nó. E separamos os nós em cenas para nos organizar melhor.  
  
### - Códigos  
  
Os códigos foram feitos em [GDScript](https://docs.godotengine.org/pt_BR/stable/getting_started/scripting/gdscript/gdscript_basics.html), uma linguagem de alto nível, de tipagem dinâmica com uma sintaxe semelhante a linguagem [Python](https://www.python.org/).  
  
Foi utilizado os códigos, por exemplo, para movimentação do jogador, transição de tela, configurações de número de jogadores, escolha do personagem, verificar o nível e se os jogadores atingiram os objetivos.
