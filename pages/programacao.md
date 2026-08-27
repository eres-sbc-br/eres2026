---
layout: page-fullwidth
show_meta: false
title: "Programação Geral"
permalink: "/programacao/"
header:
  image_fullwidth: "ERES-2026_Logo.svg"
---

<style>
  .programacao-wrapper {
    width: 100%;
    overflow-x: auto;
    margin-bottom: 30px;
  }

  .programacao-table {
    width: 100%;
    min-width: 1100px;
    border-collapse: collapse;
    table-layout: fixed;
  }

  .programacao-table th,
  .programacao-table td {
    border: 1px solid #d1d1d1;
    padding: 8px;
    text-align: left;
    vertical-align: middle;
    box-sizing: border-box;
  }

  .programacao-table th {
    text-align: center;
    font-weight: bold;
  }

  /* Coluna de horário */
  .programacao-table .time-cell {
    width: 130px;
    background-color: #f0f0f0;
    text-align: center;
    font-weight: bold;
    white-space: nowrap;
  }

  /* Coluna de observações */
  .programacao-table .observation {
    width: 260px;
    background-color: #fafafa;
  }

  /* Linhas gerais */
  .programacao-table .full-row {
    text-align: center;
    font-weight: bold;
    background-color: #f5f5f5;
  }

  /* Minicursos */
  .programacao-table .course {
    background-color: #e6f7e6;
  }

  /* Sessões técnicas */
  .programacao-table .session {
    background-color: #fff9e6;
  }

  /* Palestras */
  .programacao-table .lecture {
    background-color: #fbeaea;
  }

  /* Eventos especiais */
  .programacao-table .soft-blue {
    background-color: #f2f7ff;
  }

  .programacao-table .hard-blue {
    background-color: #1f6d8c;
    color: white;
    text-align: center;
    font-weight: bold;
    font-size: 18px;
  }

  .programacao-table .hard-green {
    background-color: #00a651;
    color: white;
    text-align: center;
    font-weight: bold;
    font-size: 18px;
  }

  /* Cabeçalhos dos dias */
  .programacao-table .header-green {
    background-color: #e6f3e6;
  }

  .programacao-table .header-purple {
    background-color: #eae6f7;
  }

  .programacao-table .header-red {
    background-color: #f7e6e6;
  }

  /* Destaques */
  .programacao-table strong {
    font-weight: bold;
  }

  @media screen and (max-width: 900px) {
    .programacao-table th,
    .programacao-table td {
      padding: 6px;
      font-size: 14px;
    }
  }
</style>

