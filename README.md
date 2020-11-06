# Setup Docker usando ansible
Projeto criado para instalação do docker e docker-compose usando ansible.

## Instalação Ansible
```
sudo apt update
sudo apt install software-properties-common
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

Após a instalação do ansible será necessário clonar o repositório do setup_docker.

```
git clone https://github.com/brunomeloalmeida/setup_docker.git
```

Entre na pasta do projeto clonado e rode o seguinte comando.
```
ansible-playbook initial-setup.yml 
```

Após ter finalizado este passo reinicie a máquina para poder usar comandos docker sem o sudo.