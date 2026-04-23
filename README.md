# 🏠 Homelab — Servidor Doméstico com Ubuntu Server + CasaOS

> Servidor doméstico de uso real, construído do zero em hardware reciclado, com foco em privacidade, automação e aprendizado prático de infraestrutura Linux e cloud.

---

## 📋 Visão Geral

Este projeto consiste na criação e manutenção de um servidor doméstico completo, utilizando um notebook antigo como hardware base, rodando **Ubuntu Server** com interface gerenciada pelo **CasaOS**. O objetivo foi criar um ambiente de aprendizado prático que simula desafios reais de infraestrutura, rede e segurança.

---

## 🛠️ Hardware

| Componente | Descrição |
|---|---|
| **Dispositivo** | Notebook reciclado |
| **Sistema Operacional** | Ubuntu Server (Linux) |
| **Interface de Gerenciamento** | CasaOS |

---

## ⚙️ Serviços Configurados

### 🛡️ Pi-hole — Bloqueador de Anúncios em Rede
- Atua como servidor DNS na rede local
- Bloqueia anúncios e rastreadores em **todos os dispositivos** da rede simultaneamente
- Sem necessidade de instalar extensões em cada dispositivo

### 🔐 Gerenciador de Senhas Privado
- Solução self-hosted para armazenamento seguro de credenciais
- Configuração de **conexão segura (HTTPS)** com certificado SSL
- Acesso protegido via **proxy reverso**

### ☁️ Nuvem Privada
- Armazenamento em nuvem privado, sem depender de serviços terceiros
- Sincronização de arquivos dentro da rede local e remotamente

### 🎵 Servidor de Músicas
- Streaming de música self-hosted
- Biblioteca musical acessível de qualquer dispositivo na rede

---

## 🌐 Acesso Remoto

- **Tailscale VPN** — acesso seguro ao servidor de qualquer lugar do mundo
- Toda a comunicação criptografada end-to-end
- Sem necessidade de expor portas diretamente à internet

---

## 🔧 Desafios Técnicos Superados

| Desafio | Solução Aplicada |
|---|---|
| Abertura e redirecionamento de portas | Configuração de port forwarding no roteador |
| Instalação e gerenciamento de pacotes | apt, Docker, gerenciamento de dependências no Linux |
| Configuração de rede local | IP fixo, DNS personalizado com Pi-hole |
| Conexão segura (HTTPS) | Certificado SSL + configuração de proxy reverso |
| Proxy e proxy reverso | Nginx / Traefik para roteamento de serviços |
| Manutenção contínua | Atualizações, backups e monitoramento periódico |

---

## 🧰 Stack Tecnológica

![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-E95420?style=flat&logo=ubuntu&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-000000?style=flat&logo=tailscale&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Pi--hole](https://img.shields.io/badge/Pi--hole-96060C?style=flat&logo=pi-hole&logoColor=white)

**Principais tecnologias utilizadas:**
- Ubuntu Server
- CasaOS
- Pi-hole
- Tailscale VPN
- Proxy Reverso (Nginx / Traefik)
- SSL/HTTPS
- Docker (containers)
- Redes TCP/IP

---

## 📚 Aprendizados

Este projeto proporcionou experiência prática em:

- **Administração de servidores Linux** — instalação, configuração e manutenção
- **Redes** — DNS, DHCP, port forwarding, VPN, proxy reverso
- **Segurança** — SSL/TLS, autenticação, acesso remoto seguro
- **Infraestrutura como código** — configuração e manutenção de serviços
- **Troubleshooting** — diagnóstico e resolução de problemas reais

---

## 👤 Autor

**Andrey Ferraz**  
Analista de Cloud Júnior | AWS Cloud Practitioner | COBIT 2019  
📍 Brasília, Brasil  
🔗 [LinkedIn](https://www.linkedin.com/in/andrey-ferraz-de-araujo/)

---

> *"A melhor forma de aprender infraestrutura é colocando a mão na massa — e esse projeto é a prova disso."*
