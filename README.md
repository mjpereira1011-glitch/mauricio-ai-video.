Maurício AI Video
Protótipo web responsivo em português para Android e desktop. Permite montar prompts cinematográficos para:
Texto para vídeo
Imagem para vídeo (com pré-visualização local)
Formato, duração pretendida, estilo visual e movimento de câmera
Copiar ou baixar o prompt em .txt
Limite importante
Este projeto não gera vídeo localmente nem inclui uma API de IA. Ele prepara um prompt e oferece links para serviços externos. Demos públicas podem ter filas, limites, indisponibilidade ou exigir conta. Hospedagem gratuita do site não significa geração de vídeo ilimitada e gratuita. Não coloque tokens/chaves de API no JavaScript público.
Testar no computador
Abra index.html em um navegador moderno. Para recursos de clipboard mais confiáveis, rode um servidor local, por exemplo:
python -m http.server 8000
Depois abra http://localhost:8000.
Publicar gratuitamente com GitHub Pages
Crie/entre na sua conta em https://github.com/.
Crie um repositório público chamado mauricio-ai-video.
Envie index.html, styles.css e app.js para a raiz do repositório (também pode enviar README.md).
No repositório, abra Settings → Pages.
Em Build and deployment, selecione Deploy from a branch.
Escolha main e a pasta / (root), depois clique Save.
Aguarde o endereço aparecer na página Pages. Geralmente será https://SEU-USUARIO.github.io/mauricio-ai-video/.
Os nomes dos menus podem mudar conforme a interface do GitHub. O endereço só funcionará depois de você publicar no seu próprio repositório.
Conectar um gerador real depois
Para integrar geração automática, escolha um provedor/modelo que ofereça API de vídeo e confira seus termos, preço, limites e política de uso. Crie um backend/serverless para guardar a chave de API como segredo e fazer a requisição; o frontend deve chamar seu backend, nunca expor a chave. Provedores gratuitos podem mudar ou encerrar cotas. Não há uma API de geração conectada neste protótipo.
Arquivos
index.html: estrutura do site
styles.css: visual e responsividade
app.js: seleção de modo, imagem, montagem/cópia/download do prompt
