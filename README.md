# ?? Laboratório de DevOps: Infraestrutura e Deploy Web

Este repositório documenta a configuração de um ambiente completo de servidor web utilizando práticas de **Infraestrutura como Código (IaC)** e automação.

## ??? Estrutura do Projeto
* **Vagrantfile:** Configuração da máquina virtual Ubuntu 20.04 (Focal Fossa).
* **projeto-professor/:** Código-fonte do site "Mundo Invertido" (HTML/CSS/JS/Assets) integrado ao repositório para histórico de deploy.
* **IP do Servidor:** \192.168.0.150\ (Acessível via rede Bridge).

## ??? Tecnologias e Ferramentas
- **Vagrant & VirtualBox:** Virtualização e provisionamento.
- **Apache2:** Servidor web responsável por hospedar os ficheiros.
- **Git/GitHub:** Controlo de versão e gestão de código.
- **WSL2:** Interface de comandos Linux no Windows.

## ?? Como realizar o Deploy (Passo a Passo)

Se precisar de subir este ambiente do zero, os comandos são:

1. **No Windows (PowerShell):**
   \\\powershell
   vagrant up
   vagrant ssh
   \\\

2. **No Ubuntu (Terminal Linux):**
   \\\ash
   # Atualizar e instalar o servidor web
   sudo apt update && sudo apt install apache2 -y

   # Copiar os arquivos do projeto para a pasta pública do Apache
   sudo cp -R /vagrant/projeto-professor/* /var/www/html/
   \\\

3. **Aceder no Navegador:**
   Abra \http://192.168.0.150\ para ver o site em funcionamento.

---
**Status do Projeto:** ?? Deploy concluído com sucesso.
**Autor:** Sivaldo (EngSivaldo)
