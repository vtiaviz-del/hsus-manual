---
description: Transferência para atendimento por telemedicina.
icon: video
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

# Para telemedicina

Destino para o paciente que será atendido por **teleconsulta**.

{% stepper %}
{% step %}
### Abra a aba Telemedicina

Abra o atendimento da transferência e clique na aba **Telemedicina** (1).

<div data-with-frame="true"><figure><img src="../imagens/transf-telemedicina.png" alt="Aba Telemedicina antes do registro"><figcaption><p>Aba Telemedicina antes do registro</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Registre a teleconsulta

Clique em **Registrar Telemedicina** (2). O sistema salva o atendimento e marca a data e a hora.

O botão muda para **Telemedicina registrada** (1), com a data e a hora logo abaixo (2), e um aviso confirma. O atendimento vai para [Finalizados › Encaminhamentos](../finalizados/encaminhamentos.md).

<div data-with-frame="true"><figure><img src="../imagens/transf-telemedicina-registrada.png" alt="Telemedicina registrada"><figcaption><p>Telemedicina registrada</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Nesta versão, o sistema registra a teleconsulta no atendimento. A ligação com a plataforma de telemedicina depende da integração configurada no hospital.
{% endhint %}
