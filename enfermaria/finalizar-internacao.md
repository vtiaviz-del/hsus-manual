---
description: Registrar a saída (alta, óbito, transferência) ou a permanência do paciente.
icon: door-open
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

# Finalizar a internação

A saída do paciente é registrada pelo médico, na aba **Evolução médica**, no cartão **Finalizar internação / encaminhamento**. O mesmo cartão registra a **permanência**, quando o paciente continua internado por algum motivo.

{% stepper %}
{% step %}
### Abra o cartão

Abra **Finalizar internação / encaminhamento**, no fim da aba Evolução médica.

<div data-with-frame="true"><figure><img src="../imagens/saida-campos.png" alt="Campos da saída" width="560"><figcaption><p>Campos da saída</p></figcaption></figure></div>

1. **Médico responsável.**
2. **CID-10 principal.**
3. **Procedimento SUS realizado:** libera depois do CID.
4. **Motivo** da saída ou da permanência.
{% endstep %}

{% step %}
### Escolha o CID

Digite o código ou parte da descrição (1), por exemplo "J18.9" ou "pneumonia", e escolha na lista (2).

<div data-with-frame="true"><figure><img src="../imagens/saida-cid.png" alt="Busca do CID" width="560"><figcaption><p>Busca do CID</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Escolha o procedimento

Com o CID escolhido (1), digite o código ou a descrição do procedimento (2). A lista mostra só os procedimentos **compatíveis** com o CID, o sexo e a idade do paciente (3).

<div data-with-frame="true"><figure><img src="../imagens/saida-procedimento.png" alt="Procedimentos compatíveis com o CID" width="560"><figcaption><p>Procedimentos compatíveis com o CID</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Escolha o motivo e registre

Confira o procedimento (1), escolha o **motivo** (2) e clique em **Registrar** (3).

<div data-with-frame="true"><figure><img src="../imagens/saida-pronta.png" alt="Saída pronta para registrar" width="560"><figcaption><p>Saída pronta para registrar</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

## Motivos (tabela do SIH)

| Grupo | Exemplos | O que acontece |
| --- | --- | --- |
| Alta | 11 Curado, 12 Melhorado, 14 A pedido, 16 Por evasão | Encerra a internação |
| Transferência | 10 Transferência | Encerra a internação |
| Óbito | 41, 42, 43 (conforme a declaração) | Encerra a internação |
| Encerramento | 51 Encerramento administrativo | Encerra a internação |
| Obstétricos | 61 a 67 (mãe e recém-nascido) | Encerra a internação |
| Permanência | 21 a 28 | O paciente **continua internado** |

{% hint style="success" %}
Ao encerrar, o **leito é liberado** e o atendimento vai para [Finalizados › Enfermaria](../finalizados/enfermaria.md). Para encerrar, o **CID** e o **procedimento SUS** são obrigatórios.
{% endhint %}

{% hint style="warning" %}
Se aparecer "Nenhum procedimento da tabela é compatível", o CID escolhido não combina com o sexo ou a idade do paciente. Escolha outro CID ou consulte as combinações em [Tabelas SUS](../cadastros/tabelas-sus.md).
{% endhint %}

{% hint style="info" %}
O CID e o procedimento da saída vão para o laudo de AIH, a AIH e a exportação da produção. Registros de permanência aparecem no histórico de acompanhamentos.
{% endhint %}
