# resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

Primeiro Lab:
---
Neste primeiro lab sobre a Microsoft Azure Computação em Numem, a professora mostrou serviços por categoria, como por exemplo:
 - **Computação**: Máquinas Virtuais, Azure Functions, Azure Kubernetes Service.
 - **Armazenamento**: Blob Storage, Azure Files, Disk Storage.
 - **Banco de Dados**: Azure SQL Database, Cosmos DB, Azure Database for MySQL/PostgreSQL.
 - **Rede**: Azure Virtual Network, Load Balancer, VPN Gateway, CDN.
 - **Segurança**: Azure Security Center, Key Vault, Sentinel.
 - **IA e Machine Learning**: Azure Machine Learning, Cognitive Services.
 - **DevOps**: Azure DevOps, GitHub Actions, Azure Monitor.

Segundo Lab:
---
No segundo lab, a gente viu um pouco sobre SLA que define o nível de disponibilidade que a Microsoft garante para seus serviços. A Azure oferece SLAs que variam entre 99% e 99,999% de tempo de atividade, dependendo do serviço, como máquinas virtuais, bancos de dados e outros. Esses SLAs são aplicados quando as condições específicas de configuração e redundância são atendidas.

Terceiro Lab:
---
No terceiro Lab a gente viu alguns modelos de serviço na nuvem, como IaaS, PaaS e SaaS, onde cada um oferece diferentes níveis de controle e gerenciamento:
  - **IaaS**: Você aluga a infraestrutura (servidores, armazenamento, rede) na nuvem. A gestão do sistema operacional e aplicativos fica por sua conta, enquanto a nuvem cuida do hardware.
  - **PaaS**: Oferece uma plataforma pronta para desenvolver, testar e gerenciar aplicativos. Você foca apenas no desenvolvimento, enquanto a infraestrutura e a plataforma são geridas pela nuvem.
  - **SaaS**: Fornece aplicativos prontos para uso, acessíveis pela internet. Você usa o software sem se preocupar com infraestrutura ou manutenção.

Quarto Lab:
---
No quarto Lab, vimos sobre a arquitetura da Azure e seus componentes, como:
 - **Regiões**: São áreas geográficas onde os data centers do Azure estão localizados. Cada região pode conter vários data centers para garantir alta disponibilidade e redundância. O Azure tem pares de regiões, onde duas regiões são conectadas para fornecer maior resiliência, como a região primária e a região de recuperação. Se uma falha ocorrer em uma região, a outra pode assumir, garantindo continuidade dos serviços.
 - **Grupo de Recursos**: É um contêiner lógico usado para agrupar recursos relacionados no Azure. Isso facilita o gerenciamento e a organização dos recursos, como máquinas virtuais, bancos de dados, redes e outros serviços, permitindo aplicar políticas, monitoramento e controle de forma eficiente.

Esses componentes ajudam a garantir alta disponibilidade, recuperação de desastres e organização eficiente dos recursos dentro do Azure.

Quinto Lab:
---
No quinto Lab, vimos sobre as máquinas virtuais Azure (VMs), que permitem executar sistemas operacionais e aplicativos na nuvem, com total controle sobre a configuração e os recursos. VMs são ideais para executar aplicativos legados, serviços personalizados ou sistemas operacionais que precisam ser configurados manualmente. E alguns aspectos correlacionados diretamente são:
 - **Conjuntos de Disponibilidade**: São usados para garantir alta disponibilidade em suas VMs. Eles distribuem as VMs em diferentes "domínios de falha" e "domínios de atualização" para minimizar o risco de falhas simultâneas, como quedas de hardware ou atualizações do sistema que afetem todas as instâncias de uma VM.
 - **Área de Trabalho Virtual (Azure Virtual Desktop)**: Oferece uma solução de virtualização de desktop e aplicativos, permitindo que os usuários acessem desktops e aplicativos Windows remotos. Isso é útil para trabalhadores remotos ou organizações que precisam de uma solução de TI escalável e centralizada.
 - **Contêineres** (Azure Kubernetes Service - AKS): É uma plataforma gerenciada para executar contêineres Docker e aplicativos distribuídos. Ele facilita a orquestração e o gerenciamento de contêineres, com alta escalabilidade e integração com outras soluções da Azure.
 - **Azure Functions**: É um serviço de computação sem servidor que permite executar código em resposta a eventos, sem precisar gerenciar infraestrutura. Você paga apenas pelo tempo de execução do código, o que a torna uma solução flexível e econômica para tarefas como processamento de eventos ou automação.
 - **Serviços de Aplicativo (App Service)**: É uma plataforma PaaS que facilita a construção, hospedagem e escalabilidade de aplicativos web e APIs. Ele suporta várias linguagens de programação e oferece recursos como autoescalonamento, integração contínua, e segurança.
