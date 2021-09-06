<!DOCTYPE html>
<html lang="pt">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="refresh" content="120">
    <meta name="estudante de TI" content="sistemas operacionais">
    <link rel="stylesheet" href="sistemas.css">
    <title>sistemas operacionais</title>
</head>

<body>
    <header id="inicio">
        <ul>
            <li><a href="#link1">sistema operacional</a></li>
            <li><a href="#link2">tipos de sistemas</a></li>
            <li><a href="#link3">processador</a></li>
            <li><a href="#link4">memoria cache</a></li>
            <li><a href="#link5">barramento</a></li>
        </ul>
    </header>
    <div id="link1">
        <h1>
            sistemas operacionais
        </h1>
        <p>
            <u>O sistema operacional então serve de interface entre o ususario e os recursos de hardware</u>,
            tornando esta comunicação transparente ou imperceptivel e permitindo ao usuario um trabalho mais eficiente e
            com
            menos possibilidades de erros.<br>
            <u> não é só no controle do acesso a hardware compartilhado que o sistema operacional atua, ele nos permite
                executar
                varias tarefas</u>, como operacional atual, eles nos permite executar varias tarefas, <u>como imprimir
                um documeto,
                copiar um arquivo pela ineternet ou processar uma planilha, entre outros</u>, O SO deve ser capaz de
            controlar a
            execução concorrente de todas essas tarefas.
        </p>
        <p>
            Ainda podemos dizer que, embora alguns programas sejam escritos baseados nas instruções de um determinado
            processador,
            será responsabilidade do sistema operacional executar tarefas básicas do micro, ou seja, ensinar ao
            processador
            como desenhar uma janela ou imprimir um documento.
        </p>
        <p>
            <u>A evolução dos processadores de entrada/saída permitiu que, enquanto um programa esperasse por uma
                operação
                de
                leitura/gravação,
                o processador executasse um outro programa. A técnica de compartilhamento da memória principal e
                processador
                deu
                se o nome de multiprogramação. A multiprogramação evoluiu, preocupada em oferecer aos usuários tempos de
                resposta razoáveis e uma interface cada vez mais amigável.
                Para tal, cada programa na memória utilizaria o processador em pequenos intervalos de tempo. A esse
                sistema
                de
                divisão de tempo do processador chamou-se time-sharing (tempo compartilhado).</u>
        </p>
        <p>
            Monoprogramáveis ou Monotarefa podem executar apenas um programa por vez. Para que um usuário possa executar
            outro programa,
            deverá aguardar a finalização do programa corrente Sistemas Multiprogramáveis ou Multitarefa: os recursos
            computacionais são compartilhados entre os diversos usuários e suas aplicações.
            Podemos observar o compartilhamento de memória e do processador. Nesse caso, o compartilhamento de tempo no
            processador é distribuído. Assim, o usuário tem a impressão que vários processos estão sendo executados
            simultaneamente.
            Um dos processos ocupa o processador enquanto os outros ficam enfileirados, aguardando a sua vez de entrar
            em
            execução. Cabe ao sistema operacional o papel de gerenciar de forma ordenada e protegida o acesso
            concorrente
            aos recursos disponíveis.
            A grande diferença entre os dois tipos de sistemas é que <u>em sistemas fortemente acoplados existe uma
                memória
                compartilhada por todos os processadores, enquanto nos fracamente acoplados, cada sistema tem sua
                própria
                memória individual.</u>
        </p>
    </div>
    <hr>
    <aside>
        <img src="imagens/SO1.png" alt="introdução a sistemas operacionais">
        <img src="imagens/SOhardware.png" alt="hardware">
    </aside>
    <hr>
    <div>
        <h2>##sistemas operacionais##</h2>
        <p>
            <u>sistema operacional embarcado: um SO sortware que so funciona em um hardware especifico</u>
            ex: dvd, tv, carro, celular iphone, ou seja não tem como usar um SO de uma geladeira em uma tv e etc..
        </p>
        <h3>
            #processamento distribuido#
        </h3>
        <p>
            é capacidade de executar a mesma instrução de dois processadores distintos ou mais da mesma marca.
        </p>
        <h4 id="link2">
            #tipos de sistemas operacionais #
        </h4>
        <p>
            <u>sistemas Monoprogramaveis ou monotarefas: permite que todos os recursos do sistema fiquem exclusivamente
                a
                uma
                unica tarefa.
                sistemas multiprogramaveis ou multitarefas: varias aplicações compartilham os mesmo recursos
                sistemas multiplos procesadores: pode possuir duas ou mais UCP's interligadas e trabalhando em conjunto,
                esse
                tipo de sistema permiti executar varios programas ao mesmo tempo, subdividindo em partes para serem
                executadas
                simutaneamente em mais de um processador. e pode ter dois tipos.
                *fracamente acplados: hardware distintos e interconectados por uma mesma linha de comunicação. pode
                possuir
                ate
                mais de dois sistemas interligados, seus processadores estão em arquiteturas diferentes interligados por
                cabos
                interconexão
                * fortemente aclopados: ta no mesmo hardware e no mesmo sistema operacional. existe mais de um
                processador,
                onde
                eles compartilham apenas uma memoria e um sistema operacional que gerencia os dispositivos de E/S.
                Quando os
                processadores são iguais podemos chama-los sistema simetrico, mas quando são processadores diferentes
                chamados
                assimetricos.</u>
        </p>
        <a href="#inicio">volte para o topo da pagina</a>
    </div>
    <h4 id="link3">#processador#</h4>
    <p>gerencia <u>todo o sistema computacional</u>, e <u>controla e executa instruções na memoria principal</u>. <u>Dentro
        do processador é composto por: unidade de controle, unidade
        logica e arimética e registradores.</u>
        unidade de controle: responsavel por gerenciar as atividades dos componentes do computador, como gravação de
        dados em disco ou a busca de isntruções na memoria.
        Unidade lógica e aritmetica: é responsavel pela realização de operações testes e comparações e aritmeticas,
        somas e subtrações.
        registradores são dipositivos com a função de armazenar dados temporariamente.
    </p>
    <IFrame src="https://manoellion.github.io/conteudos-didaticos/"></IFrame>
        <a href="https://manoellion.github.io/conteudos-didaticos/">ir para o site</a>
    <h4>#Registradores#</h4>
    <p>
        Contador de instruções (CI) ou program counter (PC) => contém o endereço da próxima instrução que o processador
        deve buscar e executar.
        Apontador de pilha (AP) ou stack pointer (SP) => contém o endereço de memória do topo da pilha.
        <br> MBR => memory buffer register, este registrador é utilizado para <u>guardar</u> o conteúdo de uma ou mais células
        de
        memória.
        <br>MAR => memory address register, através do conteúdo deste registrador a unidade de controle <u>sabe qual</u> a
        célula de memória que será acessada.
    </p>
    <aside>
        <img src="imagens/marembr.png" alt="opção de leitura e opção de gravação">
    </aside>
    <section class="section">
        <h4 id="link4">Memoria cache: É uma memória volátil, com alta velocidade, porém, pequena capacidade de
            armazenamento.
            Como funciona ?
        </h4>
        <p>
            A memória cache armazena uma pequena parte do conteúdo da memória principal. Toda vez que o processador faz
            referência a um dado armazenado na memória, é verificado, primeiramente, se o mesmo encontra-se na memória
            cache. Caso encontre, não há necessidade do acesso à memória principal, agilizando o acesso. <br>
            Existe uma hierarquização de cache, em Cache L1, com pouco espaço para armazenamento e altíssima velocidade.
            E
            em Cache L2, com maior capacidade de armazenamento, porém, com uma velocidade de acesso inferior a Cache L1
        </p>
        <h4>Memória Secundária</h4>
        <p>
            Essa memória é um meio permanente, isto é, não volátil. <br> Enquanto a memória principal precisa ser
            energizada
            constantemente, a memória secundária não
        </p>
        <a href="#inicio">volte para o topo da pagina</a>
    </section>
    <aside>
        <img src="imagens/memorias.png" alt="tipos de memorias">
    </aside>
    <h4 id="link5">barramento</h4>
    <p>
        É o <u>meio de comunicação compartilhado que permite a comunicação entre as unidades funcionais de um sistema
        computacional.</u>
    </p>
    <img src="imagens/barramento.png" alt="barramento">
    <h4>tipos de barramentos</h4>
    <dl>
        <dt> Barramentos processador-memória</dt>
        <dd>
            <u>Curtos, extremamente velozes</u>;
            Maximizam a banda passante memória-processador;
            Geralmente, são proprietários do fabricante de processador e/ou máquina.
        </dd>
        <dt>
            Barramentos de E/S
        </dt>
        <dd>
            Mais longos;
            Podem ter muitos tipos de dispositivos conectados a eles;
            Precisam atender a uma ampla faixa de bandas passantes (levando em conta dispositivos que venham a ser
            conectados);
            Não necessariamente têm interface direta com a memória;
            Podem usar o barramento processador-memória ou o barramento do backplane para se comunicar com a memória
            principal
            São padronizados;
            Apresentam uma interface moderadamente simples e de baixo nível (pouca eletrônica adicional necessária ao
            dispositivo);
        </dd>
        <dt>
            Barramentos do Backplane
        </dt>
        <dd>
            Projetados para permitir que processador, memória e dispositivos de E/S possam coexistir em um único
            barramento físico;
            Balanceiam as demandas de comunicação processador-memória com as demandas de comunicação dispositivos de
            E/S-memória;
            Muitas vezes são construídos diretamente no backplane da máquina (placa-mãe);
            São padronizados;
            Necessidade de uma lógica adicional para interface barramento de backplane-dispositivo.
        </dd>
    </dl>
    <h4>Máquinas com barramento único</h4>
    <img src="imagens/processador.png" alt="barramento">
    <h4>Máquinas com barramento memória-processador separado do barramento de E/S</h4>
    <img src="imagens/processador1.png" alt="barramento">
    <h4>pipelining</h4>
    <img src="imagens/pipelining.png" alt="pipelining">
    <h4>arquitetura risc e cisc</h4>
    <p>
        RISC – Reduced Instruction Set Computer
        Um processador com essa arquitetura se caracteriza por possui poucas instruções de máquina, em geral bastante
        simples, que <u>são executadas diretamente pelo hardware.</u>
    </p>
    <p>
        CISC – Complex Instruction Set Computer
        Possuem instruções mais complexas que <u>são interpretadas por microprogramas</u>
    </p>
    <img src="imagens/riscecisc.png" alt="risc e cisc">
    <a href="#inicio">volte para o topo da pagina</a>
</body>

</html>
