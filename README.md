# dio-ec2-lab
Repositório do desafio DIO sobre gerenciamento de instâncias EC2 na AWS

#  Desafio DIO: Gerenciamento de Instâncias EC2 na AWS

Este repositório faz parte do desafio da plataforma DIO, com o objetivo de aplicar, na prática, os conhecimentos adquiridos sobre o uso de instâncias EC2 na nuvem AWS.

---

##  Objetivo

- Criar, configurar e acessar uma instância EC2 na AWS.
- Instalar e testar um serviço simples (como o Apache).
- Documentar todo o processo de forma clara usando GitHub.

---

##  Tecnologias e Ferramentas Utilizadas

- AWS EC2
- Ubuntu Server
- SSH (Secure Shell)
- Apache2
- Git e GitHub
- Markdown

---

## Etapas Realizadas

###  1. Criação da Instância EC2

- AMI utilizada: **Ubuntu Server 22.04 LTS**
- Tipo de instância: **t2.micro (elegível ao uso gratuito)**
- Criação de par de chaves (.pem) para acesso via SSH
- Configuração do Security Group:
  - Porta 22 liberada (acesso SSH)
  - Porta 80 liberada (acesso HTTP opcional)

---

###  2. Acesso à Instância via SSH

Foi realizado o acesso à instância através de um terminal com SSH, utilizando a chave gerada no momento da criação.

---

### 3. Instalação do Servidor Apache

Após acessar a instância via SSH, foram executados os seguintes comandos:

```bash
sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2


## ✍️ Autor

**Kamila Alves Rodrigues de Souza**  
[GitHub](https://github.com/milakck)





