<p align="center">
  <img src="./logo.svg" width="140" alt="Logo EduAcompanha">
</p>

<h1 align="center">EduAcompanha</h1>
<p align="center"><b>Busca ativa escolar, sem papel.</b></p>

---

## Sobre

O EduAcompanha é um sistema para a secretaria de uma escola pública estadual controlar a frequência de falta dos alunos,
notificar os responsáveis automaticamente, e acompanhar quem está em evasão, substituindo o trabalho manual que era realizado.

Este repositório contém a **aplicação em Java**, executada pelo **terminal** por meio de um menu e
conectada a um **banco de dados MySQL**.

## O que o sistema faz

- **Acesso:** login com dois perfis, Administrador (equipe, todas as escolas) e Secretaria (uma escola)
- **Cadastros:** escolas, usuários, disciplinas, turmas, grade horária, alunos, matrículas, responsáveis e telefones
- **Frequência:** Controle das faltas, saída antecipadas e retornos por aluno e turma, com cálculo automático do percentual de cada aluno e cancelamento de lançamentos com motivo
- **Notificação:** fila de avisos aos responsáveis a cada falta, passando para o próximo telefone quando não há resposta em 24 horas
- **Alerta de evasão:** lista os alunos abaixo de 75% (crítico, mínimo da LDB) e entre 75% e 80% (atenção)
- **Busca Ativa Escolar:** abertura de casos, registro de tentativas de contato, ações e encaminhamentos
- **Relatórios** com os dados de frequência e dos casos

## Tecnologias

`Java` · `Maven` · `JDBC` · `MySQL` ·


## Protótipo web

As telas e o fluxo de uso foram validados antes em um protótipo web, independente deste código.

## Equipe Nitrix

| Integrante | Função |
|---|---|
| Cristhian Felicio Toledo | Dev Back-end, Engenheiro de Testes, Product Owner |
| Matheus S. Escaramboni | Gestor do Projeto, Scrum Master, Analista de Banco de Dados |
| Bruno Soares Cunha | Desenvolvedor Front-end, Analista de Requisitos |
| Lucas Alexandre R. Sandim | Analista de Banco de Dados |
| Luan de Libório Granado | Analista de Viabilidade, Consultor de Usabilidade |

Orientador: Eliney Sabino · Centro Universitário Facens

<p align="center">
  <img data-importer="snake" src="https://raw.githubusercontent.com/nitrixfacens/nitrixfacens/snake-output/snake.svg" alt="Snake animation" />
</p>