<main class="programacao-page">

  <div class="programacao-wrapper">

    <table class="programacao-table">

      <thead>
        <tr>
          <th class="time-cell">Horário</th>
          <th class="header-green">14/10</th>
          <th class="header-purple">15/10</th>
          <th class="header-red">16/10</th>
          <th class="observation">Observação</th>
        </tr>
      </thead>

      <tbody>

        <!-- ========================================================= -->
        <!-- MINICURSOS -->
        <!-- ========================================================= -->

        <tr>
          <td class="time-cell">08:00 – 12:00</td>

          <td class="course">
            <strong>Minicurso I</strong> - Uso do LaTeX na escrita de trabalhos acadêmicos
          </td>

          <td class="course">
            <strong>Minicurso II</strong> - a definir
          </td>

          <td class="course">
            <strong>Minicurso III</strong> - a definir
          </td>

          <td class="observation">
            Minicursos ainda são provisórios
          </td>
        </tr>


        <!-- ========================================================= -->
        <!-- SESSÕES TÉCNICAS -->
        <!-- ========================================================= -->

        <tr>
          <td class="time-cell">14:00 – 18:00</td>

          <td class="session">
            <strong>Sessão Técnica I</strong> - Trabalhos aceitos
          </td>

          <td class="session">
            <strong>Sessão Técnica II</strong> - Trabalhos aceitos
          </td>

          <td class="session">
            <strong>Sessão Técnica III</strong> - Trabalhos aceitos
          </td>

          <td class="observation"></td>
        </tr>


        <!-- ========================================================= -->
        <!-- CREDENCIAMENTO -->
        <!-- ========================================================= -->

        <tr>
          <td class="time-cell">19:00 – 19:30</td>

          <td class="soft-blue">
            <strong>Coffee break / Credenciamento</strong>
          </td>

          <td></td>

          <td></td>

          <td class="observation"></td>
        </tr>


        <!-- ========================================================= -->
        <!-- ABERTURA / COFFEE BREAK -->
        <!-- ========================================================= -->

        <tr>
          <td class="time-cell">19:30 – 20:00</td>

          <td class="soft-blue">
            <strong>Abertura Oficial da ERES 2026</strong>
          </td>

          <td class="full-row">
            Coffee Break
          </td>

          <td class="full-row">
            Coffee Break
          </td>

          <td class="observation"></td>
        </tr>


        <!-- ========================================================= -->
        <!-- PALESTRAS -->
        <!-- ========================================================= -->

        <tr>
          <td class="time-cell">20:10 – 21:10</td>

          <td class="lecture">
            <strong>Palestra I</strong> - Gestão da Transparência de Dados Pessoais
            e relacionamento com User Experience.<br><br>

            <strong>Prof. Dr. Morandini - USP</strong>
          </td>

          <td class="lecture">
            <strong>Palestra II</strong> - Alguns desafios e obstáculos na Engenharia
            de Sistemas de Softwares Contemporâneos.<br><br>

            <strong>Prof. Dr. Guilherme Horta Travassos - UFRJ</strong>
          </td>

          <td class="lecture">
            <strong>Palestra III</strong> - Pesquisa Científica Aplicada a Startups
            de Software.<br><br>

            <strong>Prof(a). Dra. Gislane Camila Lapasini Leal - UEM</strong>
          </td>

          <td class="observation">
            Os títulos e temas das palestras ainda são provisórios
          </td>
        </tr>


        <!-- ========================================================= -->
        <!-- PERGUNTAS -->
        <!-- ========================================================= -->

        <tr>
          <td class="time-cell">21:10 – 21:20</td>

          <td class="soft-blue">
            <strong>Abertura para dúvidas / Perguntas</strong>
          </td>

          <td class="soft-blue">
            <strong>Abertura para dúvidas / Perguntas</strong>
          </td>

          <td class="soft-blue">
            <strong>Abertura para dúvidas / Perguntas</strong>
          </td>

          <td class="observation"></td>
        </tr>


        <!-- ========================================================= -->
        <!-- ENCERRAMENTO -->
        <!-- ========================================================= -->

        <tr>
          <td class="time-cell">21:30</td>

          <td></td>

          <td></td>

          <td class="soft-blue">
            <strong>Encerramento / Premiações / Jantar</strong>
          </td>

          <td class="observation">
            O jantar será por adesão, com local e valor a serem definidos
          </td>
        </tr>


        <!-- ========================================================= -->
        <!-- WOMENS -->
        <!-- ========================================================= -->

        <tr>
          <td colspan="5" class="hard-blue">
            1º WOMENS
          </td>
        </tr>


        <!-- WOMENS MANHÃ -->

        <tr>
          <td class="time-cell">Manhã</td>

          <td></td>

          <td></td>

          <td class="soft-blue">
            <strong>
              Oficina Gurias of Code
            </strong>
            <br>
            (WOMENS)
          </td>

          <td class="observation">
            Atividade extensionista destinada a estudantes do ensino médio de escolas de Toledo. Informações sobre inscrições, escolas participantes e vagas serão divulgadas posteriormente.
          </td>
        </tr>


        <!-- ALMOÇO WOMENS -->

        <tr>
          <td class="time-cell">Almoço</td>

          <td></td>

          <td></td>

          <td class="full-row">
            Almoço
          </td>

          <td class="observation"></td>
        </tr>


        <!-- WOMENS TARDE -->

        <tr>
          <td class="time-cell">Tarde</td>

          <td></td>

          <td></td>

          <td class="soft-blue">
            <strong>
              Fórum de Mulheres em Engenharia de Software
            </strong>
            <br>
            (WOMENS)
          </td>

          <td class="observation">
            Painel/mesa-redonda com convidadas de diferentes trajetórias acadêmicas e profissionais.
          </td>
        </tr>


        <!-- WOMENS NOITE -->

        <tr>
          <td class="time-cell">Noite</td>

          <td></td>

          <td></td>

          <td class="soft-blue">
            <strong>
              Palestra
            </strong>
            <br>
            (WOMENS)
          </td>

          <td class="observation">
            Programação a ser divulgada posteriormente pela organização do Workshop.
          </td>
        </tr>


        <!-- ========================================================= -->
        <!-- VISITAS TÉCNICAS -->
        <!-- ========================================================= -->

        <tr>
          <td colspan="5" class="hard-green">
            Visitas Técnicas
          </td>
        </tr>

      </tbody>

    </table>

  </div>

</main>
