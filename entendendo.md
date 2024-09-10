# Atividade individual


## Qual a distinção entre sistemas em geral e sistemas de software?
A resposta desta questão parte das duas definições. 

Sistema em geral, pela definição, se refere a união das partes de algo no intuito de se ter um funcionamento final interconectado dessas partes.

Sistema de software, de forma similar e específica, se refere a união de inúmeros softwares, componentes, hardwares, governanças, entidades e pessoas de forma a operar de forma conjunta, complexa e de acordo com as vontades daquelas partes interessadas. 

Assim, a distinção reside na especificidade, complexidade e magnitude do sistema. Assim, a distinção clara é o entendimento da divisão das partes, em componentes no caso do software e outros elementos no caso geral, para a construção do sistema.


## Qual a distinção entre o conceito de projeto no contexto de gerenciamento de projetos (project management) e para o contexto de design de software?
Em gerenciamento de projetos, entende-se como projeto "um esforço temporário empreendido para criar um resultado único". Assim, aborda-se no gerenciamento de projetos a organização das atividades e tarefas em um contexto conhecido, baseado em modelos e boas práticas, para que o resultado seja obtido. 

Design de software parte desse princípio de organização e avança através da divisão das partes, com critérios claros, para que o problema seja entendido pela equipe técnica de software. Assim, com a divisão racional, sistemática e registrada, que se amplia o entendimento daquilo que varia e os relacionamentos das partes para se ter de fato a arquitetura e o design de software.

Para o design de software, o elemento principal para essa divisão é identificar o que varia no sistema. Outros critérios incluem os fluxogramas, os atributos de qualidade, as regras de negócio e relacionamentos das partes e todas as restrições associadas a cada critério. O ponto de partida, para qualquer um desses critérios, é "tudo o que variar precisa ser isolado", e sobre isso deve-se dividir o software em componentes e analisar os requisitos arquiteturalmente relevantes (geralmente requisitos de qualidade), identificar oportunidades de design patterns, princípios SOLID e demais aspectos de design. 

A divisão por fluxograma, por exemplo, é um péssimo método para problemas que escalam. Um critério de medição é 5000 linhas de código. Menos que isso o uso de fluxograma pode ser adequado. Acima disso definitivamente é inadequado.


## A norma ISO/IEC/IEEE 12207:2017 possui um processo específico para projeto (design) de software? Se afirmativo, qual seria esse processo?
Sim, processo descrito na seção 6.4.5 Processo de Definição de Design. A título de informação a ISO 12207:2021 foca em processos de software, inclusive o Processo de Design de Software na seção 6.4.5. O custo dela, na ISO (disponível em https://www.iso.org/standard/63712.html, consultado em 10/9/2024), é de USD $255.03.


## Se você fosse comprar essa norma (42010:2022), quanto custaria?
O custo dela, na ISO (disponível em https://www.iso.org/standard/74393.html, consultado em 10/9/2024), é de USD $229.05. Ela foca em registros das descrições arquiteturais (partes interessadas, decisões, visões, preocupações, estilos e padrões arquiteturais). 


## Compreenda o objetivo da ISO/IEC/IEEE 25010:2011.
A ISO 25010:2011 foca em atributos de qualidade, identificação, análise e avaliação. São eles que determinam a utilidade e sucesso de um sistema de software, e que permitam do sistema de software contra possíveis danos de reputação agora e no futuro.

Ela foi substituída pela edição 25002:2024, 25010:2023 e 25019:2023. O custo dela, na ISO (disponíveis em https://www.iso.org/standard/78175.html, https://www.iso.org/standard/78176.html e https://www.iso.org/standard/78177.html, consultados em 10/9/2024), são de USD $113.35, USD$178.28 e USD$152.31 respectivamente. Os atributos de qualidades são aspectos que orientam a descrição arquitetural de software e posteriormente o design de software.


## Para que servem as normas acima? Na ausência delas, quais seriam os incovenientes? Ligue o conteúdo dessas normas com a noção de design de software.
As normas 12207, 41010 e 25010 apresentam processos de design, atividades, tarefas e resultados de design, e aspectos de requisitos e avaliação de qualidade de sistemas de softwares para se ter um entendimento sobre o projeto de sistema de software universal no planeta. A sua ausência é a semente do caos por promover as falhas de comunicação, registros e padronização entre as várias formas de se projetar sistemas de software.


