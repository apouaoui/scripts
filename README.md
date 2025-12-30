# 🛠️ Linux Automation Suite

![Bash](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Uma coleção curada de scripts robustos para otimização, manutenção e automação de sistemas baseados em Unix.

---

## 📌 Sumário
* [Sobre o Projeto](#-sobre-o-projeto)
* [Scripts em Destaque](#-scripts-em-destaque)
* [Instalação e Uso](#-instalação-e-uso)
* [Dicas de Segurança](#-segurança)
* [Contribuindo](#-contribuição)

---

## 📖 Sobre o Projeto
Este repositório nasceu da necessidade de automatizar tarefas repetitivas no dia a dia. Aqui você encontrará desde automações de backup até setups completos de ambiente de desenvolvimento.

**Principais funcionalidades:**
* 🧹 Limpeza profunda de logs e cache.
* 🛡️ Endurecimento (Hardening) básico de segurança.
* 📦 Instalação em massa de pacotes essenciais.
* 📊 Monitoramento de recursos do sistema.

---

## 📂 Scripts em Destaque

| Nome | Função | Contexto |
| :--- | :--- | :--- |
| `sys-update.sh` | Atualização total (Apt/Flatpak/Snap) | Manutenção |
| `docker-check.sh` | Health check de containers ativos | DevOps |
| `net-speed.sh` | Teste de latência e banda via CLI | Redes |
| `auto-backup.sh` | Backup comprimido via rsync | Segurança |

---

## 🚀 Instalação e Uso

### Pré-requisitos
Certifique-se de ter o `git` instalado:
```bash
sudo apt install git -y  # Debian/Ubuntu
sudo dnf install git     # Fedora
