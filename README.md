ATIVIDADE PROJETO ESTRUTURADO 11       

Prof. Carlos Eduardo Simões Pelegrin


Nome do acadêmico: Edson Gomes Nunes         
RA: 09011309


Tema da Atividade: Versionamento e Git     



1 - O que é o Git?
O Git é um projeto de código aberto maduro e com manutenção ativa desenvolvido em 2005 por Linus Torvalds, o famoso criador do kernel do sistema operacional Linux. (Todo o código do kernel era armazenado e versionado dentro do sistema BitKeeper, da empresa chamada BitKeeper, após haver um rompimento da parceria entre a BitKeeper e a Linux Fundation, Linus Torvalds, decide criar uma ferramenta para controle de versões dos arquivos do Linux, trazendo melhorias como velocidade, design simples, suporte robusto a desenvolvimento não linear (milhares de branches paralelos), totalmente distribuído e capaz de lidar eficientemente com grandes projetos como o kernel do Linix.)
Um número impressionante de projetos de software depende do Git para controle de versão, incluindo projetos comerciais e de código-fonte aberto. Os desenvolvedores que trabalharam com o Git estão bem representados no pool de talentos de desenvolvimento de software disponíveis e funcionam bem em uma ampla variedade de sistemas operacionais e IDEs (Ambientes de Desenvolvimento Integrado). 


Fonte: Udemy




2 - O que é versionamento de software?
Versionamento de software é um processo para o controle de versões que é realizado para o acompanhamento das numerações que se modificam a cada novo lançamento. A metodologia é útil para os programadores que estão sempre atentos às modificações realizadas nos softwares com o objetivo de propiciar o uso de ferramentas otimizadas.
Com o versionamento, números únicos são atribuídos a cada nova versão dos programas, hardwares, drivers, firmwares e arquivos. Sempre que uma atualização é implementada, a numeração aumenta para tornar possível a identificação da versão mais moderna.
Trata-se de um método classificatório adotado por profissionais especializados que controlam e acompanham os históricos de atualização dos softwares para visualizar mudanças. Isso precisa ser monitorado por que as atualizações interferem na performance dos programas.

Fonte: https://www.eveo.com.br/blog/versionamento-de-software/




3 - Por que utilizar o Git como controle de versionamento?
No Git podemos trabalhar de modo descentralizado de desenvolvimento, tendo uma arquitetura distribuída, o Git é um exemplo de DVCS (portanto, Sistema de Controle de Versão Distribuído). Em vez de ter apenas um único local para o histórico completo da versão do software, como é comum em sistemas de controle de versão outrora populares como CVS ou Subversion (também conhecido como SVN), no Git, a cópia de trabalho de todo desenvolvedor do código também é um repositório que pode conter o histórico completo de todas as alterações. 
Além de ser distribuído, o Git foi projetado com desempenho, segurança e flexibilidade em mente.

Fontes: https://woliveiras.com.br/                                                           
https://www.atlassian.com/br/git/tutorials/what-is-git



4 - Quais as vantagens do Git?
Desempenho 
As características brutas de desempenho do Git são muito fortes quando comparadas a muitas alternativas. Fazer o commit de novas alterações, branches, mesclagem e comparação de versões anteriores – tudo é otimizado para desempenho. 
Segurança
O Git foi projetado com a integridade do código-fonte gerenciado como uma prioridade. O conteúdo dos arquivos, bem como os verdadeiros relacionamentos entre arquivos e diretórios, versões, tags e commits, todos esses objetos no repositório do Git são protegidos com um algoritmo de hash de criptografia seguro chamado SHA1. Isso protege o código e o histórico de alterações contra alterações acidentais e maliciosas e garante que o histórico tenha rastreabilidade total.
Flexibilidade 
Um dos principais objetivos de design do Git é a flexibilidade. O Git é flexível em vários aspectos: suporte a vários tipos de fluxos de trabalho de desenvolvimento não lineares, em eficiência em projetos pequenos e grandes e em compatibilidade com muitos sistemas e protocolos existentes.



Fonte:https://www.hostgator.com.br



5 - Qual a importância da utilização do controle de versionamento no desenvolvimento de um software?
5 - Qual a importância da utilização do controle de versionamento no desenvolvimento de um software?
O software de controle de versão mantém registro de todas as modificações no código em um tipo especial de banco de dados. Se um erro for cometido, os desenvolvedores podem voltar no tempo e comparar versões anteriores do código para ajudar a corrigir o erro enquanto diminuem interrupções para todos os membros da equipe.
Desenvolvedores de software que trabalham em equipes estão sempre escrevendo novo código-fonte e modificando código-fonte existente. O código de um componente de projeto, aplicativo ou software é, no geral, organizado em uma estrutura de pasta ou "árvore de arquivos". Um desenvolvedor na equipe pode estar trabalhando em um novo recurso, enquanto outro desenvolvedor corrige um bug não relacionado, alterando o código; cada desenvolvedor pode fazer as alterações em várias partes da árvore de arquivos.
O controle de versão ajuda as equipes a solucionarem esses tipos de problemas, rastreando cada alteração individual feita por cada contribuinte e ajudando a evitar conflito com trabalhos simultâneos. As alterações feitas em uma parte do software podem ser incompatíveis com aquelas feitas por outro desenvolvedor trabalhando ao mesmo tempo.

Fonte: https://www.atlassian.com/br/git/tutorials/what-is-version-control



6 - Cite pelo menos três ferramentas de controle de versão e faça um breve detalhamento sobre cada uma delas.