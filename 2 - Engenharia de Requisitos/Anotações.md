# Aulas

* [Aula 1 - Engenharia de Requisitos](#aula-1---engenharia-de-requisitos)
* [Aula 2 - Levantamento e Análise de Requisitos](#aula-2---levantamento-e-análise-de-requisitos)
* [Aula 3 - Requisitos funcionais, não funcionais ou como requisitos de domínio](#aula-3---requisitos-funcionais-não-funcionais-ou-como-requisitos-de-domínio)
* [Aula 8 - Medição da Qualidade dos Requisitos](#aula-8---medição-da-qualidade-dos-requisitos)

# Aula 1 - Engenharia de Requisitos

    A engenharia de requisitos trabalhar para entender problemas e apresentar soluções, trabalha no levantamento dos requisitos de um projeto para apresentar as soluções mais adequadas

    * Existe um diferença entre requisito e especificação

        * Requisito é a condição necessária para que se consiga atingir um objetivo

        * Especificaco é uma descrição detalhada, criteriosa das carcteristicas de um material

    e-licitação é um neologismo, que vem de e-liciar, que é voce apresentar um estimulo e aguardar uma resposta.

    Na engenharia de requisitos é e-licitado os requisitos a fim de encontrar uma solução.

    Engenharia de requisitos é chamado também de ERS

    * Nesse sentido a ERS é dívida em algumas etapas

        1. Levantamento inicial - onde se é levantado os requisitos inicias do projeto

        2. Análise - Onde é feito a analise dos requisitos para a viabiliade do sistema, onde os requisitos estão em uma documentação para distribuição entre os envolvidos

        3. Verificaco - Verificar se esta tudo dentro do que foi contratado pelo cliente

        4. Validação - Validar todos os itens e emitir uma garantir de qualidade, para no fim realizar o gerenciamento do requisito.

    * A ERS possui quatro fases principais

        1. Estudo da viabilidade - É algo rapido e barato, que diante da solicitação do cliente, é feito a analise do que foi pedido é viavel de ser realizado, mediante tecnologia, pessoas e processos.

        2. Levantamento de requisitos 

        3. Especificação dos requisitos

        4. Validação dos requisitos levantados

# Aula 2 - Levantamento e Análise de Requisitos

    O levantamento e análise de requisitos é iterativo, é um processo dinamico que necessita a revisitação, devido ao surgimento de novos requisitos.

    Estudo de viabilidade tecnica - É o estudo de que se o projeto pode ser realizado, mediante tecnologia, equipe e requisitos levatandos. Observados os custos e tempo de desenvolvimento.

    Levantamento e análise - Pode ser feito comparando o sistema a ser feito por um pronto, servindo de base para estimar o tempo e esforço de desenvolvimento. O usuário é muito importante nesse processo, ele tem opiniões e visões diferentes.

        * Analise de tarefas - É uma etapa que pode ser utilizada para validar o que o clientes esta querendo automatizar e melhorar com o sistema
        
        * Desenvolvimento de protótipos - Pode ser apresentado modulos para que o cliente valide e teste.

    A cada analise e iteração, uma documentação deverá ser criado e ajustada, de forma muito criteriosa, pois o sistema será feito em cima dessa documentação.

    Os requisitos são hierarquizados

        * A partir do momento de um requisitos gerado, deverá entrar numa hierarquia.
        
            1. Requisitos de negocio da empresa, são os requisitos base do sistema

            2. Requisitos do usuário, são requisitos que devem ser atendidos para utilização do usuário

            3. Requisitos de sistema, são requisitos que a aplicação utiliza para funcionar.

            4. Requisitos de software, são as caracteristicas especificas que o software oferece.
    
    Ao terminar de realizar o levantamento dos requisitos eles deverão ser transformados em um documento.

        1. Requisitos de usuário designam requisitos abstratos de alto nível. O primeiro requisito é o requisito de usuário, Eles são escritos em linguagem de alto nível, coloquial. Essa escrita tem que ser clara para cliente e dev

        2. Requisitos de sistema indicam a descrição detalhada do que o sistema deve fazer. Esse trecho do documento diz o que o software deve fazer, como fazer e como se comportar. Especificações comportamentais e não comportamentais. Essa escrita tem que ser clara, para dev e engenheiro

            * Se a especificação for rígida demais, logo impedirá o processo de criação

            * No entanto se for flexível, log dará margem para diversas interpretações

    A especificação é basicamente o contrato do sistema, que impede ao cliente quebrar clausula de contrato ou pedir algo que esta fora do escopo do sistema

# Aula 3 - Requisitos funcionais, não funcionais ou como requisitos de domínio

    Requisitos funcionais são suas ações principais, declarações de funções que o sistema deve fornecer

    Requisitos não funcionais são restrições sobre os serviços ou funções oferecidos pelo sistema.

    Requisitos de domínio são requisitos que se originam no domínio de aplicação do sistema e que reflete características desse domínio

# Aula 8 - Medição da Qualidade dos Requisitos

    Para medir a qualidade dos requisitos alguns pontos devem ser observados

        * Fidedignidade
        * Compreensibilidade
        * Maturidade
        * Testabilidade

    Os três principais criterios que devem ser observados são

        * Manutenibilidade:
            * Determinanr a consistencia
            * Contagem de comentarios
            * Complexidade
            * Modularidade
            * Tamanho e grau de complexidade
        
        * Portabilidade
            * Para determinar o grau de portabilidade deverá ser levado em consideração o acoplamento do código e da linguagem aos recursos de maquina ou arquitetura imposta
        
        * Confiabilidade
            * Erros acontecem e vão acontecer, a confiabilidade é "Capacidade que possui de identificar o erro e solucionar"