<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blue Cloud</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
  <link rel="stylesheet" type="text/css" href="Index.css"> <!--Folha de estilo (CSS)-->
  <link rel="icon" href="Imagens/icone.ico">
  <script language="Javascript"> //Funções JavaScript//
    function alerta(){  //Instruções donwload quiz//
      alert("Olá usuário!\n\nLogo após ser feito o download do arquivo (PC_Quiz.zip), descompacte e execute o arquivo 'Quiz_BlueCloud'.\n\nSe divirta!")
    }
  </script>
</head>
<body>

    <!--NavBar--> 
    <nav class="navbar sticky-md-top navbar-expand-lg navbar-dark" style="background-color: black;">
      <div class="container-fluid">
        <a class="navbar-brand" href="Index.html">
          <img src="Imagens/Logo.png" alt="" width="150px">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarColor01" aria-controls="navbarColor01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarColor01">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item1">
              <a class="nav-link active" aria-current="page" href="Index.html">Home</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link active dropdown-toggle" href="#" id="navbarDarkDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Conteúdo
              </a>
              <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="navbarDarkDropdownMenuLink">
                <li><a class="dropdown-item" href="IndexSophia.html">Sophia</a></li>
                <li><a class="dropdown-item" href="Temperatura.html">Altas temperaturas no oceano</a></li>
                <li><a class="dropdown-item" href="IndexPerseverence.html"> Perseverance</a></li>
                <li><a class="dropdown-item" href="BuracoNegro.html">Buraco Negro</a></li>
                <li><a class="dropdown-item" href="IndexIndustria.html">Indústria pelo mundo </a></li>
              </ul>
            </li>
            <li class="nav-item1">
              <a class="nav-link active" aria-current="page" href="PC_Quiz.zip" onclick="alerta()"> Quiz</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="Imagens/bd.png" style="width: 200px;">Banco de Dados</a>
            </li>
          </ul>
          <div class="login"><a class="login" href="LoginCadastro.html"><img src="Imagens/teste5.png" alt="" width="38" height="32"></img> Login / Cadastro</a></div> <!-- Cadastro/Login Cliente-->
        </div>
      </div>
    </nav>

      <!--Carousel-->

        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
         <div class="carousel-indicators">
           <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
             <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
               <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
                 <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3" aria-label="Slide 4"></button>
                   <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4" aria-label="Slide 5"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <a href="IndexSophia.html"><img src="Imagens/Sofia.png" class="d-block w-100" alt="sofia"></a>
          </div>
          <div class="carousel-item">
            <a href="Temperatura.html"><img src="Imagens/Temperatura.png" class="d-block w-100" alt="temperatura"></a>
          </div>
          <div class="carousel-item">
            <a href="IndexPerseverence.html"><img src="Imagens/Marte.png" class="d-block w-100" alt="marte"></a>
          </div>
          <div class="carousel-item">
            <a href="BuracoNegro.html"><img src="Imagens/buracos negros.png" class="d-block w-100" alt="..."></a>
          </div>
          <div class="carousel-item">
            <a href="IndexIndustria.html"><img src="Imagens/Industria.png" class="d-block w-100" alt="..."></a>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
        <br><br>

      <!--Inicio do conteúdo. 1° Parágrafo-->
        
        <br><br>
        <div class="bla">
            <h1>       
              Inteligência Artificial
            </h1>
            <p class="texto">
            Em termos mais simples, a inteligência artificial (IA) refere-se a sistemas ou máquinas que imitam a inteligência humana para executar 
            tarefas e podem se aprimorar iterativamente com base nas informações que coletam.
            A IA se manifesta de várias formas.<br><br> Alguns exemplos são:
            <br>
            <lu>
              <li class="n">Os chatbots usam a IA para entender os problemas dos clientes mais rapidamente e fornecer respostas mais eficientes</li>
              <li class="n">Os assistentes inteligentes usam a IA para analisar informações críticas de grandes conjuntos de dados de texto livre para melhorar a programação</li>
              <li class="n">Os mecanismos de recomendação podem fornecer recomendações automatizadas para programas de TV com base nos hábitos de visualização dos usuários</li>
            </lu>
            <br><br>
          </p>
        </div>

        <!--O vídeo é apenas uma sugestão. Pode ser o nosso "Elevator picht"-->

        <div class="bla3">
          <iframe width="90%" height="450" src="https://www.youtube.com/embed/N0SY3EgVIio" title="YouTube video player"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe>
         </div>
        <br><br>

        <!--Inicio 2° Parágrafo-->
        
        <br>
         <div class="bla1">
          <h1>Onde podemos encontrar inteligência artificial?</h1>
          
               <p class="texto">
                  A IA está por todos os lugares, no carro autônomo, no chão de fábrica e no sistema de atendimento dos hospitais. Mas também está na rede social, no seu celular, no antivírus, no buscador de internet. O Google, por exemplo, é um exemplo de empresa AI-first.
                  Ou seja, todos os seus produtos têm processos de machine learning.

                  <br><br>No Google Fotos, é possível procurar por objetos e situações específicos, de “abraços” a “cachorros” e “cores”. Além disso, o Assistente está sempre sugerindo criar um GIF, montagem ou efeito.

                  <br><br>No Gmail, o e-mail da gigante de buscas, o machine learning ajudou a aprimorar o filtro de spam e, no Google Tradutor, a mudança para o sistema de tradução com máquinas neurais melhorou a qualidade do que era traduzido de forma significativa.
                  Na busca, está o RankBrain, algoritmo que usa deep learning para melhorar o ranqueamento dos links. O reconhecimento de voz no Android também é “aprendizado de máquina”.
                  <img class="lat" src="Imagens/imglatnov.png" width= "20%" height="100%">
               </p>
                <br>

                  <p style="font-size: 20px; font-family:sans-serif; text-align: justify;">
                    No Facebook, a tecnologia ajuda a remover conteúdo impróprio antes mesmo de um post ser denunciado por um usuário.
                  Um mix de inteligência artificial, machine learning e visão computacional permite remover conteúdos impróprios com mais rapidez, rastrear mais conteúdo e aumentar a capacidade da equipe de revisão formada por revisores humanos.
        
                  <br><br>Mas, nem tudo são flores: você deve estar se perguntando por que, no caso da rede social, isso “não funciona”. O Facebook aponta que a IA é muito promissora, mas ainda está longe de ser eficaz para todos os tipos de conteúdos impróprios, dado que o contexto é algo muito importante.
                  Por isso, ainda temos pessoas revisando denúncias. Nesse caso, a tecnologia é usada para expandir a capacidade e acelerar o processo, mas ainda não substitui pessoas.
                  <br><br><br>

                  <b style="font-size: 25px; text-decoration: underline; text-underline-offset: 5px;">Quais são os principais benefícios da IA?</b>
                  <br><br>
                  A Inteligência Artificial é capaz de gerar vantagens para os negócios. Veja algumas das principais adiante!
                  <br><br><br>
                  <b style="font-size: 25px; text-decoration: underline; text-underline-offset: 5px;">Melhora na tomada de decisão</b>
                  <br><br>
                  A IA pode auxiliar na simplificação de processos de análise, especialmente uma empresa que preza pela tomada de decisão baseada em dados (data-driven).<br><br>
                  Isso porque ela é capaz de organizar e conferir maior clareza a dados “nebulosos” ou “confusos”, os quais dificultam o estabelecimento de estratégias.<br><br>
                  Um sistema de Inteligência Artificial pode desenvolver processos que envolvem correlações, regressões, estruturação de análises dos dados gerados etc. que servem de base para executivos tomarem decisões.<br><br>
                  Principalmente se estiver vinculada a uma solução de Big Data, que é capaz de lidar com um gigantesco volume de dados não-estruturados.<br>
                  <br><br><br>
                  <b style="font-size: 25px; text-decoration: underline; text-underline-offset: 5px;">Comodidade e escalabilidade</b>
                  <br><br>
                  Uma solução de IA virtual é capaz de empregar algoritmos para realizar segmentações mais precisas, de modo a sugerir mercadorias sintonizadas com os perfis de consumidores analisados. Isso aumenta as chances de se desenvolver boas estratégias comerciais.<br><br>
                  A IA também tem alto nível de replicabilidade de processos, já que os sistemas que a compõem são capazes de realizar as mesmas análises diversas vezes. Isso assegura que qualquer fluxo de trabalho se torne escalável.<br><br>
                  A obtenção de informações relevantes de relatórios também pode se tornar mais rápida. Isso porque já há algoritmos de text mining (mineração de textos) capazes de analisar um documento e encontrar informações nele.<br><br>
                  Esses fatores geram comodidade, já que são feitos de maneira mais rápida e simplificada pela solução de Inteligência Artificial.<br>
                  <br><br><br>
                  <b style="font-size: 25px; text-decoration: underline; text-underline-offset: 5px;">Aumento da automação</b>
                  <br><br><br>
                  A IA contribui para automação de atividades lógicas, analíticas e cognitivas, gerando maior velocidade no tratamento de informações. 
                  Isso serve como complemento à automação das tarefas físicas, especialmente da produção, que costuma ser propiciada por máquinas robóticas.
                  <br><br><br>
                  <b style="font-size: 25px; text-decoration: underline; text-underline-offset: 5px;">Redução de erros, de riscos e de custos operacionais</b>
                  <br><br>
                  Uma solução de Inteligência Artificial pode ser empregada no monitoramento de máquinas e sistemas computacionais da empresa. No caso dos equipamentos, ela pode usar dados de sensores, de câmeras, de registros em softwares de monitoramento, dentre outras fontes. Em relação aos sistemas, suas informações são provenientes de bancos de dados, de relatórios, de históricos etc.<br><br>
                  Graças aos conteúdos obtidos, ela tem a capacidade de descobrir gargalos, falhas e outros pontos fracos nos processos da empresa, diminuindo erros e aumentando a eficiência operacional. Isso reduz custos e evita dificuldades para as equipes.<br><br>
                  Aliás, dá até para realizar previsões sobre eventuais dificuldades, para que a empresa tome providências a tempo. Tal fato se dá porque ela gera diagnósticos de diversos setores e processos, contribuindo para o mapeamento de riscos (e também de oportunidades). Para tanto, ela pode checar frequentemente indicadores-chave de desempenho do negócio, com o propósito de relatar possíveis empecilhos às equipes.<br><br>
                  Outro ponto interessante é que seus processos de análise costumam apresentar baixo custo. Ela também contribui para que haja maior nível de acerto nas estratégias definidas pelos gestores, que tiveram por base os dados coletados e processados pela IA.<br><br>
                  
                  <br><br>
                  Agora vamos ao que interessa! <a href="IndexSophia.html">Vamos descobrir mais</a> sobre inteligência artificial com alguns exemplos
                </p>
                  
         </div>

        <!--Footer-->

      <div class="container1">
        <footer class="d-flex flex-wrap justify-content-between align-items-center py-2 my-0">
          <p class="col-md-4 mb-0 text-muted">&copy; 2021 Blue | Cloud, Inc</p>
          <a class="col-md-4 d-flex align-items-center justify-content-center mb-3 mb-md-0 me-md-auto link-dark text-decoration-none" href="#">
            <img src="Imagens/Logo.png">
            <svg class="bi me-2" width="40" height="32"><use xlink:href="#bootstrap"/></svg>
          </a>
          <ul class="nav col-md-4 justify-content-end">
            <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Início</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Features</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">Pricing</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">FAQs</a></li>
            <li class="nav-item"><a href="#" class="nav-link px-2 text-muted">About</a></li>
          </ul>
        </footer>
      </div>
      
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>  
</body>
</html>
