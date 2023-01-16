<script lang="ts">
  import "../site.css";

  function open() {
    window.open("https://wa.me/" + "5519996899619");
  }
</script>

<main class="wrapper">
  <nav class="navigation">
    <section class="container">
      <a class="navigation-title">
        <h1 class="title">Maria Julia Marques</h1>
      </a>
      <ul class="navigation-list float-right">
        <li class="navigation-item computer">
          <a class="navigation-link" href="#abordagem">Abordagem</a>
        </li>
        <li class="navigation-item">
          <a class="navigation-link" href="#contato">
            <button class="button button-outline">Contato</button>
          </a>
        </li>
      </ul>
    </section>
  </nav>

  <header class="header">
    <section class="container">
      <h3>Especialista em Psicologia Clínica</h3>
      <h1>Psicóloga Maria Julia Marques</h1>
      <p class="small">
        ‘‘Quando a situação for boa, desfrute-a. Quando a situação for ruim,
        transforme-a. Quando a situação não puder ser transformada,
        transforme-se’’. - Viktor Frankl
      </p>

      <button class="button" on:click={open}>Entrar em Contato</button>
      <div class="spacer" />
    </section>

    <img class="img-myself" src="/me.jpg" alt="me" />
  </header>
  <div class="content green">
    <section class="container">
      <div class="row">
        <div class="column">
          <h3>Possíveis Benefícios da Terapia</h3>
          <ul>
            <li>Manejo da ansiedade elevada</li>
            <li>Manejo das emoções</li>
            <li>Superação de limitações</li>
            <li>Autoconhecimento</li>
            <li>Ressignificação de traumas do passado</li>
            <li>Desenvolvimento de habilidades sociais</li>
            <li>Reconhecimento do seu propósito de vida</li>
            <li>Identificação de pontos frágeis</li>
          </ul>
        </div>
        <div class="column small-m">
          <p>Atendimento para todas as idades. Presencial e/ou online.</p>
          <p>
            Forneço recibo para convênios que trabalham com a modalidade de
            reembolso.
          </p>
        </div>
      </div>
      <button class="button" on:click={open}>Entrar em Contato</button>
    </section>
  </div>

  <div class="content" id="abordagem">
    <section class="container">
      <h3>Abordagem</h3>
      <p>Terapia realizada com base na abordagem da Logoterapia.</p>
      <strong>O que é Logoterapia?</strong>
      <p>
        A Logoterapia é uma abordagem dentro das humanistas. Ela estimula o(a)
        paciente a desenvolver sua autonomia e a responsabilidade pessoal diante
        dos dilemas do dia a dia. Associado a isso, também estimula o
        entendimento de quais os sentidos de sua vida e como isso se relaciona
        com a satisfação e felicidade pessoal. Na prática, a terapia é conduzida
        como uma conversa, onde troca-se informações e estimula-se a reflexão
        pra encontrar possíveis soluções para os problemas e dificuldades.
      </p>
      <strong>Quais problemas podem ser trabalhados em psicoterapia?</strong>
      <p>
        Ansiedade elevada, T.O.C. (Transtorno Obsessivo Compulsivo),
        Fobias/medos, Traumas, Depressão, Estresse, Problemas sociais,
        Dependência emocional, Insegurança, Baixa autoestima, Transtorno do
        Espectro Autista, Dificuldades sexuais, entre outros.
      </p>
    </section>
  </div>

  <div class="content alternate" id="contato">
    <section class="container">
      <h3>Contato</h3>
      <a class="inverted" href="" on:click={open}>
        Whatsapp:
        <img class="whatscontact" src="whats.svg" alt="whatsapp" />
      </a>
      <a class="inverted" href="tel:1999689-9619">Telefone: (19) 99689-9619</a>
      <a class="inverted" href="mailto:majulia.marques@gmail.com"
        >Email: majulia.marques@gmail.com</a
      >
      <a class="inverted" href="http://instagram.com/ouse.pensar"
        >Instagram: @ouse.pensar
      </a>
    </section>
  </div>
  <div class="content">
    <section class="container">
      <h3>Dúvidas Frequentes</h3>
      <strong>Como funciona a terapia?</strong>
      <p>
        A terapia é sempre elaborada com base na queixa do(a) paciente. Não
        existe uma regra única, uma vez que as pessoas não são iguais. Suas
        dúvidas e aflições não são as mesmas, e por isso, é necessário um
        atendimento personalizado para cada tipo de demanda. O importante é que
        o(a) paciente se sinta seguro(a) e que tenha certeza que as suas
        aflições serão, de fato, resolvidas. A colaboração do(a) paciente é
        outro ponto que merece destaque. Você precisa estar disposto(a) a se
        abrir na terapia e a refletir sobre as questões propostas pela psicóloga
        para que o tratamento seja eficaz.
      </p>

      <strong>Em quanto tempo verei resultados?</strong>
      <p>
        Quando você não está se sentindo bem, a ânsia para melhorar pode ser
        grande. Entretanto, quando se trata de terapia, não há como definir um
        prazo com exatidão. Existem estimativas de duração de acompanhamento
        psicoterapêutico, mas como cada paciente tem a sua própria personalidade
        e desafios, é preciso analisar cada caso separadamente. Isso significa
        que você pode demorar para ver os resultados desejados. Todavia,
        acredite, eles aparecerão à medida que você se permitir se conhecer e
        passar por processos de mudança. Para isso, é preciso dar tempo ao
        tempo.
      </p>

      <strong>Aceita convênio?</strong>
      <p>
        Forneço recibo para convênios que trabalham com a modalidade de
        reembolso.
      </p>

      <strong>Posso remarcar a minha consulta?</strong>
      <p>
        Qualquer consulta poderá ser remarcada através do WhatsApp, desde que a
        remarcação seja realizada até 24h antes do atual horário da consulta.
        Você poderá escolher um novo horário caso tenha disponibilidade de
        horários. Se houver cancelamento de última hora ou falta sem aviso
        prévio poderá ser cobrada uma taxa.
      </p>
      <button class="button" on:click={open}>Entrar em Contato</button>
    </section>
  </div>

  <div class="content blue">
    <section class="container">
      <p class="centered">
        Atenção: Este site não oferece atendimento imediato a pessoas em crise
        suicida. Em caso de crise ligue para o CVV 188. Em caso de emergência,
        procure o hospital mais próximo. Havendo risco de morte, ligue
        imediatamente para o SAMU (telefone 192).
      </p>
    </section>
  </div>
