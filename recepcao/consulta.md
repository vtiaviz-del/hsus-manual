---
description: Avaliação médica, prescrição, exames, receita, atestado e encaminhamento.
icon: stethoscope
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
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# Consulta

Na consulta, o médico registra o diagnóstico, a prescrição e os exames e decide o **encaminhamento** do paciente. O encaminhamento define para qual setor o paciente vai.

{% stepper %}
{% step %}
### Registre a avaliação e o encaminhamento

Abra o atendimento e clique na aba **Consulta**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/consulta-avaliacao.png" alt="Avaliação médica e encaminhamento"><figcaption><p>Avaliação médica e encaminhamento</p></figcaption></figure></div>

1. Confira o **médico responsável**. Ele vem com o médico conectado; se a consulta foi de outro médico, escolha o nome na lista.
2. Escreva o **diagnóstico**.
3. Escreva o **plano de cuidado**: condutas, cuidados e orientações.
4. Escolha o **encaminhamento**:
   * **Ambulatório:** o paciente fica em observação e vai para [Em observação](../ambulatorio/em-observacao.md).
   * **Enfermaria:** o paciente será internado e vai para [Internações](../enfermaria/internacoes.md), aguardando admissão.
   * **Alta:** o atendimento termina aqui.
{% endstep %}

{% step %}
### Prescreva os medicamentos e peça os exames

<div data-with-frame="true"><figure><img src="../.gitbook/assets/consulta-prescricao.png" alt="Prescrição e solicitação de exames"><figcaption><p>Prescrição e solicitação de exames</p></figcaption></figure></div>

1. Em **Prescrição de medicamentos**, clique em **Adicionar medicação** e preencha a medicação e a posologia. Repita para cada uma. A lixeira remove a linha.
2. Em **Solicitação de exames**, clique em **Adicionar exame** para cada exame, com uma observação se precisar (por exemplo, "em jejum").
{% endstep %}

{% step %}
### Gere a receita e o atestado, se precisar

<div data-with-frame="true"><figure><img src="../.gitbook/assets/consulta-receita-atestado.png" alt="Receita e atestado"><figcaption><p>Receita e atestado</p></figcaption></figure></div>

1. **Receita:** escolha o tipo (**simples** ou **controle especial**), escreva as orientações e clique em **Gerar receita**. A receita usa os medicamentos da prescrição.
2. **Atestado:** informe os **dias de afastamento**, a data de início e as observações e clique em **Gerar atestado**.
3. Clique em **Salvar** para gravar a consulta.
{% endstep %}
{% endstepper %}

{% hint style="success" %}
A consulta fica concluída quando o encaminhamento é definido. O paciente sai da lista de Entradas e aparece no setor escolhido.
{% endhint %}

## Receita e atestado prontos para imprimir

Os documentos abrem em uma nova janela, com o botão **Imprimir / salvar PDF**.

{% columns %}
{% column %}
<figure><img src="../.gitbook/assets/documento-receita.png" alt="Receita médica"><figcaption><p>Receita médica</p></figcaption></figure>
{% endcolumn %}

{% column %}
<figure><img src="../.gitbook/assets/documento-atestado.png" alt="Atestado médico"><figcaption><p>Atestado médico</p></figcaption></figure>
{% endcolumn %}
{% endcolumns %}

## Para onde vão a prescrição e os exames

* No **ambulatório**, os medicamentos aparecem para o check-in de administração.
* Na **enfermaria**, os medicamentos aparecem para o check-in na admissão e entram no aprazamento. Os exames aparecem para o check-in de coleta.
