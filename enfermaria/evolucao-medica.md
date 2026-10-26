---
description: Registro da evolução médica, com prescrição e exames.
icon: user-doctor
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Evolução médica

A aba **Evolução médica** registra o acompanhamento do médico durante a internação: hipótese diagnóstica, estado do paciente, plano, prescrição e exames. Também é nela que se [finaliza a internação](finalizar-internacao.md).

<div data-with-frame="true"><figure><img src="../imagens/med-aba.png" alt="Aba Evolução médica" width="560"><figcaption><p>Aba Evolução médica</p></figcaption></figure></div>

1. **Diagnóstico inicial:** o diagnóstico da consulta, para referência.
2. **Novo:** abre o formulário de um novo acompanhamento.
3. **Histórico de acompanhamentos:** as evoluções médicas e os registros de permanência.
4. **Finalizar internação / encaminhamento:** a saída do paciente.

## Registrar uma evolução

{% stepper %}
{% step %}
### Abra o formulário e escreva a avaliação

Clique em **Novo**.

<div data-with-frame="true"><figure><img src="../imagens/med-novo.png" alt="Novo acompanhamento médico" width="560"><figcaption><p>Novo acompanhamento médico</p></figcaption></figure></div>

1. Confira a **data**, a **hora** e o **médico**. O médico é obrigatório.
2. Escreva a **hipótese diagnóstica** e o **plano de cuidado**.
3. Abra **Sinais vitais** se quiser registrar PA, temperatura, FC, FR, SpO₂ e peso.

Mais abaixo, descreva o **estado do paciente** e as **anotações**.
{% endstep %}

{% step %}
### Prescreva e peça exames

<div data-with-frame="true"><figure><img src="../imagens/med-novo-prescricao.png" alt="Prescrição e exames da evolução médica" width="560"><figcaption><p>Prescrição e exames da evolução médica</p></figcaption></figure></div>

1. Em **Prescrição de medicamentos**, adicione os novos medicamentos com a posologia.
2. Em **Solicitação de exames**, adicione os exames pedidos.
3. Clique em **Registrar evolução médica**.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
Preencha ao menos um campo do acompanhamento (texto, prescrição ou exame). Evolução vazia não é registrada.
{% endhint %}

## O que a prescrição e os exames geram

* Os **medicamentos prescritos** entram no [aprazamento](evolucao-de-enfermagem.md#aprazamento) da enfermagem, a partir do próximo horário da tabela.
* Os **exames solicitados** aparecem nas **coletas pendentes** da evolução de enfermagem.

Para corrigir ou anular uma evolução médica, veja [Editar ou excluir uma evolução](editar-ou-excluir-evolucao.md).
