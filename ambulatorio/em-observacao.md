---
description: Acompanhamento do paciente em observação no ambulatório.
icon: eye
cover: ../.gitbook/assets/capa-ambulatorio.png
coverY: 0
layout:
  width: wide
  cover:
    visible: true
    size: full
    mask: none
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

# Em observação

Em **Ambulatório › Em observação** ficam os pacientes encaminhados para o ambulatório na consulta, ou transferidos com esse destino. Aqui a equipe registra a medicação administrada, os procedimentos e as anotações, e decide se o paciente recebe **alta** ou vai para **internação**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/obs-visao-geral.png" alt="Tela Em observação"><figcaption><p>Tela Em observação</p></figcaption></figure></div>

1. **Busca e filtros:** procure por nome, CPF, CNS ou telefone.
2. **Lista de pacientes:** cada paciente mostra a classificação de risco e etiquetas com o andamento, como "Medicação 1/2" (um de dois medicamentos administrados) e "Encaminhamento" (ainda sem destino).
3. **Resumo do paciente:** dados pessoais, alergias, sinais vitais da triagem, queixa, diagnóstico inicial, plano de cuidado e médico responsável.

O filtro **Medicação pendente** (1) mostra só quem ainda tem medicamento sem check-in (2):

<div data-with-frame="true"><figure><img src="../.gitbook/assets/obs-filtro.png" alt="Filtro Medicação pendente"><figcaption><p>Filtro Medicação pendente</p></figcaption></figure></div>

## Registrar o acompanhamento

{% stepper %}
{% step %}
### Faça o check-in dos medicamentos

Clique no paciente na lista. Em **Check-in de medicamentos** (1) estão os medicamentos prescritos na consulta. Marque a caixa ao administrar: o horário e o seu nome são gravados **na hora**, sem precisar salvar. Se marcou por engano, desmarque; o desfazer também fica registrado.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/obs-checkin.png" alt="Check-in de medicamentos"><figcaption><p>Check-in de medicamentos</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Registre os procedimentos

Em **Procedimentos realizados** (1), clique em **Adicionar procedimento** (2), descreva o procedimento e confira a hora, que já vem com o horário atual.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/obs-procedimento.png" alt="Procedimentos realizados"><figcaption><p>Procedimentos realizados</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Escreva a anotação de enfermagem

As anotações anteriores ficam listadas (1). Escreva a nova anotação (2): evolução, intercorrências e orientações. Ela recebe a hora em que você salvar.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/obs-anotacao.png" alt="Anotação de enfermagem"><figcaption><p>Anotação de enfermagem</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Encaminhe e salve

Quando o paciente for sair da observação, escolha **Alta** ou **Internação** (1) e clique em **Salvar** (2). **Descartar** desfaz o que não foi salvo.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/obs-encaminhar.png" alt="Encaminhamento da observação"><figcaption><p>Encaminhamento da observação</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Ao salvar com um encaminhamento, o paciente sai da observação:

* **Alta:** o atendimento vai para [Finalizados › Ambulatório](../finalizados/ambulatorio.md).
* **Internação:** o paciente aparece em [Internações](../enfermaria/internacoes.md), aguardando admissão. O atendimento também fica em Finalizados › Ambulatório como "Internação".
{% endhint %}

{% hint style="info" %}
Você pode salvar quantas vezes quiser sem encaminhamento, por exemplo para registrar procedimentos e anotações ao longo do plantão.
{% endhint %}
