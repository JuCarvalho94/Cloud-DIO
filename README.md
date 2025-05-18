# Cloud-DIO
Aulas do curso 

**Aula 1 - Como a Computação em Nuvem Funciona**
As máquinas de processamento não estão no local, é um serviço acessado na internet, então este armazenamento/processamento é feito no ambiente cloud (na nuvem).
**On premise:** quando a máquina fica na empresa.
**Ambiente cloud:** quando a máquina fica em outro lugar e o acesso é pela internet (infra as a service - Iaas).
**Hybrid model:** mescla os dois modelos, pode acontecer quando a demanda é sazonal.
Dependendo de onde fica o servidor haverá uma latência para o processamento, ou seja, um delay, por isso as empresas que fornecem esse tipo de serviço normalmente tem pontos com servidores em várias partes do mundo, para fornecer uma maior velocidade de comunicação.
**Region:** lugares no mundo onde você vai encontrar conjuntos de máquinas para alugar (Iaas).
**Zonas:** diferentes áreas dentro das regions.

**Aula 2 - Introdução aos conceitos básicos do Microsoft Azure**
**O que é computação em nuvem?**
É o fornecimento de serviços de computação pela internet, habilitando inovações mais rápidas, recursos flexíveis e economias de escala.

**Tipos de nuvem:**
**Nuvem privada:** quando o ambiente é 100% on-premise, ou seja, a organização cria um ambiente em nuvem em seu datacenter e é responsável por operar os serviços que fornece, não dando acesso aos usuários de fora da organização.
**Nuvem pública:** disponível para quem quiser e puder pagar, ou seja, pertencente a servidores de nuvem ou provedor de hosting, que fornece recursos e serviços a várias organizações e usuários. É acessada via conexão de rede segura, geralmente pela internet.
**Nuvem híbrida:** quando a organização utiliza a nuvem privada e pública, podendo até ter uma comunicação entre os servidores.
**Multi Cloud:** quando a organização utiliza mais de um tipo de cloud. Ex: datacenter próprio, Microsoft e AWS.

**Comparação de modelos de nuvem:**
**Nuvem pública:** nenhuma despesa de capital para escalar verticalmente; os aplicativos podem ser provisionados e desprovisionados rapidamente; as organizações pagam apenas pelo que utilizam.
**Nuvem privada:** as organizações têm controle total sobre os recursos e segurança, além de serem responsáveis pela manutenção e pelas atualizações do hardware.
**Nuvem híbrida:** as organizações determinam onde ficam seus aplicativos, controlam a segurança, a conformidade e os requisitos legais; fornece maior flexibilidade.

**Comparar CapEx x OpEx:**
**Despesas de capital (CapEx):** o gasto inicial de dinheiro em infraestrutura física, essas despesas têm um valor que se reduz com o tempo.
**Despesas operacionais (OpEx):** gastar com produtos e serviços conforme necessário, pagamento conforme o uso; talvez seja cobrado imediatamente.
**Modelo baseado em consumo:** os provedores de serviços em nuvem operam em um modelo baseado no consumo, o que significa que os usuários finais pagam somente pelos recursos que usam. Com isso, é possível ter melhor previsão de recursos, são fornecidos preços para recursos e serviços individuais, e a cobrança é feita com base no seu uso real.

**Aula 3 - Benefícios da Computação em Nuvem**
**Domínio do objetivo:** descrever os benefícios da alta disponibilidade, escalabilidade, confiabilidade, previsibilidade, segurança, governança e capacidade de gerenciamento da nuvem.

**Alta disponibilidade:** recursos disponíveis sempre que necessário, serviços entregáveis; se concentra em garantir a disponibilidade máxima, independente de interrupções ou eventos que possam ocorrer
**Escalabilidade:** refere-se à capacidade de ajustar recursos para atender à demanda; a capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda; outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços, como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa, e se a demanda cair, você poderá reduzir seus recursos e assim reduzir seus custos; com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual.
**Elasticidade:** com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente); você pode adicionar máquinas virtuais ou contêineres por meio da expansão, da mesma forma, se houver queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).
**Confiabilidade:** devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente; com um design descentralizado, a nuvem permite que você tenha recursos implantados em várias regiões do mundo; com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento.
**Previsibilidade:** permite que você avance com confiança, seja no desempenho ou no custo, ambas são influenciadas pelo Microsoft Azure Well-Architected Framework.
**Segurança:** a nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente; se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e software instalado, incluindo aplicação de patches e manutenção; se vocÊ quiser a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem para você.
**Governança:** a auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com seus padrões corporativos e fornece estratégias de mitigação; dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e segurança; ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.
**Gerenciabilidade:** um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento, há dois tipos de capacidade de gerenciamento para computação em nuvem que você aprenderá nesta série e ambos trazem excelentes benefícios; o gerenciamento da nuvem diz respeito a gerenciar seus recursos de nuvem, por exemplo, escalar automaticamente a implantação de recursos com base na necessidade, por meio de um portal da web, usando uma interface de linha de comando, usando APIs ou usando o PowerShell; implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
