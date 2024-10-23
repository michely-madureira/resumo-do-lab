### resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO, como o tema: Tipos de Serviço de Nuvem
___
# Três Principais Modelos de Serviço Da Computação Em Nuvem: 
A computação em nuvem distribui os recursos na forma de serviços e podem dividir em três cenários principais, de acordo com o nível de serviço oferecido. 
A diferença principal entre estes modelos está relacionada às responsabilidades dos atores envolvidos na computação em nuvem:
+ INFRAESTRUTURA COMO UM SERVIÇO (IaaS) - É um modelo de serviço de nuvem que permite ao usuário utilizar recursos de infraestrutura sob demanda, como armazenamento, virtualização e rede. 
Nesse cenário, os serviços de virtualização e rede são fornecidos pelo provedor, enquanto o usuário cuida do sistema operacional, dos aplicativos e dados. 
Exemplos desse tipo de serviço incluem o serviço de máquinas virtuais do Azure. 
Diferença: No IaaS, o usuário é responsável por gerenciar tudo, aplicativos, middleware, sistemas operacionais e máquinas virtuais. 
O provedor de serviço é responsável por manter a infraestrutura do datacenter que hospedará as máquinas virtuais dos usuários. 
Logo, a IaaS requer o máximo de gerenciamento do usuário entre os serviços da nuvem.

+ PLATAFORMA COMO UM SERVIÇO (PaaS) – É um tipo de modelo de serviço de computação em nuvem que oferece uma plataforma de nuvem flexível e escalonável para desenvolver, implantar, executar e gerenciar apps. 
Nesse cenário, o usuário tem todas as ferramentas necessárias para criar aplicativos, as necessidades de software, hardware, rede e sistemas operacionais são atendidas pelo provedor de serviços. 
Diferença:  No PaaS, a responsabilidade do usuário diminui e aumenta a do provedor. O provedor é responsável por entregar todos os recursos de hardware e software necessários para que o usuário possa construir seus aplicativos. O código e os dados gerados pela aplicação são responsabilidade do usuário. 
Logo, a PaaS requer menos gerenciamento do usuário.

+ SOFTWARE COMO UM SERVIÇO (SaaS): É um modelo que permite aos usuários se conectar e usar aplicativos baseados em nuvem pela internet, como e-mail, serviços de armazenamento, entre outros. 
Nesse cenário, as necessidades de computação e armazenamento são atendidas pelo provedor de serviços em nuvem, o usuário só precisa fazer upload e baixar dados. 
Manutenção, tempo de inatividade, atualização e segurança são atendidos pelo provedor de serviços. 
Diferença: O SaaS é aquele com o qual o usuário tem menor responsabilidade, bastando apenas se conectar aos aplicativos disponibilizados e utilizar. O provedor de serviços é o que tem maior responsabilidade. Ele é responsável por gerenciar toda a pilha de aplicativos, desde o hardware, passando pelos sistemas operacionais, até o aplicativo. 
Logo, o SaaS requer o mínimo de gerenciamento do usuário.
___
# Modelo de Responsabilidade Compartilhada
+ Em modelos on-premise a organização tem total responsabilidade sobretudo (estrutura, equipamentos, segurança física e logica, atualizações, etc);
+ No modelo de responsabilidade compartilhada, a responsabilidade é compartilhada com o provedor de nuvem.
+ Toda estrutura física passa a ser responsabilidade do provedor de nuvem;
+ O cliente se responsabiliza, com: toda gestão de dados e tudo que é armazenado na nuvem, bem como, será responsável por toda segurança de acesso, login de usuários, autenticação, autorização.
+ Ao transferir os serviços para a nuvem as responsabilidades mudam e o modelo dependerá de tipos de serviço de nuvem adotado como: **IaaS (infraestrutura como serviço)**, **PaaS (plataforma como serviço)** e **SaaS (software como serviço)**.
+ O cliente sempre será responsável pelas informações e dados armazenados na nuvem (como bancos de dados e documentos), assim como pelos dispositivos e suas permissões para acesso por meio dela (telefones celulares, computadores e assim por diante) e por contas e identidades como pessoas, serviços e dispositivos em sua organização. 
+ Já o provedor de nuvem é sempre responsável pelo datacenter físico, rede física e lógica e pelos servidores (hosts físicos).
+ O modelo de serviço escolhido pelo cliente (empresa) determinará a responsabilidade por itens como: sistemas operacionais, controles de rede, aplicativos, identidade e infraestrutura.
