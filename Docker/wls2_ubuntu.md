# Guia de Instalação do Docker no WSL 2 com Ubuntu 22.04
[Texto do link](https://medium.com/@habbema/guia-de-instala%C3%A7%C3%A3o-do-docker-no-wsl-2-com-ubuntu-22-04-9ceabe4d79e8)

### Comandos
- sudo apt install -y apt-transport-https ca-certificates curl software-properties-common - instalar as dependências do Docker.

- curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg - Adiciona a chave GPG oficial do Docker.

- echo "deb [signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null - Adiciona o repositório do Docker ao sistema.

- sudo apt update
- sudo apt install -y docker-ce docker-ce-cli containerd.io
- Os 2 comandos acima precisa ser juntos - Atualiza os repositórios e instale o Docker Engine.

- sudo usermod -aG docker $USER - Adicione seu usuário ao grupo Docker para evitar a necessidade de usar sudo em cada comando Docker.

- docker --version - verificar se o Docker foi instalado de forma correta.