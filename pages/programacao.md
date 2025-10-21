---
layout: page-fullwidth
show_meta: false
title: "Programação Geral"
permalink: "/programacao/"
header:
  image_fullwidth: ERES-2025_Logo.svg
---

<style>
  table {
    width: 100%;
    border-collapse: collapse;
  }

  th, td {
    border: 1px solid #d1d1d1;
    padding: 8px;
    text-align: left;
  }

  .full-row {
    text-align: center;
    font-weight: bold;
    background-color: #f5f5f5;
  }

  .course {
    background-color: #e6f7e6;
  }

  .session {
    background-color: #fff9e6;
  }

  .lecture {
    background-color: #fbeaea;
  }

  .hard-blue {
    background-color: #e6ecf7;
  }

  .soft-blue {
    background-color: #f2f7ff;
  }

  .header-green {
    background-color: #e6f3e6;
  }

  .header-purple {
    background-color: #eae6f7;
  }

  .header-red {
    background-color: #f7e6e6;
  }

  .time-cell {
    background-color: #f0f0f0;
  }
</style>

<main>
  <table>
    <thead>
      <tr>
        <th class="time-cell">Hora</th>
        <th class="header-green">Quarta (29/10)</th>
        <th class="header-purple">Quinta (30/10)</th>
        <th class="header-red">Sexta (31/10)</th>
      </tr>
    </thead>
    <tbody>
      <!-- Manhã: Minicursos -->
      <tr>
        <td class="time-cell">08:00 – 12:00</td>
        <td class="course">
          <a href="{{ site.baseurl }}/programacao/minicursos/#minicurso1">
            Minicurso: Guia de IA pro empreendedor-programador (RÁPIDO | ATUALIZADO 2025)
          </a><br>
          Instrutor: Renato Mello Konflanz<br>
          <em>Sala a confirmar</em>
        </td>
        <td class="course">
          <a href="{{ site.baseurl }}/programacao/minicursos/#minicurso2">
            Minicurso: Da Ideia ao Deploy — Construindo e Publicando Aplicações Web Modernas
          </a><br>
          Instrutor: Bernardo Zanetti<br>
          <em>Sala a confirmar</em>
        </td>
        <td class="course">
          <a href="{{ site.baseurl }}/programacao/minicursos/#minicurso3">
            Minicurso: Da Ideia ao Deploy — UX para pessoas de TI: criando softwares que as pessoas amam usar
          </a><br>
          Instrutor: Jean Carlos da Campo<br>
          <em>Sala a confirmar</em>
        </td>
      </tr>

      <!-- Almoço -->
      <tr>
        <td class="time-cell">12:00 – 14:00</td>
        <td colspan="3" class="full-row">Almoço</td>
      </tr>

      <!-- Tarde: Sessões Técnicas (29/10) -->
      <tr>
        <td class="time-cell">14:00 – 16:00</td>
        <td class="session">
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao1">
            Sessão Técnica 1 – Engenharia de Software Experimental e Qualidade
          </a>
        </td>
        <td class="session">
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao4">
            Sessão Técnica 4 – Testes e Validação de Software
          </a>
        </td>
        <td class="session">
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao7">
            Sessão Técnica 7 – Educação em Computação e Extensão Universitária
          </a>
        </td>
      </tr>

      <!-- Intervalo da tarde -->
      <tr>
        <td class="time-cell">16:00 – 16:30</td>
        <td colspan="3" class="full-row">Intervalo</td>
      </tr>

      <!-- Tarde: Sessões Técnicas (pós-intervalo) -->
      <tr>
        <td class="time-cell">16:30 – 18:15</td>
        <td class="session">
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao3">
            Sessão Técnica 3 – IA e Aprendizado de Máquina em ES
          </a><br>
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao9">
            Sessão Técnica 9 – Arquitetura e Microsserviços
          </a>
        </td>
        <td class="session">
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao5">
            Sessão Técnica 5 – Requisitos e Usabilidade
          </a><br>
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao6">
            Sessão Técnica 6 – Aplicações Web e Full Stack
          </a>
        </td>
        <td class="session">
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao8">
            Sessão Técnica 8 – Aplicações em Engenharia de Software
          </a><br>
          <a href="{{ site.baseurl }}/programacao/sessoes/#sessao10">
            Sessão Técnica 10 – Desenvolvimento de APIs e Ontologias
          </a>
        </td>
      </tr>

      <!-- Jantar -->
      <tr>
        <td class="time-cell">18:15 – 19:00</td>
        <td colspan="3" class="full-row">Jantar</td>
      </tr>

      <!-- Noite: Palestras 19:00 -->
      <tr>
        <td class="time-cell">19:00 – 20:00</td>
        <td class="lecture">
          <a href="{{ site.baseurl }}/programacao/palestras/#palestra1">
            Palestra: Prof. Edson Oliveira Junior — Towards Open Software Engineering
          </a>
        </td>
        <td class="lecture">
          <a href="{{ site.baseurl }}/programacao/palestras/#palestra3">
            Palestra: Prof. Raul Sidnei Wazlawick — Desenvolvimento de software Centrado no Usuário
          </a>
        </td>
        <td class="lecture">
          <a href="{{ site.baseurl }}/programacao/palestras/#palestra5">
            Palestra: Prof. Graziela Simone Tonin — ES em Transição: Legados, IA e Sustentabilidade
          </a>
        </td>
      </tr>

      <!-- Coffee-break -->
      <tr>
        <td class="time-cell">20:00 – 20:30</td>
        <td colspan="3" class="full-row">Coffee-break</td>
      </tr>

      <!-- Noite: Palestras 20:30 -->
      <tr>
        <td class="time-cell">20:30 – 21:30</td>
        <td class="lecture">
          <!-- Se houver segunda palestra nesta noite, linke aqui; caso contrário, mantenha em branco -->
          <!-- Exemplo (se aplicável): <a href="{{ site.baseurl }}/programacao/palestras/#palestraX">Palestra X</a> -->
        </td>
        <td class="lecture">
          <a href="{{ site.baseurl }}/programacao/palestras/#palestra4">
            Palestra: Prof. Guilherme Henrique Piasson — Do Código à Cabine: ES na Aviação
          </a>
        </td>
        <td class="lecture">
          <a href="{{ site.baseurl }}/programacao/palestras/#palestra6">
            Palestra: Prof. Ana Márcia Debiasi Duarte — Testes têm cheiro, e não é bom!
          </a>
        </td>
      </tr>

      <!-- Encerramentos/Happy Hours -->
      <tr>
        <td class="time-cell">21:30</td>
        <td class="soft-blue">
          Happy Hour — <strong>Sose7e</strong> (pão com linguiça)<br>
          R. Itaboraí, 195 – Efapi, Chapecó – SC
          <br><a href="{{ site.baseurl }}/programacao/happy-hour/">Detalhes</a>
        </td>
        <td class="soft-blue">
          Happy Hour — <strong>Saudoso</strong> (apresente o crachá e ganhe 1 chopp)<br>
          Av. Getúlio Dorneles Vargas, 1520N – Centro, Chapecó – SC
          <br><a href="{{ site.baseurl }}/programacao/happy-hour/">Detalhes</a>
        </td>
        <td class="hard-blue">Encerramento</td>
      </tr>
    </tbody>
  </table>
</main>
