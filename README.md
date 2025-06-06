# resumo-lab-dio-cloud
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO do bootcamp Computação em Nuvem com Azure.

### **☁️ Computação em Nuvem**
A computação em nuvem é um modelo em que serviços de tecnologia como armazenamento, processamento, softwares e redes são oferecidos pela internet. Com isso, empresas e usuários acessam esses recursos sob demanda, pagando apenas pelo que utilizam. Essa abordagem elimina a necessidade de manter infraestrutura física própria e permite mais flexibilidade, escalabilidade e acesso remoto.

Tipos de Nuvem:
- Nuvem Pública: oferecida por provedores para diversos clientes ao mesmo tempo.
- Nuvem Privada: criada e usada exclusivamente por uma única organização.
- Nuvem Híbrida: combinação de nuvem pública e privada, aproveitando os benefícios de ambas.

### **🖥️ Infraestrutura de TI**
Infraestrutura é o conjunto de elementos físicos e virtuais que sustentam os sistemas de TI de uma organização – como servidores, redes e armazenamento.

Modelos de Infraestrutura:
- On-premise (Local) 🏠: infraestrutura própria da empresa. Oferece controle total, mas exige altos custos com equipamentos e manutenção.
- Nuvem (Cloud) ☁️: recursos alugados de provedores como Azure, AWS ou Google Cloud. Permite escalar facilmente, reduzir custos e acessar tecnologias avançadas.
- Modelo Híbrido ⚙️: parte da infraestrutura permanece local, enquanto outras operações utilizam a nuvem. É mais flexível, mas exige gestão mais complexa.

### **🧰 Modelos de Serviço em Nuvem**
Os modelos de serviço definem o quanto de controle e responsabilidade o cliente terá sobre os recursos da nuvem:

- IaaS (Infrastructure as a Service): fornece infraestrutura básica como servidores, redes e armazenamento. O cliente gerencia o que será instalado e utilizado.
- PaaS (Platform as a Service): oferece uma plataforma pronta para o desenvolvimento de aplicativos, sem precisar cuidar da infraestrutura.
- SaaS (Software as a Service): entrega softwares prontos para uso direto pela internet (como e-mail, editores de texto etc.), com tudo gerenciado pelo provedor.

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
  
