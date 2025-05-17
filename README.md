PROJETO REALIZADO DURANTE A IMERSÃO ALURA DE GOOGLE GEMINI! 

Este projeto surge da dificuldade de encontrar a trilha sonora ideal para vídeos (VTs) de forma rápida e eficiente. Os criadores de conteúdo frequentemente enfrentam os seguintes problemas:

Sobrecarga de Opções: Plataformas de streaming musical oferecem milhões de faixas, tornando a escolha da música perfeita para um vídeo uma tarefa demorada e exaustiva.
Falta de Inspiração: A busca por músicas adequadas pode ser um processo criativamente desafiador, especialmente quando se tenta evocar um sentimento ou complementar um tema específico do vídeo.
Dificuldade em Conectar Música e Conteúdo: Encontrar músicas que realmente ressoem com a narrativa visual e emocional de um vídeo requer tempo e um certo grau de conhecimento musical.
Necessidade de Sugestões Personalizadas: Ferramentas genéricas de busca musical podem não levar em consideração o contexto específico e as nuances da descrição de um vídeo.
Em essência, este projeto resolve a ineficiência e a dificuldade criativa no processo de seleção musical para vídeos, oferecendo uma solução inteligente e personalizada.

Ao analisar a descrição textual do vídeo utilizando a inteligência artificial do Google Gemini, o programa é capaz de identificar os gêneros musicais mais adequados para complementar o seu conteúdo. Em seguida, através da integração com a vasta biblioteca do Spotify, o programa fornece sugestões concretas de músicas e playlists prontas para uso, economizando tempo e oferecendo novas ideias aos criadores de conteúdo.

Além disso, a funcionalidade de refinamento permite ao usuário explorar ainda mais as sugestões por gênero, aprofundando a busca e descobrindo opções que talvez não fossem encontradas por meio de uma pesquisa manual tradicional. A exportação dos resultados em um arquivo TXT facilita o acesso e o compartilhamento das sugestões encontradas.

cOMO INICIALIZAR O PROGRAMA!
Para inicializar e utilizar o programa de sugestão musical para vídeos, siga estes passos:

Abrir o Ambiente Colab: Acesse o Google Colaboratory (Colab) através do seu navegador web (https://colab.research.google.com/).
Abrir o Notebook do Projeto: Carregue o arquivo .ipynb do projeto no Colab. Você pode fazer isso através de Arquivo (File) > Abrir notebook (Open notebook) e selecionando o arquivo do seu computador ou do Google Drive.
Executar as Células de Código: Execute as células de código em sequência, de cima para baixo. Para executar uma célula, você pode clicar no ícone de "play" (▶️) ao lado da célula ou pressionar Shift + Enter.
Célula de Configuração das APIs: Certifique-se de que esta célula seja executada sem erros. Ela configura as conexões com as APIs do Gemini e do Spotify, utilizando suas respectivas chaves de API (que devem estar configuradas como variáveis de ambiente).
Células de Funções: Execute as células que definem as funções do programa (buscar_playlists_spotify, analisar_vt_e_sugerir_musica_com_spotify_e_playlists, formatar_resultado_com_playlists, buscar_mais_musicas_relacionadas, buscar_mais_playlists, buscar_artistas_relacionados, exportar_resultados).
Célula do Formulário Principal: Esta célula contém o campo para inserir a descrição do seu vídeo e o menu interativo.
Inserir a Descrição do Vídeo: No formulário que aparece após executar a célula principal, digite uma descrição detalhada do seu vídeo no campo de texto fornecido. Seja o mais específico possível sobre o tema, o tom, a emoção que você deseja evocar e qualquer outro detalhe relevante.
Executar a Análise Inicial: Após inserir a descrição, execute a célula do formulário principal (clicando no ícone de "play" ao lado dela ou pressionando Shift + Enter). O programa utilizará o Gemini para analisar a descrição e exibirá as sugestões iniciais de gêneros, músicas e playlists do Spotify.
Interagir com o Menu: Um menu de opções será exibido abaixo dos resultados iniciais:
Opção 1: Refinar busca por gênero: Se você deseja explorar mais sugestões com base em um dos gêneros sugeridos, digite 1 e siga as instruções.
Opção 2: Sair e exportar resultados (TXT): Quando estiver satisfeito com as sugestões ou quiser salvar os resultados obtidos, digite 2. O programa fará o download automático de um arquivo de texto (vt_music_suggestions.txt) contendo todas as sugestões (iniciais e refinadas) para o seu computador e encerrará o programa.
Seguindo estes passos, você poderá utilizar o programa para obter sugestões musicais personalizadas para seus vídeos de maneira fácil e intuitiva.
