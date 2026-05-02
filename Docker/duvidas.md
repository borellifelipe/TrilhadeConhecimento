#  Mudar o perfil padrão de inicialização e diretorio.
[Texto do link](https://youtu.be/yGPMJsjUL78?si=knhD3f_A360aVmbR&t=86)

- Duvida seria se isso é importante para o dia a dia, e se ajuda ou prejudica em algo.
<!-- passo a passo.
No terminal - setinha para baixo
configuração
inicialização - Perfil padrão mudar para Ubuntu

Ubuntu
Diretorio inicial - procurar o diretorio Inicial - 
Barra de pesquisa - \\wsl$ enter ira aparecer o ubuntu e selecione e salve

testar com o comoando pwd para ver se ficou no diretorio que voce escolheu. 

-->

Neste exercício você precisará fazer download de um arquivo .zip, alterá-lo e compactá-lo novamente.

Utilize o campo de texto para listar todos os comandos necessários para executar as ações requisitadas. Caso queira fazer algum comentário, fique a vontade.

O arquivo a ser utilizado no exercício se encontra em:
https://saipos-estatico.s3.sa-east-1.amazonaws.com/files_devops.zip

1. Crie um novo diretório para receber o arquivo que será baixado;
2. Baixe o arquivo indicado (files_devops.zip) dentro do novo diretório criado;
3. Descompacte o arquivo baixado;
4. Crie um novo arquivo compactado chamado "files_devops_new.zip" com todos os arquivos descompactados anteriormente, exceto os iniciados com "old_".

Dicas: pesquise sobre os comandos "curl" e "zip".

Pasta criada - mkdir -SAIPOS
Entrando na pasta - cd SAIPOS
Foi necessario baixar o curl, zip, e unzip. - apt install < comando>
Comando -  curl -O https://saipos-estatico.s3.sa-east-1.amazonaws.com/files_devops.zip - para baixar o arquivo "zip"

<!--

file files_devops.zip
"Isso é mesmo um ZIP?"

ls -lh	Armazenamento	"Quanto espaço esse ZIP ocupa?"
7z l	Conteúdo	"O que tem dentro desse ZIP?"