# resumo-lab-dio-cloud
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO do bootcamp Computação em Nuvem com Azure.

### **☁️ Cloud Computing (Computação em Nuvem)**

A **computação em nuvem** é um modelo de entrega de **serviços de tecnologia** em que recursos como **armazenamento**, **processamento de dados**, **software**, **redes** e muito mais são fornecidos pela internet, em vez de ficarem em servidores e data centers próprios. Com a nuvem, empresas e usuários podem acessar e utilizar esses recursos sob demanda, pagando apenas pelo que utilizam. Isso elimina a necessidade de investir em **infraestrutura física** cara e difícil de manter. A computação em nuvem permite **escala**, **flexibilidade** e **agilidade**, além de possibilitar o acesso a esses recursos de qualquer lugar e a qualquer momento. Os principais tipos de nuvem incluem a **pública**, a **privada** e a **híbrida**, cada uma com suas características e aplicações específicas.

### **⚙️ O que é Infraestrutura?**

Infraestrutura refere-se ao conjunto de recursos físicos ou virtuais necessários para o funcionamento de sistemas de TI. Inclui servidores, redes, armazenamento, e outras tecnologias essenciais para suportar aplicativos e operações de uma organização. Modelos de infraestrutura podem variar entre on-premise, cloud, ou híbrida, dependendo das necessidades e estratégias da empresa.

- **🏢💻 On-Premise (Local)**
    
    O modelo **on-premise** refere-se à **infraestrutura física** e aos sistemas de **TI** que são instalados, mantidos e gerenciados dentro das instalações da própria empresa, ou seja, em um **data center local**. Nesse modelo, todas as operações e dados ficam sob o **controle total** da empresa, que é responsável pela compra, manutenção e operação de **servidores**, **software**, **rede** e outros recursos. Apesar de oferecer maior **controle** e **segurança** (pois os dados ficam dentro da empresa), o modelo on-premise exige **investimentos altos** em equipamentos, espaço físico e mão de obra especializada para manutenção.

- **☁️🌐 Modelo Cloud (Nuvem)**
    
    O **modelo cloud** (ou modelo de nuvem) é uma **infraestrutura baseada na internet**, onde a empresa ou o usuário utiliza **recursos de TI** de um provedor externo. Em vez de ter servidores, bancos de dados e outros sistemas dentro de suas instalações, as empresas **alugam** esses serviços de **fornecedores de nuvem**, como **Amazon Web Services (AWS)**, **Microsoft Azure** ou **Google Cloud**. Isso permite a **escalabilidade**, ou seja, é possível aumentar ou diminuir a capacidade dos serviços de acordo com a necessidade, sem a necessidade de investir em infraestrutura própria. Além disso, o modelo de nuvem permite **reduzir custos**, melhorar a **agilidade** e **acessar serviços avançados** que seriam difíceis de implementar localmente.

- **🌍🔗 Modelo Hybrid (Híbrido)**
    
    O modelo **híbrido** combina os benefícios dos modelos **on-premise** e **cloud**. Nesse caso, uma empresa mantém parte de sua infraestrutura local, enquanto usa **serviços de nuvem** para outras operações, criando uma combinação de **recursos internos e externos**. Por exemplo, uma empresa pode manter dados sensíveis em servidores próprios (on-premise) e, ao mesmo tempo, usar a nuvem para hospedar aplicativos ou serviços que exigem mais escalabilidade. O modelo híbrido oferece **flexibilidade**, permitindo que as empresas escolham o que é melhor em cada situação. No entanto, esse modelo também exige **gestão mais complexa**, pois é necessário integrar e monitorar tanto a infraestrutura local quanto os recursos na nuvem.

### 🛠️ **O que são os Modelos de Serviço em Nuvem?**

**Definição**: Modelos de serviço em nuvem definem o nível de controle que a empresa tem sobre a infraestrutura e os serviços fornecidos pelo provedor de nuvem. Eles ajudam a escolher a solução mais adequada às necessidades do negócio, podendo envolver diferentes níveis de abstração e responsabilidades.

🌟 **Golden Rules**: Regras universais para escolher e implementar os modelos de serviço com base nas necessidades de controle, custo e escalabilidade.
Exemplo: "Escolha o modelo de serviço adequado conforme o nível de controle necessário."

