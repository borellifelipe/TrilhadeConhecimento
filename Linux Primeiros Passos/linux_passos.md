#  Primeiros Passos
[Texto do link](https://youtu.be/6nN2EglOqCM?si=SbHhSWE4AbvLkuWu)

- apenas a pessoa falando dos proximos videos de como ira ser.

#  Onde o Linux pode ser usado? #01
[Texto do link](https://youtu.be/R_8l3xj3QEg?si=qSEJWyl-bfpeM88b)

- Introdução do Linux, onde ele é usado.

# De onde veio o Linux? O que é software livre? #02
[Texto do link](https://youtu.be/qs_NZXmVUr0?si=n7R8BWB9UDoxtaLq)

### De onde veio o Linux? 
- O Linux não foi criado do zero "no vácuo". Ele foi fortemente inspirado no Unix, um sistema robusto criado nos anos 70.

### O que é software livre?
- O conceito de software livre refere-se a programas de computador que garantem aos seus usuários total autonomia e liberdade de uso, opondo-se ao modelo de software proprietário, onde o controle pertence exclusivamente a uma empresa.

# Licenças e Liberdades: é importante saber? #03
[Texto do link](https://youtu.be/-cR-0Ggi3B4?si=YlHBpXwmxSelXDIS)

- Licenças e liberdades no contexto do Linux e do software livre são fundamentais para entender como os programas podem ser usados, modificados e distribuídos. O vídeo explica que software livre não significa necessariamente gratuito, mas sim que oferece liberdade ao usuário.

# Instalando Linux Mint? #04
[Texto do link](https://youtu.be/-cR-0Ggi3B4?si=YlHBpXwmxSelXDIS)

- Não instalei o Mint, pois tenho o Ubuntu

# Pendrive Linux com Etcher #04.2
[Texto do link](https://youtu.be/EgPxsHGxspA?si=cbxmH03BdRqK0uXF)

- Continuação da instalação do Linux Mint para quem ficou com problema na instalação na parte do pendriver.

# Conhecendo o Ambiente do Linux Mint #05
[Texto do link](https://youtu.be/7KsdRHwO2Sk?si=ACe7rbYfgyXAp6iV)

- passo a passo de instalação de blibliotecas(pacotes), para deixar o sistema pronto para rodar.

# Instalação básica de programas no Linux #06.1
[Texto do link](https://youtu.be/L79u8csXwBU?si=-M6dkOfdpW4b9d3-)

- instalaçãoes basicas de aplicativos - entrando no "Gerenciador de Aplicativos" 

# Instalação avançada de programas no Linux #06.2
[Texto do link](https://youtu.be/HlbrYQqyXpg?si=4HzN5QKO7F1QI8H0)

- Synaptic Package Manager
Primeiro ele mostra a instalação de programas de forma gráfica

-Repositórios via APT (apt / apt-get)
Depois ele vai para o terminal, mostrando como instalar pelos repositórios

- Site oficial do programa (ex: Visual Studio Code)
Em seguida, mostra baixar direto do site do desenvolvedor

-Sites de pacotes (.deb), como pkgs.org
Por último, mostra buscar pacotes em sites externos

# Terminal no Linux - Introdução #07.1
[Texto do link](https://youtu.be/mgs92GtkQCE?si=Sc_F3EYdH--QTZJh)

- Ensinaram comandos básicos como:
pwd - mostra onde você está no sistema
ls - lista arquivos e pastas
cd nome_da_pasta - entra em uma pasta
cd .. - volta uma pasta
/ representa a raiz do sistema

- Mostram algumas pastas importantes:
/bin - comandos do sistema
/home - arquivos dos usuários
/boot - inicialização
/tmp - arquivos temporários
/var - logs e dados variáveis
/dev - dispositivos

-Criar pastas e arquivos
mkdir linux - cria pasta
touch arquivo.txt - cria arquivo vazio

# Terminal no Linux - Introdução #07.2
[Texto do link](https://youtu.be/kK6eBHSxAgA?si=SaTkJbEXyt3lL2mX)

- Para visualizar arquivos e pastas:
ls - lista conteúdo
ls -a - mostra arquivos ocultos
ls -l - lista detalhada

- Depois explicam como criar diretórios:
mkdir Nome_da_Pasta - cria pasta chamada cursos
mkdir -p pasta1/pasta2/pasta3 - cria várias pastas de uma vez

- remoção:
ir nome_da_pasta → remove pasta vazia
rm arquivo.txt - remove arquivo
rm -r pasta - remove pasta e conteúdo
rm -rf pasta - remove tudo sem pedir confirmação (comando perigoso)

# Terminal Linux - Referência Global #08
[Texto do link](https://youtu.be/7XQ3Qt7EuWg?si=-uXyEUxhZqlj9oHW)

- Asterisco (*) - Representa qualquer quantidade de caracteres.
ls *.txt - Mostra todos os arquivos com final .txt
rm foto* - Apaga tudo que começa com foto

- Interrogação (?) - Representa apenas 1 caractere.
ls arquivo?.txt

- Colchetes [ ] - Usado para escolher caracteres específicos.
ls arquivo[123].txt
ls arquivo[1-5].txt
ls foto[a-z].jpg

# Manipulação de Arquivos com Linux - Curso Linux #09
[Texto do link](https://youtu.be/GEU0tmpjVfM?si=FDAwZEYrkG8IxkpU)

- Conceitos importantes explicados
mkdir teste - Cria uma pasta chamada teste no local atual.
cd teste - Entra dentro da pasta teste.
touch arquivo1.txt - Cria um arquivo vazio chamado arquivo1.txt.
cat arquivo1.txt - Mostra o conteúdo do arquivo. Como ele está vazio, não aparecerá nada.
cp arquivo1.txt copia.txt - Cria uma cópia de arquivo1.txt com o nome copia.txt
mv copia.txt novo.txt - Renomeia copia.txt para novo.txt
ls - Lista o conteúdo da pasta atual. 
rm novo.txt - Apaga o arquivo novo.txt
cd .. - Sai da pasta teste e volta para a pasta anterior.
rm -r teste - Apaga a pasta teste e tudo que estiver dentro dela.

# Uso de pendrives e HDs externos no Linux - Curso Linux #10
[Texto do link](https://youtu.be/Ntg1JfjEAd4?si=DvYFS7ApyGXlqNRz)

- Ensinam que é possível formatar pendrives e HDs externos direto no Linux, escolhendo o sistema de arquivos ideal dependendo do uso:
FAT32 - maior compatibilidade
exFAT - arquivos grandes e compatibilidade moderna
EXT4 - melhor para uso somente no Linux


lsblk - Lista discos e partições
df -h -Espaço livre/usado
sudo fdisk -l - Detalhes completos dos discos
