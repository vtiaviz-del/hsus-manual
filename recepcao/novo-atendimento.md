---
description: Como abrir o atendimento de um paciente que chegou ao hospital.
icon: user-plus
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

# Novo atendimento

Use a origem **Novo** para o paciente que procurou o hospital por conta própria. O atendimento passa por três etapas, sempre nesta ordem:

| Etapa                             | Quem faz   | Fica concluída quando                           |
| --------------------------------- | ---------- | ----------------------------------------------- |
| [Identificação](identificacao.md) | Recepção   | CNS, nome da mãe e logradouro estão preenchidos |
| [Triagem](triagem.md)             | Enfermagem | A classificação de risco é escolhida            |
| [Consulta](consulta.md)           | Médico     | O encaminhamento é definido                     |

Cada aba só libera depois que a anterior for **salva e concluída**. Enquanto isso, ela aparece com um cadeado.

## Abrir o atendimento

{% stepper %}
{% step %}
### Clique em Novo

Clique em **Novo** (1). O formulário à direita fica em branco, com o título **Novo atendimento** (2).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/novo-abrir.png" alt="Formulário de novo atendimento aberto"><figcaption><p>Formulário de novo atendimento aberto</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Preencha os dados da chegada

1. Se quiser, escolha a **cor do perfil**. As iniciais aparecem sozinhas a partir do nome.
2. Digite o **nome completo**.
3. Escreva o **relato**: o motivo da procura, com as palavras do paciente.
4. Confira a **data e a hora** da chegada. Elas vêm com o momento atual.
5. Em **Origem**, escolha **Novo**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/novo-preencher.png" alt="Dados da chegada preenchidos"><figcaption><p>Dados da chegada preenchidos</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Paciente que já veio antes? Use a sugestão

Ao digitar o nome (1), o sistema mostra os pacientes já atendidos (2). Escolha o nome na lista e a **identificação** e as **alergias** são preenchidas sozinhas. O mesmo vale para o CNS e o CPF.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/novo-sugestao.png" alt="Sugestões de pacientes já atendidos"><figcaption><p>Sugestões de pacientes já atendidos</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Salve

Role até o fim do formulário e clique em **Salvar**. O atendimento entra na lista (1), as abas das etapas aparecem (2) e um aviso mostra o que ainda falta (3).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/novo-salvo.png" alt="Atendimento salvo"><figcaption><p>Atendimento salvo</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

{% hint style="info" %}
Para salvar, bastam nome, relato, data, hora e origem. Assim você registra a chegada rapidamente e completa o resto depois.
{% endhint %}

Continue em [Identificação](identificacao.md).