🏠 **House Rules**: Regras específicas para cada organização com base em sua arquitetura e objetivos. Exemplo: "Para aplicativos mais complexos, prefira PaaS para abstração e gerenciamento facilitado."

- 🎨 **IaaS (Infrastructure as a Service)**
**Definição**: IaaS oferece infraestrutura de TI básica como serviço, fornecendo recursos como servidores virtuais, armazenamento, redes e outros componentes essenciais de TI, com base em uma cobrança por uso.

- 🎨 **PaaS (Platform as a Service)**
**Definição**: PaaS oferece uma plataforma de desenvolvimento completa na nuvem, permitindo que os desenvolvedores construam, testem e implementem aplicativos sem se preocupar com a infraestrutura subjacente.

- 🎨 **SaaS (Software as a Service)**    
**Definição**: SaaS entrega software e aplicações completas pela nuvem, sendo acessadas via internet, sem necessidade de instalação ou manutenção local. O provedor cuida de tudo, desde a infraestrutura até as atualizações do software.

📌 Modelo de responsabilidade compartilhada: 
Explica o que é responsabilidade do provedor e do cliente (segurança, sistema operacional, aplicativos, dados etc.).

### **💰 Modelos de Custos**
- **CapEx (Capital Expenditure):** Gasto inicial com hardware e infraestrutura física. Depreciação ao longo do tempo.
- **OpEx (Operational Expenditure):** Gasto com produtos e serviços conforme necessidade. Cobrança imediata, sem grandes investimentos iniciais.

### **✅ Benefícios da Nuvem**
- Alta disponibilidade e confiabilidade
- Elasticidade (aumentar/reduzir recursos conforme necessário)
- Escalabilidade (suportar aumento de carga)
- Segurança, governança e previsibilidade de custos
- Gerenciabilidade simplificada com ferramentas automatizadas

### **🌐 Componentes da Arquitetura do Azure**

**🔹 Regiões**
- Mais de 60 regiões globais (ex: Leste dos EUA, Sudeste do Brasil), compostas por um ou mais datacenters próximos.

**🔹 Zonas de Disponibilidade**
- Isolamento físico (energia, rede, refrigeração)
- Alta resiliência contra falhas de datacenter

**🔹 Pares de Regiões**
- Pelo menos 300 milhas de separação
- Replicação automática para alguns serviços
- Atualizações distribuídas para minimizar falhas

**🔹 Regiões Soberanas**
- Azure Government (EUA): segurança e conformidade para órgãos federais
- Azure China: operação separada, em parceria com 21Vianet, dados mantidos na China por exigência regulatória

**🔹 Recursos do Azure**
- Elementos como máquinas virtuais, redes, storage etc., usados para montar soluções em nuvem.

**🔹 Grupos de Recursos**
- Contêiner lógico para gerenciar recursos de forma agrupada
- Um recurso pertence a um grupo por vez, mas podem estar em diferentes regiões
- Recursos podem ser movidos entre grupos

**🔹 Assinaturas**
- Controle de acesso e limites de cobrança
- Pode haver múltiplas assinaturas sob uma mesma conta

**🔹 Grupos de Gerenciamento**
- Estrutura hierárquica que organiza múltiplas assinaturas
- Suporte a 10.000 grupos e até 6 níveis de profundidade

### **💾 Armazenamento no Azure**
**🔹 Tipos de Serviço**
- Blob Storage: arquivos não estruturados (imagens, vídeos)
- File Storage: compartilhamento de arquivos (semelhante a SMB)
- Queue Storage: mensagens entre componentes
- Table Storage: dados NoSQL

**🔹 Redundância**
- LRS (Local Redundant Storage): cópias na mesma região
- GRS (Geo-Redundant Storage): cópias em regiões diferentes
- RA-GRS: leitura permitida da réplica secundária

**🔹 Camadas de Acesso**
- Hot: acesso frequente
- Cool: acesso esporádico
- Archive: armazenamento de longo prazo

**🔹 Ferramentas e Migração**
- AzCopy: ferramenta de linha de comando para movimentação de arquivos
- Storage Explorer: ferramenta gráfica para gerenciamento
- Azure File Sync: sincronização entre servidores locais e nuvem
- Azure Data Box: dispositivo físico para migração de grandes volumes (até 80 TB)
  
