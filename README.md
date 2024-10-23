### resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO, como o tema: Componentes de Arquitetura do Azure
# Componentes de Arquitetura do Azure
Os datacenters são a base da infraestrutura física da plataforma Azure e estão distribuídos globalmente para oferecer serviços de computação em nuvem.
+ **Regiões do Azure:** São áreas geográficas que contêm datacenters do Microsoft Azure, garantindo que os dados e as cargas de trabalho estejam próximos aos usuários finais para reduzir a latência. Cada região assegura que os dados residam na localidade especificada.

+ **Zonas de Disponibilidade (AZ):** São datacenters fisicamente separados, mas interconectados, dentro da mesma região. Cada zona tem infraestrutura independente de energia, refrigeração e rede, garantindo a continuidade do serviço mesmo se uma zona ficar indisponível. 

+ **Pares de Regiões:** São regiões geograficamente separadas, mas em proximidade suficiente para proporcionar redundância e resiliência. O emparelhamento de regiões reduz o impacto de desastres naturais ou eventos adversos, permitindo a migração de serviços para a região parceira em caso de necessidade. 

+ **Regiões Soberanas:** São um conjunto de localizações geográficas em que a Microsoft oferece seus serviços de nuvem. O conceito de "soberania" aqui refere-se ao controle de dados e serviços dentro de uma determinada jurisdição, atendendo a requisitos legais e regulatórios específicos de cada país ou região. Essas regiões são projetadas para garantir que os dados sejam armazenados e processados em conformidade com as leis locais, o que é especialmente importante para organizações que precisam proteger informações sensíveis ou que operam em setores regulamentados.

+ **Recursos do Azure:** São componentes individuais que podem ser provisionados e gerenciados no Microsoft Azure, como: **máquinas virtuais**, **contas de armazenamento**, **redes virtuais**, **serviços de aplicativos**, *bancos de dados** e **funções**. Todos esses são recursos que, precisam estar obrigatoriamente em um grupo de recursos.

+ **Grupos de Recursos:** São contêineres lógicos que servem para organizar e gerenciar os recursos do Azure de forma coletiva. Cada recurso criado deve ser associado a um único grupo de recursos. Um recurso pertence exclusivamente a um grupo de recursos, mas pode ser movido entre grupos. Porém não é possível aninhar grupos de recursos (colocar dentro de outro). Os grupos de recursos foram criados para a organização dos recursos e normalmente são organizados por setor, região ou empresas. Ao aplicar uma política ou ação a um grupo de recursos, essa ação será aplicada a todos os recursos contidos nesse grupo.
 ### Assinaturas do Azure
As assinaturas do Azure desempenham um papel crucial no gerenciamento, cobrança e escalabilidade dos recursos na plataforma.
+ Objetivo: Permitem a organização lógica dos recursos, facilitando a gestão e cobrança precisa do que está sendo utilizado.
+ Necessidade de Assinatura: Sem uma assinatura, não é possível criar ou gerenciar recursos no Azure.
+ Uma conta pode ter diversas assinaturas e um único responsável, mas uma assinatura só pode estar associada a uma única conta. 
+ **Acesso Autenticado e Autorizado:** As assinaturas fornecem acesso autenticado e autorizado aos serviços do Azure. Ao criar uma assinatura, ela pode ser associada à conta do Azure, que é uma identidade no Azure Active Directory.
+ **Tipos de Limites de Assinatura:**
1.	Limite de Cobrança: Define requisitos de cobrança com base no tipo e quantidade de assinaturas realizadas pelo uso da conta do Azure.
2.	Limite de Controle de Acesso: São políticas de gerenciamento de acesso no nível da assinatura da conta Azure, permitindo criar assinaturas separadas para refletir diferentes estruturas organizacionais.

+ **Grupos de gerenciamento:** Grupos de gerenciamento podem incluir várias assinaturas do Azure. As assinaturas herdam as condições aplicadas ao grupo de gerenciamento.
