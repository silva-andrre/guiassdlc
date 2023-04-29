---
layout: default
title: Implementação
parent: Tecnologia e Processos
nav_order: 2.1.3
---

Nessa próxima etapa da esteira, nós começamos implementar ferramentas e processos que possam automatizar os testes necessários para garantir que todos os levantamentos das fases anteriores foram atendidos e que possíveis riscos e vulnerabilidades, sejam identificados antes mesmo do software se transformar em um produto funcional e entrar em produção. 

É aqui que vamos realizar nossas análises de código, nos preocupar em escolher e implementar uma ferramenta para gerenciar os riscos de segurança ao utilizar componentes de terceiros, também conhecido pela sigla *SCA (*Software Components Analysis), outra para realizar os testes de análise estática de segurança, conhecido pela sigla SAST (Static Analysis Security Testing) e uma para realizar os testes de análise dinâmica de segurança, conhecido pela sigla DAST (Dynamic Analysis Security Testing). 

Muito mais do que definir as ferramentas a serem utilizadas, precisamos ter em mente que é nesta fase que precisamos da conscientização dos times em adotar esses processos, ter uma cultura de segurança é muito mais difícil e abrangente do que adotar ferramentas, pois se os times não as utilizarem ou burlarem o processo para que as análises não aconteçam, de nada vai adiantar investir recursos para ter essas ferramentas, sejam elas pagas ou não. Ter em mente que hoje a maioria dos projetos de software são construídos utilizando componentes de terceiros (bibliotecas comerciais ou open source), possuir uma lista de ferramentas e softwares aprovados, que possam ser utilizados na construção desses sistemas é tão ou mais importante que a ferramenta em si. 

Como referência, sem posição ou inclinação nessa escolha, temos diversos fabricantes, ferramentas e projetos que buscam resolver essa dor e permitir que criemos escala em nosso processo, dentre elas e não se limitando, estão o Fortify, Acunetix, w3af, OWASP ZAP, BurpSuite, WebInspect, entre outros. 

Vale ressaltar que os testes de Segurança de Aplicações não se limitam aos citados neste tópico, temos também o RASP (Runtime Application Self-Protection), IAST (Interactive Application Security Testing) e MAST (Mobile Application Security Testing), podemos enxergar estes como uma evolução e complemento dos anteriores, sendo possível tirar o melhor dessas combinações conforme a maturidade do ambiente evolui e permite que a adoção de processos e ferramentas aconteçam com o intuito de trazer mais valor ao negócio e não somente como forma de aumentar os processos e não conseguir extrair o máximo de cada teste implementado. 

Quanto mais maduro for nosso processo de entrega contínua de software, melhor será para implementar ferramentas de segurança e evoluir o DevOps para o DevSecOps, aumentar a cultura das equipes com os aspectos de segurança e trazer para o conhecimento de todos os envolvidos nesse processo, qual a importância de nos preocuparmos com a cadeia de suprimentos e dependências dos nossos códigos, realizar testes recorrentes enquanto o software está sendo construído, ainda na fase estática e mais preocupado com o código em si e posteriormente quando começa se tornar funcional e podemos realizar testes dinâmicos, encontrando e trazendo para a superfície, problemas que podem rapidamente serem corrigidos ou riscos que devem ser endereçados para a melhor tratativa.
