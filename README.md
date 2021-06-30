Projeto Íris
Íris é uma bot em inglês, espanhol e português criada e mantida atualizada pelo Lucas R. - KillovSky para o grupo "Legião Z", ela tem mais de 200 comandos e atualização frequente com correções e novidades.

Outros idiomas
if you want a English tutorial, open this English Tutorial, si quieres en español, abre esta Tutorial Español Para deixar sua bot completamente em outro idioma, abra a configuração de linguagem aqui e troque o "pt" para "en" que é inglês ou "es" para espanhol, não há outros idiomas além destes, não agora.

Nota Pessoal
Esse software funciona sob a licença MIT, sendo proibido a retirada de créditos, e lembre-se, eu gasto MUITO tempo ajudando todos que tem dúvidas e melhorando a BOT, mas sem ganhar nada nisso, por favor, não remova os créditos. Se você ver alguém roubando ou que tenha roubado, mostre a verdade, diga a ela que isso é plagio, esse é o único pedido que tenho.

Erros & Bugs
Se notar erros leia a Discussions, se ela não resolver, fale comigo pelos meios no final da pagina ou reporte no Issues, e claro, se certifique de ter instalado chrome e de ler TUDO que estiver escrito abaixo. Baixe Chrome no Windows por aqui, no linux use os comandos abaixo.

> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
> sudo apt install ./google-chrome-stable_current_amd64.deb
Funções (+200)
Função	Contém
Rodar WA-Automate/Functions dentro do WhatsApp	✅
Administrar Grupos	✅
Apostar/Cassino/Outros Jogos	✅
Anti Porno & Imagem +18/Link de Chat	✅
Ataques SMS/CALL/EMAIL	✅
Bem Vindo/Adeus/Anti-Fake/Blacklist	✅
Bloquear/Desbloquear/Rastrear pessoas	✅
Buscar Anime/Letra de Música/Twitter/Instagram	✅
Mandar mensagens a outros grupos	✅
Conversar por texto/voz Sim-Simi/Local (ilimitado)	✅
Deletar Mensagens do BOT	✅
Downloads (Redes-Sociais e YouTube)	✅
Falar 51 idiomas/Tradutor	✅
Geração de Textos/Diário	✅
Google/Google Play/Pinterest	✅
Informações de Grupo/Perfil	✅
Marcar todos/Remover Todos	✅
Memes/Fazer Memes	✅
Nasa, Brainly, Wikipédia	✅
Pausar/Sair de Tudo/Transmissão/Apagar Tudo	✅
Pesquisa Fotos/Dados/Covid	✅
Printar Tela/Sites	✅
Sticker de GIF/Sem-Fundo/Link/Palavras	✅
Uploads de Fotos	✅
Usar CMD/Terminal pelo WhatsApp	✅
XP/Ranking/Level/Votações	✅
Outras	✅
Requisitos
Dois números no WhatsApp, um para o dono e outro para a BOT.
NodeJS - Recomendo a LTS.
Git - Para as Unix-Tools - Cuidado.
FFmpeg - Para conversões.
Libwebp - Ajuda no de cima e outras coisas.
Para um tutorial de instalação do FFmpeg no Windows 7/8, veja WikiHow, no caso de Windows 10 veja a SoundArtifacts.
Para instalar o LibWebP siga os mesmos passos, mas mudando o nome da pasta para LibWebP em vez de FFmpeg.
Para a instalação de tudo acima no Linux, você pode usar o comando abaixo:

> sudo apt install nodejs git ffmpeg -y
Caso você obtenha erros com a versão do node no repositório de seu Linux, use o Node Source, lembre-se de usar a LTS (14).

Instalação
Você precisa ter esse repositório, é simples, rode os comandos abaixo, em caso de erros, rode como sudo/administrador ou veja os Tutoriais.

> git clone https://github.com/KillovSky/iris.git
> cd iris
> npm i
Mudanças OBRIGATÓRIAS
EDITE as API's encontradas em:

Linguagem
Dono
DDI
Prefix
API 1 - API-Flash
API 2 - RemoveBG
API 3 - WallHaven
API 4 - Deep-AI
Limite de Grupos
Limite de Membros
Sticker-Autor
Sticker-Pack
User-Agent
Tempo de Jogo
Anti-Flood
Max-Size
Win-Time
Elas são referentes aos sites RemoveBG, API-Flash, WallHaven & Deep-AI.
A DDI e Linguagem são necessárias apenas se você for de fora do Brasil, as linguagens disponiveis são "en" de inglês, "pt" de português e "es" de espanhol e afetam todos os diálogos e o akinator.
Você pode inserir dois ou mais números de dono, se não quiser apenas deixe o segundo como está, o tempo de jogo deve ser inserido em MINUTOS, ele limitará o tempo para cada jogatina, o Anti-Flood deverá ser em SEGUNDOS e limita os comandos e a User-Agent é opcional, Max-Size é para Downloads, coloque entre 1 a 64 (Sugiro 16) e a Win-Time é o tempo de ganho de XP para cada mensagem.
Iniciar
Após a edição dos arquivos necessários, rode o comando abaixo e espere iniciar, após isso, escaneie o QR Code.

> npm start
Ver todos os comandos
Digite no seu chat a mensagem, se você editou sua prefix, troque a '/' para o caractere que você utilizará.

> /menu
Crie seus comandos
Há uma base simples para suas criações por aqui, sem Prefix aqui, basta que você remova a "/*" e a "*/" para utilizá-la, se precisar de outros tipos, você pode ver sobre eles por aqui, se obtiver dificuldades, chame-me por aqui ou aqui.

Alertas no WhatsApp
Para receber também as mensagem de erros da Íris pelo WhatsApp, remova a "//" da linha Catch.
