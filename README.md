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
No quarto Lab vimos sobre a arquitetura da Azure e seus componentes, como:
 - **Regiões**: São áreas geográficas onde os data centers do Azure estão localizados. Cada região pode conter vários data centers para garantir alta disponibilidade e redundância. O Azure tem pares de regiões, onde duas regiões são conectadas para fornecer maior resiliência, como a região primária e a região de recuperação. Se uma falha ocorrer em uma região, a outra pode assumir, garantindo continuidade dos serviços.
 - **Grupo de Recursos**: É um contêiner lógico usado para agrupar recursos relacionados no Azure. Isso facilita o gerenciamento e a organização dos recursos, como máquinas virtuais, bancos de dados, redes e outros serviços, permitindo aplicar políticas, monitoramento e controle de forma eficiente.

Esses componentes ajudam a garantir alta disponibilidade, recuperação de desastres e organização eficiente dos recursos dentro do Azure.

Quinto Lab:
---
No quinto Lab vimos sobre as máquinas virtuais Azure (VMs), que permitem executar sistemas operacionais e aplicativos na nuvem, com total controle sobre a configuração e os recursos. VMs são ideais para executar aplicativos legados, serviços personalizados ou sistemas operacionais que precisam ser configurados manualmente. E alguns aspectos correlacionados diretamente são:
 - **Conjuntos de Disponibilidade**: São usados para garantir alta disponibilidade em suas VMs. Eles distribuem as VMs em diferentes "domínios de falha" e "domínios de atualização" para minimizar o risco de falhas simultâneas, como quedas de hardware ou atualizações do sistema que afetem todas as instâncias de uma VM.
 - **Área de Trabalho Virtual (Azure Virtual Desktop)**: Oferece uma solução de virtualização de desktop e aplicativos, permitindo que os usuários acessem desktops e aplicativos Windows remotos. Isso é útil para trabalhadores remotos ou organizações que precisam de uma solução de TI escalável e centralizada.
 - **Contêineres** (Azure Kubernetes Service - AKS): É uma plataforma gerenciada para executar contêineres Docker e aplicativos distribuídos. Ele facilita a orquestração e o gerenciamento de contêineres, com alta escalabilidade e integração com outras soluções da Azure.
 - **Azure Functions**: É um serviço de computação sem servidor que permite executar código em resposta a eventos, sem precisar gerenciar infraestrutura. Você paga apenas pelo tempo de execução do código, o que a torna uma solução flexível e econômica para tarefas como processamento de eventos ou automação.
 - **Serviços de Aplicativo (App Service)**: É uma plataforma PaaS que facilita a construção, hospedagem e escalabilidade de aplicativos web e APIs. Ele suporta várias linguagens de programação e oferece recursos como autoescalonamento, integração contínua, e segurança.

Sexto Lab:
---
No sexto Lab vimos os studios da azure, o Estúdio de Fala e o Language Studio:
 - **Estúdio de Fala (Speech Studio)**: Essa plataforma permite criar e personalizar soluções que lidam com reconhecimento de fala, síntese de fala, tradução e outros serviços relacionados à fala. Ele oferece APIs para transformar voz em texto (ASR), texto em voz (TTS), e realizar transcrições de áudio, entre outros. O objetivo é integrar interações de fala natural em aplicativos, como assistentes virtuais e sistemas de atendimento ao cliente.
 - **Language Studio**: Focado em soluções de processamento de linguagem natural (PLN), o Language Studio permite que os desenvolvedores criem, treinem e implementem modelos de IA para análise de texto. Isso inclui tarefas como entendimento de intenção (NLP), análise de sentimentos, extração de informações e tradução de idiomas. Ele também oferece ferramentas para trabalhar com chatbots e modelos de linguagem personalizados.

Ambos os estúdios são integrados à Azure Cognitive Services, proporcionando poderosas ferramentas de IA que podem ser facilmente aplicadas em vários cenários, como chatbots, assistentes de voz e sistemas de automação.

Sétimo Lab:
---
No sétimo Lab vimos algumas ferramentas do azure sobre buscas cognitivas e alguns conceitos:
 - **Mineração de Conhecimento**: Processo de descobrir padrões, insights e informações relevantes a partir de grandes volumes de dados, utilizando técnicas de análise e aprendizado de máquina.
 - **Solução de Pesquisa Cognitiva do Azure**: Plataforma que combina IA, aprendizado de máquina e processamento de linguagem natural (PLN) para melhorar a busca e extração de informações em grandes volumes de dados, permitindo resultados mais inteligentes e relevantes.
 - **Enriquecimento de IA**: Conjunto de ferramentas do Azure que aplicam IA para melhorar dados, como a extração de informações contextuais e insights, usando APIs de aprendizado de máquina, visão computacional e PLN.
 - **Buscas Cognitivas**: Ferramenta de busca inteligente que utiliza IA para fornecer resultados mais precisos e contextuais, permitindo que empresas integrem e busquem dados de diferentes fontes de maneira mais eficaz, com base no significado e não apenas nas palavras-chave.

Oitavo Lab:
---
No oitavo Lab vimos sobre IA Generativa Responsável, e ferramentas generativas da microsoft:
 - **IA Generativa Responsável**: Refere-se ao desenvolvimento e uso de tecnologias de inteligência artificial (IA) de maneira ética e segura, priorizando a transparência, a equidade, a privacidade e a responsabilidade social. O objetivo é minimizar os riscos de danos causados pela IA, como a geração de desinformação ou discriminação, garantindo que as ferramentas sejam benéficas para todos.
 - **Microsoft Copilot**: É uma linha de ferramentas de IA integradas a produtos Microsoft, como o Word, Excel e Outlook. Ele utiliza IA generativa para automatizar tarefas e melhorar a produtividade, ajudando os usuários a redigir textos, gerar relatórios, analisar dados e realizar várias outras funções de maneira mais eficiente e inteligente.
 - **Possibilidades do Microsoft Learning**: Envolvem o uso de IA e ferramentas de aprendizado baseadas em nuvem para promover uma educação personalizada e acessível. A Microsoft oferece recursos de aprendizado que ajudam tanto educadores quanto alunos a melhorar suas habilidades, com cursos online, certificações e ferramentas interativas. A IA pode personalizar o conteúdo conforme o progresso do aluno, tornando o aprendizado mais eficaz e focado nas necessidades individuais.
