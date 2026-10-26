---
description: Transferência para coleta de exames e envio ao LabSUS.
icon: flask
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

# Para exames

Destino para o paciente que vem ao hospital **só para fazer exames**.

{% stepper %}
{% step %}
### Abra a aba Exames

Abra o atendimento da transferência e clique na aba **Exames** (1).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/transf-exames.png" alt="Aba Exames da transferência"><figcaption><p>Aba Exames da transferência</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Liste os exames pedidos

Em **Solicitação de exames** (2), clique em **Adicionar exame** e preencha o exame e a observação. Repita para cada exame da guia.
{% endstep %}

{% step %}
### Envie para o LabSUS

Clique em **Enviar para LabSUS** (3). O sistema salva o atendimento e registra o envio.

Depois do envio, o botão muda para **Enviado para LabSUS** (1) e mostra a data e a hora (2). O atendimento vai para [Finalizados › Encaminhamentos](../finalizados/encaminhamentos.md).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/transf-exames-enviado.png" alt="Exames enviados ao LabSUS"><figcaption><p>Exames enviados ao LabSUS</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
É preciso ter ao menos um exame na lista para enviar.
{% endhint %}

{% hint style="info" %}
Nesta versão, o sistema registra o envio no atendimento. A transmissão automática dos pedidos para o LabSUS depende da integração configurada no hospital.
{% endhint %}
