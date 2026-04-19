# Introdução - O que é git? #1
[Texto do link](https://youtu.be/2c7yWlpWDJM?si=-3HJUxs51RItOlWU)

- GitHub é um provedor de hospedagem na Internet para desenvolvimento de software e controle de versão usando Git. Ele oferece o controle de versão distribuída e a funcionalidade de gerenciamento de código-fonte do Git, além de seus próprios recursos.

1. "Hostear" o seu código em um local seguro.
2. Compartilhar seu projeto facilmente com outros devs.
3. Outros devs podem colaborar com o seu projeto.

# Conceitos básicos do gitt? #2
[Texto do link](https://youtu.be/bZb0KiAbmNU?si=VRre25owHg-bqi2w)

### Repositório
- Este repositório rastreia todas as mudanças feitas nos arquivos do seu projeto, construindo um histórico ao longo do tempo.

### Commit
- Normalmente é usado quando termina as alterções do projeto, para deixar salvo.

### Branch
- É uma linha do tempo pararela dentro do seu projeto, normalmente usado para trabalhar outras funcionalidades, melhorias, correções sem afetar o projeto principal.

# Instalação e configuração #3
[Texto do link](https://youtu.be/q9dnokwu7S8?si=sslLfQpvrOs9f6mX)

- Github - já instalado
- Visual Studio Code - já instalado
- Nano - Já instalado

# Criando repositórios #4
[Texto do link](https://youtu.be/Hw3ykxHHKiw?si=z1KRx8F6-Jcj9XV7)

- mkdir - *comando que ira criar nova pasta - mkdir nomedapasta*
- mv - *comanda para trocar o nome da pasta - mv nomeantigo nomenovo*
- git init - *iniciar o git*
- cd nomepastaentrar - *comando que faz entrar na pasta.*
- cd .. para sair da pasta atual - *comando para sair da pasta que está.*
- cd ../nomepastarentrar - *comanda que faz voce sair da pasta autal para a outra que quer entrar.*

# Colocando arquivos no stage #5
[Texto do link](https://youtu.be/-PGHFtlEF0E?si=CKFqdOX96ZDE4RUK)

- git status - *comando para iniciar o git.*
- git add nomedoarquivo - *comando para criar o arquivo dentro da pasta, exemplo index.html.*
- git add - *comando para adicionar todos os arquivos juntos.*

# Fazendo commits #6
[Texto do link](https://youtu.be/n5WUYkkeCws?si=eZraHXx12gP_a6hd)

- git commit -m "Adicionando arquivo index". - *comando para comentar alguma informação no commet.*

# Desfazendo commit #7
[Texto do link](https://youtu.be/CAlg29rF2VY?si=UZkV-Z2uwJ4kMFrq)

- git log --oneline - *comando para visualizar o historico de alterações, onde verifica os ids dos commit*
-git chackout iddeondequervoltar - *comando que faz voltar o estagio que estava antes, apaga tudo que foi feito depois do id colocado para voltar.*
- git checkout main - *comando que faz voltar tudo que foi feito até o momento atual, caso tenha sido apagado algo.*

# Ignorando arquivos #8
[Texto do link](https://youtu.be/pNLb7M-UzO8?si=kkieC0YaEyeNKeZc)

- gitignore - *um arquivo onde não aparece as informações dentro dele para outros usuários, alem de quem tem o arquivo.*

# Criando branches #9
[Texto do link](https://youtu.be/lq3nawUnpEI?si=kid6aj0lJ6fNlbIn)

 - Branch - *uma outra linha de codigo que voce começa a fazer edições sem afetar o script principal, depois da atualização é so fundir com o código principal.*
 - git branch - *comando que mostra a lista de branch existente no projeto.*
 - gt branch nomedocarquivo - *comando onde criar uma nova Branch para trabalhar.*

# Fundindo branches #10
[Texto do link](https://youtu.be/o5fm7l_e1Bc?si=fn5M5q5tzmVFFjuE)

- Senpre ir para o Main de destino, desta forma voce ira trazer o outro Branc que voce quer fundir.
- git merge nomedoarquivo- *comando que ira trazer a outra branch para a atual, fundindo as duas.*

# Resolvendo conflitos #11
[Texto do link](https://youtu.be/FSzHRPa-zl4?si=vahWvQMYRdjs5How)

git log --onelinne - *comando onde mostra todos os commits.*
git commit - *comando que em casos de erro termina a fusão das branches.*

# Iniciando com Github #12
[Texto do link](https://youtu.be/uaWtCItNry8?si=H4dXIAjzNRMdKSTA)

- Baixar o GitHub  Já está instalado.
- git clone SSHdoprojetonocit - *comando que faz clonar o projeto do git para seu computador.*
- rm -rf nomedaspatas - *comando para deletar uma pasta.*

### Vincular a chave SSH no GitHub
- ssh-keygen -t rsa -b 4096 -C "borelli.felipe01@gmail.com" - *comando para permitir ser gerado a chave SSH.* Depois disso ira aparecer para colocar a senha caso queira, se não precisar da enter até aparecer os desenhos.
- cat C:\Users\Saipos\.ssh\id_rsa.pub - *comando para gerar a chave para ser colado no GitHub.*

# Simulando múltiplos devs #13
[Texto do link](https://youtu.be/AQ5v4ZCG1h0?si=uSsKWSPvFjPM58d6)

- git clone SSHdoprojetonocit nomedapasta - *comando que faz clonar a pasta renomeando ela no seu computador de outra forma para queira identificar.*
- Git commit -m "mensagem" --autor= "nomedequemfezcomit" - *comando para identificar o comite com o nome do responsavel.*

# Fazendo Pull Request (PR) #14
[Texto do link](https://youtu.be/RNbKd8cD0LI?si=FEcqXjZj-i3I0NIC)

git push origin svg - *comando para ficar no GitHub para o script ser analisado, para alguém autorizar a fusão no GetHub.*
