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
    min-width: 850px;
    border-collapse: collapse;
    table-layout: fixed;
  }

  .programacao-table th,
  .programacao-table td {
    border: 1px solid #d1d1d1;
    padding: 8px;
    text-align: left;
    vertical-align: top;
    box-sizing: border-box;
  }

  .programacao-table th {
    text-align: center;
  }

  .programacao-table .time-cell {
    width: 130px;
    background-color: #f0f0f0;
    text-align: center;
    font-weight: bold;
    white-space: nowrap;
  }

  .programacao-table .full-row {
    text-align: center;
    font-weight: bold;
    background-color: #f5f5f5;
  }

  .programacao-table .course {
    background-color: #e6f7e6;
  }

  .programacao-table .session {
    background-color: #fff9e6;
  }

  .programacao-table .lecture {
    background-color: #fbeaea;
  }

  .programacao-table .hard-blue {
    background-color: #e6ecf7;
    text-align: center;
    font-weight: bold;
  }

  .programacao-table .soft-blue {
    background-color: #f2f7ff;
  }

  .programacao-table .header-green {
    background-color: #e6f3e6;
  }

  .programacao-table .header-purple {
    background-color: #eae6f7;
  }

  .programacao-table .header-red {
    background-color: #f7e6e6;
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
          <th class="time-cell">Hora</th>
          <th class="header-green">Quarta-feira<br>14/10</th>
          <th class="header-purple">Quinta-feira<br>15/10</th>
          <th class="header-red">Sexta-feira<br>16/10</th>
        </tr>
      </thead>

      <tbody>

        <!-- Manhã -->
        <tr>
          <td class="time-cell">08:00 – 12:00</td>

          <td class="course">
            <!--
            <a href="{{ site.baseurl }}/programacao/minicursos/#minicurso1">
              Minicurso 1
            </a>
            -->
          </td>

          <td class="course">
            <!--
            <a href="{{ site.baseurl }}/programacao/minicursos/#minicurso2">
              Minicurso 2
            </a>
            -->
          </td>

          <td class="course">
            <!--
            <a href="{{ site.baseurl }}/programacao/minicursos/#minicurso3">
              Minicurso 3
            </a>
            -->
          </td>
        </tr>

        <!-- Almoço -->
        <tr>
          <td class="time-cell">12:00 – 13:30</td>
          <td colspan="3" class="full-row">Almoço</td>
        </tr>

        <!-- Abertura -->
        <tr>
          <td class="time-cell">13:30 – 14:00</td>

          <td class="soft-blue">
            <strong>Abertura do Evento</strong>
          </td>

          <td></td>
          <td></td>
        </tr>

        <!-- Início da tarde -->
        <tr>
          <td class="time-cell">14:00 – 16:00</td>

          <td class="session">
            <!--
            <a href="{{ site.baseurl }}/programacao/sessoes/#sessao1">
              Sessão Técnica 1
            </a>
            -->
          </td>

          <td class="session">
            <!--
            <a href="{{ site.baseurl }}/programacao/sessoes/#sessao4">
              Sessão Técnica 4
            </a>
            -->
          </td>

          <td class="session">
            <!--
            <a href="{{ site.baseurl }}/programacao/sessoes/#sessao7">
              Sessão Técnica 7
            </a>
            -->
          </td>
        </tr>

        <!-- Coffee-break -->
        <tr>
          <td class="time-cell">16:00 – 16:30</td>
          <td colspan="3" class="full-row">Coffee-break</td>
        </tr>

        <!-- Final da tarde -->
        <tr>
          <td class="time-cell">16:30 – 18:15</td>

          <td class="session">
            <!--
            <a href="{{ site.baseurl }}/programacao/sessoes/#sessao3">
              Sessão Técnica 3
            </a>
            -->
          </td>

          <td class="session">
            <!--
            <a href="{{ site.baseurl }}/programacao/sessoes/#sessao5">
              Sessão Técnica 5
            </a>
            -->
          </td>

          <td class="session">
            <!--
            <a href="{{ site.baseurl }}/programacao/sessoes/#sessao8">
              Sessão Técnica 8
            </a>
            -->
          </td>
        </tr>

        <!-- Premiação -->
        <tr>
          <td class="time-cell">18:00</td>
          <td></td>
          <td></td>

          <td class="soft-blue">
            <!--
            <strong>Premiação do Evento</strong>
            -->
          </td>
        </tr>

        <!-- Intervalo -->
        <tr>
          <td class="time-cell">18:15 – 19:00</td>
          <td colspan="3" class="full-row">Intervalo</td>
        </tr>

        <!-- Palestras -->
        <tr>
          <td class="time-cell">19:00 – 20:00</td>

          <td class="lecture">
            <!--
            <a href="{{ site.baseurl }}/programacao/palestras/#palestra1">
              Palestra 1
            </a>
            -->
          </td>

          <td class="lecture">
            <!--
            <a href="{{ site.baseurl }}/programacao/palestras/#palestra3">
              Palestra 3
            </a>
            -->
          </td>

          <td class="lecture">
            <!--
            <a href="{{ site.baseurl }}/programacao/palestras/#palestra5">
              Palestra 5
            </a>
            -->
          </td>
        </tr>

        <!-- Coffee-break -->
        <tr>
          <td class="time-cell">20:00 – 20:30</td>
          <td colspan="3" class="full-row">Coffee-break</td>
        </tr>

        <!-- Últimas palestras -->
        <tr>
          <td class="time-cell">20:30 – 21:30</td>

          <td class="lecture"></td>

          <td class="lecture">
            <!--
            <a href="{{ site.baseurl }}/programacao/palestras/#palestra6">
              Palestra 6
            </a>
            -->
          </td>

          <td class="lecture">
            <!--
            <a href="{{ site.baseurl }}/programacao/palestras/#palestra4">
              Palestra 4
            </a>
            -->
          </td>
        </tr>

        <!-- Encerramento -->
        <tr>
          <td class="time-cell">21:30</td>
          <td class="soft-blue"></td>
          <td class="soft-blue"></td>
          <td class="hard-blue">Encerramento</td>
        </tr>

      </tbody>
    </table>

  </div>
</main>
