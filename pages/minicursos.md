---
layout: page-fullwidth
title: "Minicursos"
subheadline: ""
permalink: "/programacao/minicursos/"
header:
  image_fullwidth: ERES-2025_Logo.svg
---

<style>
  .minicurso {
    margin-bottom: 40px;
  }

  .minicurso-content {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }

  .minicurso img {
    max-width: 200px;
    height: auto;
    margin-right: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .minicurso h2 {
    margin-top: 0;
  }

  .minicurso p {
    text-align: justify;
    color: #666;
    line-height: 1.6;
  }

  .instrutor {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }

  .instrutor img {
    max-width: 150px;
    height: auto;
    margin-right: 20px;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  }

  .instrutor-content {
    flex: 1;
  }

  .instrutor h3 {
    margin-top: 0;
  }

  .instrutor p {
    text-align: justify;
    color: #666;
    line-height: 1.6;
  }

  .instrutor-h3 {
    margin-bottom: 0.5rem;
  }

  hr.divisor {
    border: none;
    border-top: 1px solid #d3d3d3;
    margin: 40px 0;
  }

  @media (max-width: 768px) {
    .minicurso-content,
    .instrutor {
      flex-direction: column;
      align-items: center;
    }

    .minicurso img,
    .instrutor img {
      margin-right: 0;
      margin-bottom: 20px;
      max-width: 100%;
    }
  }
</style>

<!-- =========================
     MINICURSO 1 – RENATO
========================= -->
<div id="minicurso1" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Minicurso 1: Guia de IA para o empreendedor-programador (RÁPIDO | ATUALIZADO 2025)</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> Um guia direto ao ponto para programadores que querem empreender usando IA. Discutiremos como a profissão está mudando, por que o momento é favorável ao empreendedorismo, um passo a passo prático para tirar a ideia do papel com apoio de ferramentas de IA e, principalmente, como manter a experiência humana no atendimento enquanto a automação cuida do operacional.
      </p>

      <p><strong>📅 Data e horário:</strong> 29 de Outubro (quarta-feira), das 08h às 12h</p>

      <h3>Objetivos do minicurso</h3>
      <ul>
        <li>Discutir sobre o futuro da carreira de programador;</li>
        <li>Argumentar que estamos na melhor era para programadores investirem no empreendedorismo;</li>
        <li>Demonstrar como usar as novas ferramentas de IA para acelerar o processo de criação de uma startup;</li>
        <li>Argumentar que, na era da automação, delegar o operacional para as máquinas e focar no atendimento humano é o melhor caminho.</li>
      </ul>

      <h3>Sumário dos tópicos</h3>
      <p><strong>Seção 1 –</strong> Como a profissão do programador deve mudar nos próximos anos: impacto atual da IA e cenários próximos.</p>
      <p><strong>Seção 2 –</strong> Por que o empreendedorismo é uma opção cada vez mais atrativa para programadores.</p>
      <p><strong>Seção 3 –</strong> Decidi pular no barco: etapas, estratégias e ferramentas para começar.</p>
      <p><strong>Seção 4 –</strong> O novo diferencial: deixar a máquina no operacional e focar no humano.</p>
      <p><strong>Seção 5 –</strong> Avisos, promessas, situações inesperadas e dicas para a jornada empreendedora.</p>

      <h3>Público-alvo</h3>
      <p>Programadores que almejam empreender ou têm curiosidade sobre a área.</p>

      <h3>Relevância</h3>
      <p>Na nova era da IA, a profissão de programador está mudando rapidamente. Este curso mostra como aproveitar o momento para migrar (ou complementar a carreira) com empreendedorismo, unindo teoria e prática.</p>

      <h3>Duração</h3>
      <p>4 horas</p>

      <h3>Recursos necessários</h3>
      <p>Apenas uma sala com projetor (de preferência sem computadores).</p>
    </div>
  </div>

  <h3 class="instrutor-h3">Instrutor:</h3>
  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/renato.png" alt="Renato Mello Konflanz">
    <div class="instrutor-content">
      <h3>Renato Mello Konflanz</h3>
      <p>
        <strong>Contato:</strong> 📞 (49) 99171-9309 &nbsp;|&nbsp; 📧 <a href="mailto:renato.konflanz@unochapeco.edu.br">renato.konflanz@unochapeco.edu.br</a><br>
        <strong>Vínculo:</strong> Sócio da Dimo e Treino.io
      </p>
      <p>
        <strong>Breve currículo:</strong> Apaixonado por tecnologia desde cedo e adepto do empreendedorismo desde a adolescência. Graduado em Sistemas de Informação; após algumas tentativas independentes, tornou-se sócio e tech lead da Dimo, onde atua até hoje. Recentemente cofundou a Treino.io, unindo prática de produto, liderança técnica e educação.
      </p>
    </div>
  </div>
</div>

<hr class="divisor">

<!-- =========================
     MINICURSO 2 – BERNARDO
========================= -->
<div id="minicurso2" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Minicurso 2: Da Ideia ao Deploy — Construindo e Publicando Aplicações Web Modernas</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> Visão prática e integrada do ciclo completo de desenvolvimento web — da concepção à publicação — cobrindo modelagem, back-end com Node.js/Express/Sequelize (PostgreSQL), front-end com React/Nuxt, boas práticas de autenticação, dockerização, CI/CD e deploy em nuvem. O foco é hands-on: os participantes saem com uma aplicação funcional publicada.
      </p>
      <p><strong>📅 Data e horário:</strong> 30 de Outubro (quinta-feira), das 08h às 12h</p>

      <h3>Objetivos do Minicurso</h3>
      <ul>
        <li>Apresentar o ciclo completo de desenvolvimento de uma aplicação web moderna, da ideia ao deploy.</li>
        <li>Capacitar o uso de ferramentas e boas práticas em back-end, front-end, bancos de dados e publicação.</li>
        <li>Demonstrar um fluxo integrado com Node.js, Express, Sequelize, PostgreSQL, React/Nuxt, Docker e CI/CD.</li>
        <li>Estimular a prática hands-on para que os participantes publiquem uma aplicação funcional.</li>
      </ul>

      <h3>Sumário dos Tópicos</h3>
      <ul>
        <li><strong>Introdução ao Desenvolvimento Web Moderno</strong>
          <ul>
            <li>Conceitos gerais de cliente/servidor.</li>
            <li>Arquiteturas: monolito vs microsserviços.</li>
            <li>Visão geral do projeto do minicurso.</li>
          </ul>
        </li>
        <li><strong>Planejamento e Modelagem</strong>
          <ul>
            <li>Definição da ideia do sistema.</li>
            <li>Modelagem simples de banco (PostgreSQL).</li>
            <li>Versionamento com Git/GitHub.</li>
          </ul>
        </li>
        <li><strong>Back-end com Node.js e Express</strong>
          <ul>
            <li>Estruturação da API.</li>
            <li>Conexão ao banco com Sequelize.</li>
            <li>Boas práticas de autenticação (JWT).</li>
          </ul>
        </li>
        <li><strong>Front-end com React/Nuxt</strong>
          <ul>
            <li>Estrutura inicial do projeto.</li>
            <li>Comunicação com a API.</li>
            <li>Componentização e usabilidade.</li>
          </ul>
        </li>
        <li><strong>Dockerização e Deploy</strong>
          <ul>
            <li>Containers para back-end e banco de dados.</li>
            <li>Configuração de <code>docker-compose</code>.</li>
            <li>Deploy cloud/local (ex.: Vercel, Render, DigitalOcean).</li>
          </ul>
        </li>
        <li><strong>Boas Práticas de Engenharia de Software</strong>
          <ul>
            <li>Testes básicos e logs.</li>
            <li>CI/CD e monitoramento.</li>
            <li>Segurança, escalabilidade e manutenção.</li>
          </ul>
        </li>
      </ul>

      <h3>Público-alvo</h3>
      <ul>
        <li>Estudantes de graduação em Computação e áreas afins.</li>
        <li>Profissionais iniciantes que desejam entender o ciclo completo de desenvolvimento.</li>
        <li>Interessados em criar, integrar e publicar aplicações modernas na prática.</li>
      </ul>

      <h3>Relevância, Impacto e Benefícios</h3>
      <ul>
        <li>Conecta teoria (modelagem, arquitetura) à prática (deploy real) alinhada ao mercado.</li>
        <li>Estímulo à cultura DevOps e à entrega contínua.</li>
        <li>Entrega um produto funcional publicado, aplicável a projetos acadêmicos e profissionais.</li>
      </ul>

      <h3>Duração e Roteiro</h3>
      <p>3h30 a 4h</p>
      <ul>
        <li>30 min — Introdução e modelagem</li>
        <li>1h30 — Implementação back-end e front-end</li>
        <li>1h — Dockerização e deploy</li>
        <li>30 min — Encerramento e boas práticas</li>
      </ul>

      <h3>Recursos Necessários</h3>
      <ul>
        <li>Laboratório com computadores e internet.</li>
        <li>Projeção multimídia.</li>
        <li>Pré-instalações: Node.js (18), Docker, Git, VSCode (ou similar).</li>
      </ul>
    </div>
  </div>

  <h3 class="instrutor-h3">Instrutor:</h3>
  <div class="instrutor">
    <!-- Opcional: adicione uma foto em /images/minicursos/bernardo.jpg -->
    <img src="{{ site.urlimg }}/minicursos/bernardo.png" alt="Bernardo Zanetti">
    <div class="instrutor-content">
      <h3>Bernardo Zanetti</h3>
      <p>
        <strong>Vínculo:</strong> Unochapecó (Acadêmico de Ciência da Computação) / Desenvolvedor de Sistemas<br>
        <strong>Local:</strong> Chapecó – SC
      </p>
      <p>
        <strong>Contato:</strong>
        📧 <a href="mailto:Bernardo.zanetti@unochapeco.edu.br">Bernardo.zanetti@unochapeco.edu.br</a> &nbsp;|&nbsp;
        📞 (49) 9 8921-4727 &nbsp;|&nbsp;
        <a href="https://www.linkedin.com/in/bernardo-zanetti-378928233/" target="_blank" rel="noopener">LinkedIn</a>
      </p>
      <p>
        <strong>Breve currículo:</strong> Estudante de Ciência da Computação na Unochapecó, com experiência prática em desenvolvimento full stack, bancos de dados e infraestrutura. Atua com Engenharia de Software, DevOps, migração de legados, APIs REST, dockerização e UI/UX. Participou de projetos com Sequelize (PostgreSQL e Oracle), React, Nuxt.js, Express, Docker, CI/CD e integrações corporativas, unindo teoria e prática para soluções modernas em contextos acadêmicos e corporativos.
      </p>
    </div>
  </div>
</div>

<hr class="divisor">

<!-- =========================
     MINICURSO 3 – JEAN
========================= -->
<div id="minicurso3" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Minicurso 3: Da Ideia ao Deploy — UX para pessoas de TI: criando softwares que as pessoas amam usar</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> Fundamentos e prática de UX para profissionais de tecnologia: do entendimento do usuário às heurísticas de Nielsen, fluxos centrados no usuário, testes de usabilidade rápidos e a integração UX + Dev no dia a dia de engenharia de software.
      </p>
      <p><strong>📅 Data e horário:</strong> 31 de Outubro (sexta-feira), das 08h às 12h</p>

      <h3>Objetivos do minicurso</h3>
      <ul>
        <li>Introduzir fundamentos de UX e usabilidade para estudantes e profissionais de TI;</li>
        <li>Mostrar como decisões de experiência impactam adoção e sucesso de sistemas;</li>
        <li>Ensinar técnicas simples de avaliação de usabilidade aplicáveis por qualquer pessoa da área;</li>
        <li>Exercitar a colaboração entre desenvolvimento e experiência do usuário.</li>
      </ul>

      <h3>Conteúdo (sumário e descrição)</h3>
      <ol>
        <li><strong>Introdução a UX no contexto da Engenharia de Software</strong><br>
          O que é UX (além de UI). Relação entre usabilidade e qualidade (ISO 9241; eficiência, eficácia, satisfação). Exemplos práticos de bons e maus designs. <em>Mini exercício:</em> análise de interfaces.
        </li>
        <li><strong>Heurísticas de Nielsen aplicadas ao código e produtos</strong><br>
          As 10 heurísticas com exemplos. Como devs aplicam no dia a dia (mensagens de erro, feedback, consistência). <em>Exercício:</em> análise em duplas ou quiz (Kahoot).
        </li>
        <li><strong>Fluxos de usuário vs fluxos técnicos</strong><br>
          Diferença entre o que o sistema faz e como o usuário percebe. Exemplos (incluindo referências como growth.design). <em>Exercício:</em> fluxo técnico vs fluxo de usuário (cadastro em app de delivery).
        </li>
        <li><strong>Testes de usabilidade que qualquer um pode aplicar</strong><br>
          O que é, técnicas simples e validação sem designer dedicado. <em>Exercício:</em> teste em papel (ex.: redefinir senha/criar playlist).
        </li>
        <li><strong>UX como diferencial na carreira</strong><br>
          Por que profissionais de TI com noção de UX são mais valorizados. Como trabalhar com designers. Pipeline ágil integrando UX + Dev.
        </li>
      </ol>

      <h3>Público-alvo</h3>
      <p>Estudantes de CC, SI, ES e áreas correlatas; desenvolvedores, PMs e QAs que desejam elevar a experiência do usuário.</p>

      <h3>Relevância</h3>
      <p>Ajuda desenvolvedores a pensar além do código, reduzindo retrabalho e erros de usabilidade; conecta técnica com experiência real e apresenta práticas de UX que cabem no fluxo de ES, além de apresentar trilhas de carreira relacionadas.</p>

      <h3>Recursos necessários</h3>
      <ul>
        <li>Projetor e computador;</li>
        <li>Sala com mesas em grupo (para exercícios);</li>
        <li>Papel A4 e canetas (prototipagem rápida).</li>
      </ul>
    </div>
  </div>

  <h3 class="instrutor-h3">Ministrante:</h3>
  <div class="instrutor">
    <img src="{{ site.urlimg }}/minicursos/jean.png" alt="Jean Carlos da Campo">
    <div class="instrutor-content">
      <h3>Jean Carlos da Campo</h3>
      <p>
        <strong>Vínculo:</strong> IXCSoft<br>
        <strong>Contato:</strong> 📧 <a href="mailto:jeancarlosdacampo@gmail.com">jeancarlosdacampo@gmail.com</a>
      </p>
      <p>
        <strong>Breve currículo:</strong> Product Design Manager na IXCSoft, liderando um time de 15 pessoas para elevar a experiência dos produtos do grupo. Focado em organizar equipes, otimizar processos e usar design como ferramenta estratégica. Graduado em Sistemas de Informação (Unochapecó), pós-graduado em UX Design & Learning Experience (IDI) e UX Design & Agilidade (PUC Minas). Iniciou carreira como programador e, há ~5 anos, migrou para UX, unindo visão técnica e foco na experiência do usuário.
      </p>
    </div>
  </div>
</div>

<hr class="divisor">

<!-- =========================
     MINICURSO 4 – GEOMAR
========================= -->
<div id="minicurso4" class="minicurso">
  <div class="minicurso-content">
    <div>
      <h2 class="minicurso-title">Minicurso 4: Modelagem para Bancos de Dados NoSQL — Uma saga de 4 tipos de dados</h2>
      <p class="minicurso-resumo">
        <strong>Resumo:</strong> Apresenta os diferentes modelos de dados de bancos NoSQL e os contextos adequados para sua aplicação. O foco é prático: explora técnicas específicas de modelagem para chave-valor, colunar, orientado a documentos e orientado a grafos, visando eficiência e desempenho.
      </p>
      <p><strong>📅 Data e horário:</strong> 31 Outubro (sexta), das 14h às 18h</p>

      <h3>Objetivos do Minicurso</h3>
      <ul>
        <li>Apresentar os modelos de dados NoSQL e os cenários em que cada um é mais apropriado;</li>
        <li>Explorar técnicas práticas de modelagem específicas para cada modelo de dados;</li>
        <li>Discutir o papel dos BDs NoSQL diante dos desafios do Big Data;</li>
        <li>Capacitar os participantes a tomar decisões de modelagem orientadas à performance.</li>
      </ul>

      <h3>Sumário dos Tópicos</h3>
      <ul>
        <li><strong>Histórico dos Bancos de Dados</strong> — Evolução dos modelos e os problemas que cada um se propôs a resolver.</li>
        <li><strong>Big Data e seus Desafios</strong> — O que é, como identificar e quais os principais desafios associados.</li>
        <li><strong>Panorama dos Bancos NoSQL</strong> — Características, vantagens e desvantagens gerais.</li>
        <li><strong>Modelagem para diferentes tipos de dados:</strong>
          <ul>
            <li>Chave-Valor</li>
            <li>Orientado a Colunas</li>
            <li>Orientado a Documentos</li>
            <li>Orientado a Grafos</li>
          </ul>
          Para cada tipo, serão discutidas as principais características e apresentada uma abordagem prática de modelagem visando desempenho e escalabilidade.
        </li>
      </ul>

      <h3>Público-alvo</h3>
      <p>Estudantes de Graduação e Pós-Graduação em Computação e áreas correlatas.</p>

      <h3>Relevância</h3>
      <p>Com o crescimento dos sistemas distribuídos e da demanda por performance em ambientes de Big Data, compreender e aplicar corretamente a modelagem em bancos NoSQL é fundamental para profissionais e pesquisadores.</p>

      <h3>Duração</h3>
      <p>3h30 a 4h</p>

      <h3>Recursos Necessários</h3>
      <p>Datashow e ponteiro. Não é necessário laboratório de informática.</p>
    </div>
  </div>

  <h3 class="instrutor-h3">Instrutor:</h3>
  <div class="instrutor">
    <img src="{{ site.urlimg }}/geomar.gif" alt="Geomar André Schreiner">
    <div class="instrutor-content">
      <h3>Geomar André Schreiner</h3>
      <p>
        <strong>Vínculo:</strong> Universidade Federal da Fronteira Sul (UFFS)<br>
        <strong>Contato:</strong> 📧 <a href="mailto:geomar.schreiner@uffs.edu.br">geomar.schreiner@uffs.edu.br</a>
      </p>
      <p>
        <strong>Breve currículo:</strong> Doutor em Ciência da Computação pela UFSC. Professor da UFFS (Chapecó), atua nas áreas de Banco de Dados NoSQL e NewSQL, interoperabilidade e particionamento de dados. Possui experiência acadêmica e prática em projetos de modelagem e otimização de desempenho em sistemas de dados modernos.
      </p>
    </div>
  </div>
</div>