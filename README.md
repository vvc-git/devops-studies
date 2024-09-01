
## o que é DevOPS?

**Uma cultura de ferramentas para aumentar capacidades de desenvolver e entregar softwares.**

É uma **cultura** para impulsionar a integração entre times de desenvolvimento e administradores de sistema (sysadmins).

Isso é importante porque muitas vezes esses dois times trabalham de forma antagônica. Enquanto os desenvolvedores estão preocupados em produzir novas funcionalidades rapidamente (gerando instabiilidade) e os sysadmin querem gerenciar a infraestrutura (mantendo a estabilidade do sistema).

Dev representaria o lado de desenvolvimento, e Ops a **operação** e sustentação.

## Melhore práticas DevOPS

1. Arquitetura de microserviços:  Desacopla  sistemas  grandes  e  complexos  e  os transforma  emsistemas  menores  e  independentes.
    
    Os  sistemas  são  divididos  em vários serviços individuais, e cada um delesabrange uma função única do negócio, além de ser operado independentemente dos serviços de mesmo nível e do sistema como um todo.
    
2. Integração contínua:  Prática  de  desenvolvimento  que  permite  a **execução  dos  testes**  sempre  que  as  alterações  de  código  são  enviadas  para  o repositório central.  
3. Infraestrutura com código: A   infraestrutura   como   código   é   uma   prática   que   utiliza   técnicas   de desenvolvimento de código e que permite controle de versão e integração contínua da  infraestrutura, por  meio de  API, para  que  os  desenvolvedores  e  sysadmins trabalhem com a infraestrutura de modo programático, em vez de instalar e configurar manualmente a infraestrutura.
4. Monitoramento, Alarme, Log e Idexação: Ao  capturar,  indexar  e  analisar  os  logs gerados  pelos   aplicativos  e  pela   infraestrutura,  é   possível  entender   como  as alterações  ou  atualizações  estão  afetando  o  ambiente  e  seus  usuários,  o  que proporciona  maisfacilidade  na  rastreabilidade,  fornecendo  maior  esclarecimento sobre  as  causas  raiz  dos  problemas.

## Estágios e ferramentas.

| Etapa             | Ferramenta                                                                                                                                                                |
|-------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Planejamento      |                                                                                                                                                                           |
| Desenvolvimento   | Git                                                                                                                                                                       |
|                   | **Jira**: Organizar atividades do time (parece um Trello mais robusto)                                                                                                        |
|                   | Confluence: Para documentação colaborativa do sistema                                                                                                                     |
| Build (Construção)| Apache Maven: Realiza a automação da compilação do código e gerenciamento das dependências.                                                                               |
|                   | Processo no qual o código e dependências do software e da infraestrutura são baixados do repositório central, compilados e fechados em uma versão, que será disponibilizada para os testes. |
| Teste             | **JUnit**: Para testes unitários de código                                                                                                                                    |
| Release (Entrega) | **Jenkins** e CodeShip: Ferramentas de pipeline de entrega, que suportam integração e entrega contínua                                                                         |
| Deploy (Implantação)| **Docker**: Encapsula o software em um contêiner com tudo o que é necessário para ser executado                                                                             |
| Operação          | **Kubernetes** e Apache Mesos: Sistemas de orquestração de contêineres open source que automatizam a implantação. Possuem funcionalidades de balanceamento de carga (load balance), para distribuir a carga de trabalho uniformemente entre os containers. |
| Monitoração       | Nagios: Fase em que é feito o acompanhamento do ambiente em tempo real para análise de performance, comportamentos da aplicação e usuário, troubleshooting (análise de problemas), entre outros.|

![img](Resumo%20de%20DevOPS%204c05e2be9e534882a97dcfb81cc4cad0/Untitled.png)

