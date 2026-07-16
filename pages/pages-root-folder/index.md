---
layout: page-fullwidth
permalink: /index.html
title: "Bem-vindo à ERES 2026"
homepage: true
header:
  image_fullwidth: "banner-eres2026.png"
---

<style>
  h1 {
    text-align: center;
  }

  #countdown-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    background-color: #f1f1f1;
    padding: 20px;
    border-radius: 10px;
  }

  .countdown-unit {
    margin: 10px;
    text-align: center;
    background-color: #ffffff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    padding: 20px;
    flex: 1;
    min-width: 125px;
  }

  .countdown-unit span {
    display: block;
    font-size: 2.5em;
    font-weight: bold;
  }

  .unit-label {
    font-size: 1em;
    text-transform: uppercase;
    letter-spacing: 1px;
    color: #555;
  }

  .container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
    margin-top: -20px;
  }

  #countdown-title {
    font-size: 2em;
    margin-bottom: 20px;
    text-align: center;
  }

  h1, h3 {
    color: #333;
    margin: 20px 0;
    font-size: 1.8em;
  }

  .text {
    font-size: 1.1em;
    line-height: 1.6;
    color: #666;
  }

  .event-started {
    text-align: center;
    font-size: 2em;
    color: #FF6347;
    background-color: #FFF8F0;
    padding: 30px;
    margin-bottom: 1.25 rem;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  }

  @media (max-width: 768px) {
    #countdown-container {
      flex-direction: column;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 10px;
      width: 100%;
    }

    .countdown-unit {
      width: 75%;
      margin: 5px auto;
    }

    #title {
      text-align: left;
    }
  }
</style>
<!-- 
  <p class="text" style="text-align: center">
    <a href="{{ site.baseurl }}/certificados/" target="_blank">Clique aqui para consultar seu Certificado de Participação.</a>
  </p> -->

  <p class="text">A <b>Escola Regional de Engenharia de Software (ERES)</b> é um evento promovido anualmente pela Sociedade Brasileira de Computação (SBC). Em sua décima edição, a <b>ERES 2026</b> será realizada <b>presencialmente</b> entre os dias 14 e 16 de outubro de 2026.</p>

<p class="text">Nesta edição, o evento será organizado pela <a href="https://www.utfpr.edu.br/campus/toledo/" target="_blank">Universidade Tecnológica Federal do Paraná (UTFPR)</a>.</p>

<p class="text">A ERES tem como objetivo disseminar conhecimentos, experiências e boas práticas em Engenharia de Software, tanto sob a perspectiva acadêmica quanto profissional. A ERES 2026 constituirá um espaço regional para a apresentação e discussão de resultados de pesquisas, projetos de extensão, trabalhos desenvolvidos em cursos de graduação e pós-graduação, além de relatos de experiência provenientes da indústria.</p>

<p class="text">O evento também promoverá um ambiente propício para o debate sobre metodologias, práticas e abordagens relacionadas ao ensino e à aprendizagem em Engenharia de Software, fortalecendo a integração entre estudantes, professores, pesquisadores e profissionais da área.</p>

<p class="text">A realização da ERES 2026 proporcionará aos participantes o acesso a temas atuais e aos avanços do estado da arte da pesquisa científica em Engenharia de Software. A programação contará com palestras ministradas por pesquisadores de destaque e profissionais reconhecidos da indústria, contribuindo para a divulgação de pesquisas e práticas desenvolvidas na região Sul, no Brasil e no cenário internacional.</p>

<p class="text">Dessa forma, o evento busca estimular a troca de conhecimentos, a formação de novas parcerias e o interesse pela pesquisa científica, além de aproximar a academia do setor produtivo.</p>

<p class="text">A programação da ERES 2026 está sendo elaborada para contemplar palestras, minicursos e apresentações de artigos. Os trabalhos submetidos poderão ser apresentados no Fórum de Graduação, no Fórum de Pós-Graduação e no Fórum de Extensão, ampliando as oportunidades de participação e divulgação das iniciativas desenvolvidas pela comunidade de Engenharia de Software.</p>

  <h3>Fórum de Graduação</h3>
  <p class="text">Espaço destinado para apresentação dos trabalhos de pesquisa ou relatos de experiência em Engenharia de Software, desenvolvidos por acadêmicos de graduação, principalmente das IES catarinenses, gaúchas e paranaenses.</p>

  <h3> Fórum de Pós-Graduação</h3>
  <p class="text">Espaço para apresentação de trabalhos de estudantes de pós-graduação, com o objetivo de incentivar a troca de experiências e divulgar pesquisas em andamento e/ou concluídas e resultados obtidos. Além da clareza do trabalho, relevância do tema, e qualidade da apresentação, o Comitê Científico da ERES 2025 avaliará também as contribuições científicas do trabalho.</p>

  <h3>Fórum de Extensão</h3>
  <p class="text">Espaço para apresentação de trabalhos de relatos das atividades extensionistas aplicados aos currículos de computação, especialmente da Engenharia de Software, relacionados à forma  como estão implantando a extensão em seus currículos, conforme previsto na Resolução CNE/CES nº 7, de 18 de dezembro de 2018. O objetivo é incentivar a troca de experiências entre docentes e estudantes que atuam em ações de extensão.</p>

  <script>
    const countDownDate = new Date("October 14, 2026 13:00:00").getTime();
    const countdownTimer = setInterval(() => {
      const now = new Date().getTime();
      const distance = countDownDate - now;
      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);
      document.getElementById("days").innerHTML = String(days).padStart(2, '0');
      document.getElementById("hours").innerHTML = String(hours).padStart(2, '0');
      document.getElementById("minutes").innerHTML = String(minutes).padStart(2, '0');
      document.getElementById("seconds").innerHTML = String(seconds).padStart(2, '0');
      if (distance < 0) {
        clearInterval(countdownTimer);
        document.getElementById("countdown-container").style.display = "none";
        document.getElementById("title").style.display = "none";
        const eventStarted = document.createElement("div");
        eventStarted.classList.add("event-started");
        eventStarted.innerHTML = "O evento começou!";
        eventStarted.style.marginBottom = "1.5rem";
        document.querySelector(".container").prepend(eventStarted);
      }
    }, 1000);
  </script>
