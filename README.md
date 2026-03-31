# 🚀 Curso de DevOps & Infraestrutura como Código (IaC)

Este repositório contém os laboratórios práticos realizados durante o curso de DevOps na Uninter. O objetivo principal é a automação de infraestrutura, monitorização e gestão de serviços utilizando ferramentas modernas do mercado.

## 🛠️ Tecnologias Utilizadas
* **Vagrant:** Gestão e automação de máquinas virtuais.
* **Oracle VirtualBox:** Provedor de virtualização.
* **Ubuntu 20.04 LTS (Focal Fossa):** Sistema operativo do servidor.
* **Apache2:** Servidor Web para disponibilização de serviços.
* **WSL2:** Ambiente Linux dentro do Windows para execução de comandos.

## 🏗️ Estrutura do Laboratório
O ambiente foi configurado com um endereço IP fixo (**192.168.0.150**) para permitir o acesso direto a partir do sistema anfitrião (Windows).

### Principais Comandos de Gestão:
- \agrant up\: Inicia a infraestrutura.
- \agrant ssh\: Acesso remoto ao servidor Linux.
- \agrant halt\: Desliga a máquina virtual para poupar recursos.
- \ip a\: Verificação de interfaces de rede e conectividade.

## 📝 Evolução do Projeto
1. [x] Configuração do Ambiente Vagrant.
2. [x] Estabelecimento de conectividade via Bridge e NAT.
3. [x] Instalação e configuração do Servidor Web Apache.
4. [ ] Implementação de Monitorização (Próximo passo: Prometheus & Grafana).

---
**Desenvolvido por Sivaldo**
*Aspiring DevOps & Cybersecurity Professional*