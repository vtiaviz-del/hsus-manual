---
description: >-
  Gerar a numeração das AIHs, emitir as AIHs do mês, cancelar AIH e exportar a
  produção.
icon: file-invoice
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

# AIH e produção do mês

No fim do mês, as internações encerradas recebem o número de AIH, a partir das [Faixas de AIH](../cadastros/faixas-de-aih.md) cadastradas. Com todas numeradas, você emite as AIHs e exporta o arquivo de produção.

<figure><img src="../.gitbook/assets/fluxo-aih.svg" alt="Ciclo da AIH no H-SUS"><figcaption><p>Ciclo da AIH no H-SUS</p></figcaption></figure>

## Documentos do mês

<div data-with-frame="true"><figure><img src="../.gitbook/assets/fin-docs-mes.png" alt="Botões de Documentos do mês"><figcaption><p>Botões de Documentos do mês</p></figcaption></figure></div>

1. **Gerar AIHs:** numera as saídas do mês que ainda não têm AIH. O número no botão é a quantidade de saídas sem número.
2. **Exportar Produção:** baixa o arquivo CSV com a produção do mês.
3. **Prontuários:** todos os prontuários do mês num só documento.
4. **Laudos de AIH:** todos os laudos do mês.
5. **AIHs:** todas as AIHs do mês.

{% hint style="warning" %}
**AIHs** e **Exportar Produção** só ficam disponíveis quando **todas** as saídas do mês têm número de AIH.
{% endhint %}

## Gerar a numeração

{% stepper %}
{% step %}
### Clique em Gerar AIHs

Escolha o mês e clique em **Gerar AIHs**. Confira a lista de pacientes sem número e a quantidade de números disponíveis na faixa (1). Clique em **Gerar** (2).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/fin-gerar-aihs.png" alt="Confirmação antes de gerar"><figcaption><p>Confirmação antes de gerar</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Confira o resultado

Um aviso confirma quantos números foram gerados (4). **Gerar AIHs** fica desabilitado (1), e **Exportar Produção** (2) e **AIHs** (3) ficam disponíveis.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/fin-aihs-geradas.png" alt="Numeração gerada"><figcaption><p>Numeração gerada</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

Cada saída recebe um número de 13 dígitos (12 da faixa mais o dígito verificador), na ordem das saídas. Números cancelados são reaproveitados primeiro. Se a faixa acabar no meio, o sistema avisa quantos foram gerados: cadastre uma faixa nova e gere de novo.

## Cancelar uma AIH

Use quando a AIH foi emitida com erro.

{% stepper %}
{% step %}
### Clique em Cancelar AIH

Clique no atendimento. Na linha do tempo, ao lado do número da AIH (1), clique em **Cancelar AIH** (2).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/fin-aih-numero.png" alt="Número da AIH e o botão Cancelar AIH"><figcaption><p>Número da AIH e o botão Cancelar AIH</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Informe o motivo e confirme

Escreva o **motivo** (1) e clique em **Cancelar AIH** (2).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/fin-cancelar-aih.png" alt="Cancelamento com motivo"><figcaption><p>Cancelamento com motivo</p></figcaption></figure></div>
{% endstep %}
{% endstepper %}

O número volta para ser o primeiro reaproveitado, e o cancelamento fica registrado no atendimento. Para dar um número novo ao paciente, clique de novo em **Gerar AIHs**.

## Exportar a produção

Clique em **Exportar Produção** (1) para baixar o arquivo `producao-aih-ANO-MES.csv`. Um aviso confirma a exportação (2).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/fin-exportar.png" alt="Produção exportada"><figcaption><p>Produção exportada</p></figcaption></figure></div>

O arquivo traz uma linha por AIH, em ordem de número, com os dados usados no faturamento:

* **Paciente:** CNS, nome, prontuário, nascimento, sexo, raça, mãe, responsável, endereço, CEP e código IBGE.
* **Internação:** entrada, saída, CID, procedimento, clínica, caráter e motivo da alta.
* **Médico solicitante:** CPF, CNS e CBO.
* **Número da AIH.**

{% hint style="info" %}
Se algum campo obrigatório estiver em branco (CNS, nascimento, sexo, IBGE, CID, procedimento…), o arquivo é gerado mesmo assim e o aviso mostra quem está incompleto e o que falta. Corrija no atendimento ou no cadastro e exporte de novo.
{% endhint %}
