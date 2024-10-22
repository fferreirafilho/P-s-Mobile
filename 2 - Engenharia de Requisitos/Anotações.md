# Aulas

* [Aula 1 - Engenharia de Requisitos](#aula-1---engenharia-de-requisitos)
* [Aula 2 - Levantamento e Análise de Requisitos](#aula-2---levantamento-e-análise-de-requisitos)
* [Aula 3 - Requisitos funcionais, não funcionais ou como requisitos de domínio](#aula-3---requisitos-funcionais-não-funcionais-ou-como-requisitos-de-domínio)
* [Aula 8 - Medição da Qualidade dos Requisitos](#aula-8---medição-da-qualidade-dos-requisitos)
* [Aula 9 - Requisitos de rastreabilidade bidirecional](#aula-9---requisitos-de-rastreabilidade-bidirecional)
* [Aula 10 - Requisitos não-funcionais: requisitos de produtos](#aula-10---requisitos-não-funcionais-requisitos-de-produtos)
* [Aula 11 - Requisitos de usuário](#aula-11---requisitos-de-usuário)
* [Aula 12 - Requisitos de Sistema ](#aula-12---requisitos-de-sistema)
* [Aula 13 - Linguagem Natural Estruturada](#aula-13---linguagem-natural-estruturada)
* [Aula 14 - Especificação de requisitos usando PDL](#aula-14---especificação-de-requisitos-usando-pdl)
* [Aula 15 - Análise de problemas](#aula-15---análise-de-problemas)
* [Aula 16 - Especificação de Requisitos de Software (ERS)](#aula-16---especificação-de-requisitos-de-software-ers)
* [Aula 17 - Análise de requisitos orientada a objetos](#aula-17---análise-de-requisitos-orientada-a-objetos)
* [Aula 18 - Especificação genérica](#aula-18---especificação-genérica)
* [Aula 19 - Dicionário de dados](#aula-19---dicionário-de-dados)
* [Aula 20 - Especificação do processo](#aula-20---especificação-do-processo)
* [Aula 21 - Estudos de viabilidade](#aula-21---estudos-de-viabilidade)
* [Aula 22 - Levantamento e análise de requisitos](#aula-22---levantamento-e-análise-de-requisitos)

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

# Aula 9 - Requisitos de rastreabilidade bidirecional
    
    Quando é determinado os requisitos do projeto, ele tem uma origem que pode ser

        1. Necessidade da Aplicação
        
        2. Necessidade do usuário

        3. Imposição Legal

        4. Imposição Cliente

    Quando a analise do requisto é feito, deve ser determinado dois caminhos

        1. Caminho ascendente: Do requisito até quem o originou

        2. Caminho descendente: De quem originou até o requisito ou do requisito até quem ele influência
    
    Para realizar o rastreamento é necessário na documentação numerar os requisitos e adicionar um numero de origem

    Os principais resultados da analise de requisitos sao:

        * **Funcional**(ações principais): identifica as atividades do sistema;
        * **Comportamental**(atividades de controle): descreve a sequência e a possível sobreposição das funções do ssitema em uma hierarquia de atividades de controle;
        * **Não-comportamental**(Atributos): inclui o planejamento de engenharia humana e de garantia de qualidade  

# Aula 10 - Requisitos não-funcionais: requisitos de produtos

    * Requisitos não funcionais podem ser dividos em três

        1. Requisitos relativos ao produtos - Dizem respeito ao comportamento do produto, "Como ele faz".
            * Velocidade de Operação
            * Espaço mínimo memoria exigido
            * Confiabilidade
            * Taxa aceitavel de falhas
            * Portabilidade

        2. Requisitos organizacionais - Tem haver com a cultura da empresa que solicitando o sistema
            * Padrões de processos
            * Cultura organizacional
            * Linguagem de programação - Levar em consideração a stack da sua empresa que voce trabalha

        3. Requisitos externos - Exigencias ambientais que influênciam no sistema
            * Interoperabilidade
            * Requisitos Legais
            * Regras de Compliance
            * Raestrabilidade

    * Os requisitos de dominio são : São aqueles derivados do domínio da aplicação, em vez de serem obtidos a partir das nacessidades específicas dos usuários do sistema.

# Aula 11 - Requisitos de usuário

    Requisitos de usuários devem ser especificados para o cliente em linguagem humana, pode utilizar graficos, planilhas, o que quiser, para melhor descrever o sistema, mas apenas comportamentos externos do sistema.

    Alguns erros podem acontecer durante a escrita de requisitos de usuário.

        * Falta de Clareza

        * Confusão em relação aos requisitos

        * Fusão de Requisitos


    É boa pratica separar o requisitos de usuário os requisitos mais detalhados do sistema, em um documento específico de requisitos

# Aula 12 - Requisitos de Sistema 

    Requisitos do sistema são instruções detalhadas do sistema, ele provavelmente será utilizado como item do contrato.

    Podem servir como base para um contrato destinado à implantação do sistema e, portanto, devem ser uma especificação completa e consistente de todo o sistema

    O relatorio de requisitos do sistema, deve possuir linguagem tecnica das instruções do sistema.

    Uma arquitetura inicial do sistema pode ser definida para ajudar a estrutura a especificação de requisitos.

    A compreensão da linguagem natural depende do uso das mesmas palavras para o mesmo conceito, pelos leitores e por quem escreve as especificações

# Aula 13 - Linguagem Natural Estruturada

    A linguagem natural estrutura é uma forma restrita da linguagem natural, que se destina a escrever requisitos de sistema

    Sua vantagem é que ela mantém a maior parte da facilidade de expressão e compreesão da linguagem natura, mas também garante que algum grau de uniformidade seja imposto à especificação

    As notações de linguagem estruturada podem limitar a terminologia utilzada e usar templates para especificar os requisitos de sistema

    A especificação pode ser estruturada em torno dos objetos manipulados pelo sistema, das funções realizadas ou dos eventos por ele processados

    Quando é utilizado um formulario padronizado voce fazer um
    
        1 - Descrição da função ou entidade que esta sendo especificada.
        
        2 - Descrição de suas entradas e de onde elas se originam

        3 - Descrição de suas saidas e para onde elas prosseguirão

        4 - Se uma abordagem funcional for uitilizada, será "chamada" uma pré condição estabelecendo o que deve ser verdadeiro antes da função

        5 - Descrição dos efeitos colaterais (se existirem) da operação

# Aula 14 - Especificação de requisitos usando PDL

    PDL significa (Linguagem de Descrição de Programa)

    PDL é uma linguagem derivada de linguagem de programação Java ou Ada, que pode conter princípios mais abstratos, adicionais, para aumentar o poder de expressão

    Omissões e inconsistências de requisitos podem ser inferidas a partir do resultados dessas especificações

    A aplicabilidade da PDL é melhor em dois casos

        1 - Quando a operação é especificada com consequência de ações mais simples e a ordem de execução é fator importante.

        2 - Quando interfaces de hardware e software tiverem de ser especificadas

    Existem pelo menos três desvantagens ao usar PDL

        1 - A linguagem utilizada para escrever a especificação pode não ser suficientemente expressiva para descrever a funcionalidade do sistema

        2 - A notação só é compreesível para pessoas que tenham algum conhecimento de linguagem de programação

        3 - O requisito pode ser considerado um esboço de especificação de projeto, em vez de um modelo para ajudar o usuário a compreender o sistema


# Aula 15 - Análise de problemas

    Análise de problemas é outra forma de se referir a analise de requisitos.

    Sua vantagem é que ela mantém a maoir parte da facilidade de expressão e compreensão da linguagem natural, mas também garante que algum grau de uniformidade seja importo à especificação.

    É identificar maneiras de identificar soluções pros problemas informados..

    A analise de problemas implica em três formas de analise

        1 - Particionamento: Agrega as relações estruturais entre os objetos, ele compartimenta as estruturas a serem analisadas

        2 - Abstração: É a identificação das relações estruturais entre os objetos, funções e estados.
        
        3 - Projeção: É quando se é forncecido uma projeção da relação entre os objetos, funções e estados.

    Especificação de interfaces

    A maioria dos sistmas devem operar como outros sistemas.

    As espeificações devem ser definidas no início do processo e incluídas no documento de requisitos.

    existem três tipos de interfaces

        1. Interface de procedimentos

        2. Estrutura de dados

        3. Representação dos dados

        4. As notaçõos formais permitem que as interfaces sejam definidas de maneira nao ambígua, mas sua natureza especializada significa que elas não são compreensíveis sem treinamento especial.

# Aula 16 - Especificação de Requisitos de Software (ERS)

    A especificação de requisitos de software é prevista no padrão IEEE 830-1993.

    Ela trata de uma descrição do produto de software que esta sendo oferecido.

    No momento da geração de artefatos a partir da quebra dos procedimentos, é gerada os requisitos de software.

    Ao escrever uma especificação deverá ser levada em conta 5 principios

        1. Funcionalidade - O que o software deve fazer

        2. Interfaces Externas - Interação do software com o ambiente, seja outros sitemas ou pessoas

        3. Desempenho - Velocidade do sistema

        4. Atributos

        5. Restrições

    Ao final disso será elaborado um documento de requisitos de software a ERS.

    Deve incluir os requisitos de usuários e requisitos de sistema.

    Naturalmente, as informações incluas no documento de requisitos devem depender do tipo de software que esta sendo desenvolvido e a abordagem de desenvolvimento utilizada. Não há uma fórmula única.
    
# Aula 17 - Análise de requisitos orientada a objetos

    A abordagem orientada a objetos para a especificação de um sistema de software é caracterizada por hierarquias de objetos.

    A ideia basica é dar uma abordagem incremental à compreensão do problema, para ocultar detalhes desncessários e facilitar a captura dos recursos essenciais de um sistema complexo.

    A analise de requisitos orientada a objetos (OORA) começa com a definição dos objetos indentificados em uma partição

    Na primeira parte da analise é identificado:

        1. caracteristicas de cada objetos: é escolhido nome, serviços, Atributos

        2. Atributos

        3. Cardinalidade

# Aula 18 - Especificação genérica

    A classe de objetos é identificada de forma que os objetos representem instâncias dessa classe, herdem os atributos e os serviços fornecidos pelos membros da classe.

    O diagrama de fluxo de dados é conhecido como (DFD)

    O DFD é uma combinação com o fluxo de dados com o que esta especificado no dicionario de dados e nos processos. Tudo trabalha para concorrer a solução do problema

    São de fácil utilização e muito úteis para preencher lacunas entre as descrições informais do sistema e o desenvolvimento das descrições do fluxo de informações no sistema.

# Aula 19 - Dicionário de dados

    Ele fornece informações como tipo de dados, acurácia necessária de dados úteis aos projetistas e implementadores 

    Fluxo de dados especificam processo que geram ou recebem dados

    A engenharia de requisitos é um processo que contempla todas as atividades exigidas para criar e manter o documento de requisitos de sistema.

    Nesse contexto existem 4 atividades genericas que se deve trabalhar

        1. Estudo da viabilidade

        2. Obtenção
        
        3. análise de requisitos.

        4. Gerenciamento de requisitos

    A engenharia de requisitos pode ser empregada como processo de aplicação de método estruturado, como a análise orientada a objetos.  

# Aula 20 - Especificação do processo

    Ao descrever um processo pode até ser usado linguagem natural, mas não deve ser exagerado na linguaguem informal.

    É recomendado utilização de pseudo linguagem

    A descrição do processo não é feito para ser uma descrição do processo, mas sim uma descrição do processo em si

    
# Aula 21 - Estudos de viabilidade

    Para todos os sistemas novos, o processo de engenharia de requisitos de sistema deve começar com o estudo de viabilidade, por que se o projeto se mostrar inviável, nem adianta começar.

    A entrada para o estudo de viabilidade é uma descrição geral do sistema e de como ele será utilizado na organização.

    O estudo de viabilidade se atem a responder 3 perguntas

        1. O sistema contribui para os objetos da organização?

        2. O sistema pode ser implementado com a utilização da tecnologia atual dentro das restrições de custo e de prazo ?

        3. O sistema pode ser integrado a outros sistemas que já se encontram em operação?

    Preparar estudos de viabilidade envolve avaliar e coletar informações e redigir relatórios

    Como a organização se comportaria se esse sistema forsse implementado?

    O sistema requer tecnologia que não tenha sido utilizada anteriormente na organização?

# Aula 22 - Levantamento e análise de requisitos

    Stakeholder é qualquer pessoa que terá ou sofrerá influência direta ou indireta em relação aos requisitos do sistema

    