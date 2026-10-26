---
description: Aprazamento de medicação e registro da evolução de enfermagem.
icon: user-nurse
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

# Evolução de enfermagem

A aba **Evolução de enfermagem** reúne o aprazamento das medicações e as evoluções de cada plantão: doses administradas, coletas de exames, sinais vitais, estado do paciente e anotação.

<div data-with-frame="true"><figure><img src="../imagens/enf-aba.png" alt="Aba Evolução de enfermagem" width="560"><figcaption><p>Aba Evolução de enfermagem</p></figcaption></figure></div>

1. **Aviso de medicação:** doses atrasadas ou a próxima medicação do dia.
2. **Novo:** abre o formulário de uma nova evolução.
3. **Aprazamento de medicações:** os horários de cada medicamento prescrito.
4. **Histórico de evoluções:** as evoluções registradas, da mais recente para a mais antiga.

## Aprazamento

Abra **Aprazamento de medicações** para ver e ajustar os horários de cada medicamento prescrito, na consulta ou nas evoluções médicas.

<div data-with-frame="true"><figure><img src="../imagens/enf-aprazamento.png" alt="Aprazamento de medicações" width="560"><figcaption><p>Aprazamento de medicações</p></figcaption></figure></div>

1. **Intervalo e início:** 6/6, 8/8, 12/12 ou 24/24 horas, **Dose única** ou **Se necessário**. O sistema lê o intervalo da posologia ("EV 12/12h", por exemplo) e sugere o início pela tabela do hospital. Mudou? A mudança vale para o paciente e é gravada na hora.
2. **Sequência de horários** do dia.
3. **Situação de cada horário hoje:**

| Etiqueta | Significado |
| --- | --- |
| ✓ 12H #2 · 12:05 | Dose registrada na evolução nº 2, às 12:05 |
| ⚠ 06H (vermelha) | Dose atrasada, sem registro |
| 18H | Dose pendente, ainda no horário |

{% hint style="info" %}
**Primeira dose:** a medicação da consulta tem a 1ª dose na admissão e as próximas pela tabela. A medicação de evolução médica começa no próximo horário da tabela depois da prescrição.
{% endhint %}

## Registrar uma evolução

{% stepper %}
{% step %}
### Abra o formulário e registre as medicações

Clique em **Novo**.

<div data-with-frame="true"><figure><img src="../imagens/enf-novo-medicacoes.png" alt="Nova evolução: medicações e coletas" width="560"><figcaption><p>Nova evolução: medicações e coletas</p></figcaption></figure></div>

1. Confira a **data**, a **hora** e o **profissional**. O profissional vem com o usuário conectado, se for da enfermagem.
2. Marque o **acompanhamento**: total, parcial ou não realizado.
3. Escolha o **horário da medicação**. O sistema já sugere o horário pendente mais próximo.
4. Marque cada medicamento administrado naquele horário. Em **Se necessário e dose única**, marque o que foi dado fora dos horários fixos.
5. Em **Coletas pendentes**, marque os exames coletados.
{% endstep %}

{% step %}
### Registre sinais vitais, estado e anotação

<div data-with-frame="true"><figure><img src="../imagens/enf-novo-sinais.png" alt="Sinais vitais, estado e anotação" width="560"><figcaption><p>Sinais vitais, estado e anotação</p></figcaption></figure></div>

1. **Sinais vitais:** PA, temperatura, FC, FR, SpO₂ e glicemia (HGT).
2. **Estado:** diurese, evacuação, verbalização, deambulando, aceitando dieta e acesso venoso (AVP).
3. **Anotação de enfermagem.** Ela é obrigatória.
4. Clique em **Registrar evolução**.
{% endstep %}

{% step %}
### Confira no histórico

A nova evolução aparece no topo do histórico (1) e um aviso confirma o registro (2). As doses marcadas passam a aparecer como ✓ no aprazamento.

<div data-with-frame="true"><figure><img src="../imagens/enf-registrada.png" alt="Evolução registrada" width="560"><figcaption><p>Evolução registrada</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Registrou depois do horário? Informe a data e a hora reais do atendimento. O sistema guarda também o momento do lançamento, e o prontuário mostra os dois.
{% endhint %}

Para corrigir ou anular uma evolução, veja [Editar ou excluir uma evolução](editar-ou-excluir-evolucao.md).
