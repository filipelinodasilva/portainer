###🚀 Auto-Instalador Docker Swarm + Traefik + Portainer
Diga adeus à configuração manual e olá para a automação total! Este projeto lança seu ambiente Docker Swarm, com Traefik e Portainer, em minutos, garantindo um setup de nível profissional sem dor de cabeça.

<br>
📌 Pré-requisitos
Antes de decolar, você só precisa de uma coisa: um sistema Linux preparado para rodar o Docker Swarm.

<br>
🛠️ Passo a passo para instalação
Siga esta missão e veja a mágica acontecer diretamente no seu terminal.

<br>
<br>
1️⃣ Instale o Git
O ponto de partida! Se o Git ainda não está no seu arsenal, adicione-o com este comando:

```bash
apt install git -y
```

<br>
2️⃣ Faça o clone do repositório
Traga a caixa de ferramentas mágica para sua máquina com um simples clone do nosso GitHub:

```bash
git clone https://github.com/filipelinodasilva/portainer.git
```

<br>
3️⃣ Acesse a pasta do script
Entre na sala de controle. É aqui que a ação vai começar!

```bash
cd portainer
```

<br>
4️⃣ Dê permissão de execução ao script
Dê superpoderes ao nosso script! Este comando o torna executável e pronto para o trabalho:

```bash
chmod +x install_docker_swarm.sh
```

<br>
5️⃣ Execute o script de instalação
O momento da verdade! Rode o comando abaixo e assista seu ambiente ser construído na sua frente:

```bash
./install_docker_swarm.sh
```

<br>
<br>
🔍 O que este script faz?
<br>✅ Lança o Docker Swarm para você, sem esforço.
<br>✅ Cria uma rede overlay exclusiva para seus serviços rodarem em harmonia.
<br>✅ Configura o Traefik com SSL via Let's Encrypt para acesso seguro e profissional.
<br>✅ Sobe o Portainer para você gerenciar seu Docker com uma interface gráfica incrível.
<br>✅ Gera os arquivos traefik.yaml e portainer.yaml dinamicamente para você.

<br>
<br>
📢 Atenção
- Durante a execução, o script vai te pedir algumas infos cruciais (nome da rede, e-mail para SSL, domínio do Portainer). Capriche nas respostas para o sucesso da missão!
- Após o término, dê uma pausa de 30 segundos antes de acessar o Portainer no navegador para dar tempo de tudo iniciar.
🔗 Acesse o Portainer usando o domínio que você configurou durante a instalação!

<br>
<br>
💡 Dúvidas ou sugestões?
Sua ideia pode ser a próxima grande feature! Contribua com o projeto AutomateIA! 🚀