</main>

<style>
  .img-myself {
    width: 20%;
    position: absolute;
    top: 14%;
    right: 2%;
    border: solid 3pt white;
    border-radius: 4px;
  }

  @media (max-width: 600px) {
    .img-myself {
      width: 33%;
      top: 490px;
    }
    .computer {
      display: none;
    }

    .navigation .navigation-list {
      margin-right: 1rem !important;
    }
  }

  .button-outline {
    color: var(--primary);
    border-color: var(--primary);
  }

  .button:not(.button-outline) {
    background-color: var(--primary);
    border-color: var(--primary);
  }

  .content {
    padding-top: 4rem;
    padding-bottom: 4rem;
    background-color: var(--bg);
    font-size: 13pt;
    font-weight: bolder;
  }

  p {
    font-size: 12pt;
    font-weight: normal;
  }

  .centered {
    text-align: center;
  }

  .content.orange {
    background-color: var(--orange);
    color: white;
  }

  .content.green {
    background-color: var(--green);
    color: white;
  }

  .content.blue {
    background-color: var(--color4);
    color: white;
  }
  .content.yellow {
    background-color: var(--yellow);
    color: white;
  }

  .content.pink {
    background-color: var(--pink);
    color: white;
  }

  .content.alternate {
    background-color: var(--alternate);
    color: white;
  }

  .content.inverted {
    background-color: var(--inverted);
    color: white;
  }
  a.inverted {
    color: white;
    display: block;
  }

  .whatscontact {
    height: 25px;
  }

  .spacer {
    padding: 1.5rem;
  }

  p.small {
    margin-bottom: 1rem;
  }
</style>
