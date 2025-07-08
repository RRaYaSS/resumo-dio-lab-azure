# Desafio DIO: Relatório de Criação de Máquina Virtual no Azure

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)

---

## 📄 Resumo do Projeto

Relatório técnico que documenta o processo simulado de criação de uma Máquina Virtual Windows no Azure para o Desafio de Projeto da DIO. O projeto aborda a configuração de recursos de computação, rede e armazenamento, com foco na demonstração dos conhecimentos em nuvem e na documentação via GitHub.

---

## 🎯 Objetivos de Aprendizagem

O principal objetivo deste projeto foi consolidar e aplicar os conhecimentos adquiridos sobre a plataforma Microsoft Azure, especificamente em:

- **Planejamento e Criação:** Entender o fluxo de criação de um serviço IaaS (Infraestrutura como Serviço).
- **Configuração:** Definir parâmetros essenciais de uma VM, como grupo de recursos, dimensionamento, rede e segurança.
- **Documentação Técnica:** Estruturar e documentar um processo técnico de forma clara, utilizando Markdown e compartilhando o resultado no GitHub.

---

## 🛠️ Conceitos e Tecnologias Abordadas

- **Microsoft Azure:** Plataforma de nuvem utilizada para a criação dos recursos.
- **Máquinas Virtuais (VMs):** Serviço de computação IaaS central deste projeto.
- **Grupos de Recursos:** Contêineres lógicos para agrupar e gerenciar os serviços do Azure.
- **Rede Virtual (VNet) e Segurança de Rede:** Conceitos de conectividade e segurança para a VM, incluindo a liberação da porta RDP (3389) para acesso remoto.
- **GitHub:** Plataforma utilizada para versionamento de código e documentação.
- **Markdown:** Linguagem de marcação para formatação do `README.md`.

---

## 👣 Guia de Criação da VM (Processo Simulado)

A seguir, são detalhadas as etapas simuladas no Portal do Azure para a criação da Máquina Virtual.

### 1. Aba "Básicos"
Nesta etapa inicial, foram definidas as configurações fundamentais da VM.

- **Grupo de Recursos:** `desafio-dio-azure-rg`
- **Nome da máquina virtual:** `vm-windows-dio01`
- **Região:** `(South America) Brazil South`
- **Imagem:** `Windows Server 2022 Datacenter: Azure Edition`
- **Credenciais de Administrador:** Usuário `admin-dio` e senha segura.
- **Portas de Entrada:** Permitido o acesso à porta `RDP (3389)`.

![Captura de tela da Aba Básicos](images/aba-basicos.png)

### 2. Aba "Discos"
Foi mantida a configuração padrão com um disco de sistema operacional do tipo **SSD Padrão** para um bom equilíbrio entre custo e performance.

![Captura de tela da Aba Discos](images/aba-discos.png)

### 3. Aba "Rede"
As configurações de rede foram, em sua maioria, criadas automaticamente pelo Azure. A validação principal foi garantir que o Grupo de Segurança de Rede (NSG) permitia o tráfego de entrada na porta RDP (3389).

![Captura de tela da Aba Rede](images/aba-rede.png)

### 4. Aba "Revisar + criar"
O Azure realizou uma validação final de todas as configurações. Após a confirmação ("Validação aprovada"), a implantação da VM foi iniciada.

![Captura de tela da Aba Revisar + criar](images/aba-revisar-criar.png)

---

## ✅ Conclusão

Este desafio permitiu uma imersão prática e simulada no processo de provisionamento de recursos no Microsoft Azure. A documentação de cada etapa não apenas solidificou o aprendizado, mas também resultou em um guia claro que demonstra as competências adquiridas. O projeto foi concluído com sucesso, atingindo todos os objetivos propostos.
