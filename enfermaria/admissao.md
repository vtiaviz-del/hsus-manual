---
description: Admissão de enfermagem - leito, acompanhante, anamnese, exame físico e plano.
icon: clipboard-check
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

# Admissão

A admissão coloca o paciente no leito e registra a avaliação inicial de enfermagem. Ela é o primeiro passo da internação: as evoluções só liberam depois que a admissão for salva.

{% stepper %}
{% step %}
### Escolha o leito

Selecione o paciente **Aguardando admissão** na lista e abra a aba **Admissão**.

<div data-with-frame="true"><figure><img src="../imagens/adm-leito.png" alt="Leito e internação" width="560"><figcaption><p>Leito e internação</p></figcaption></figure></div>

1. Confira a **data e a hora da admissão**. As duas são obrigatórias.
2. Escolha a **ala**. O sistema mostra só as alas compatíveis com o sexo e a idade do paciente (por exemplo, a pediátrica para menores de 12 anos).
3. Clique em um **leito livre**. Os ocupados aparecem em vermelho, com o nome de quem está nele.
4. Escolha o **caráter da internação**: eletiva, urgência, acidente no local de trabalho, acidente no trajeto, outros acidentes de trânsito ou outras lesões.
{% endstep %}

{% step %}
### Confira o leito escolhido

O leito fica destacado (1) e a mensagem abaixo confirma a ala e o número (2).

<div data-with-frame="true"><figure><img src="../imagens/adm-leito-escolhido.png" alt="Leito selecionado" width="560"><figcaption><p>Leito selecionado</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Registre o acompanhante e os check-ins da consulta

Clique no título de cada seção para abri-la.

<div data-with-frame="true"><figure><img src="../imagens/adm-secoes.png" alt="Acompanhante e medicamentos da consulta" width="560"><figcaption><p>Acompanhante e medicamentos da consulta</p></figcaption></figure></div>

1. **Acompanhante:** nome, telefone, parentesco e documento.
2. **Medicamentos e exames da consulta:** check-in da administração e da coleta. Como no ambulatório, a marcação é gravada na hora.
{% endstep %}

{% step %}
### Preencha a anamnese e os sinais vitais

Os cartões (1) abrem formulários próprios. Clique em **Concluir** para voltar; o cartão passa a mostrar quantos itens foram informados.

<div data-with-frame="true"><figure><img src="../imagens/adm-cartoes.png" alt="Cartões da admissão" width="560"><figcaption><p>Cartões da admissão</p></figcaption></figure></div>

* **Anamnese — Hábitos:** religião, tabagismo, drogas, etilismo, alimentação, ingestão hídrica, atividade física e sono.
* **Anamnese — Históricos:** doenças, internações, cirurgias e medicamentos de uso contínuo do paciente e da família.
* **Estado de entrada:** modo de entrada, consciência, pupilas, autocuidado e higiene.
* **Sinais vitais:** PA, temperatura, FC, SpO₂, FR, glicemia, peso e altura. O IMC é calculado sozinho.

<div data-with-frame="true"><figure><img src="../imagens/adm-habitos.png" alt="Cartão Anamnese — Hábitos aberto"><figcaption><p>Cartão Anamnese — Hábitos aberto</p></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../imagens/adm-sinais.png" alt="Cartão Sinais vitais aberto"><figcaption><p>Cartão Sinais vitais aberto</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Faça o exame físico

Abra **Exame físico** e clique na região do corpo (1): cabeça, tórax e sistemas, membros superiores ou inferiores. Marque as alterações encontradas. A legenda (2) mostra as regiões já avaliadas.

<div data-with-frame="true"><figure><img src="../imagens/adm-exame-fisico.png" alt="Mapa do corpo para o exame físico" width="560"><figcaption><p>Mapa do corpo para o exame físico</p></figcaption></figure></div>

<div data-with-frame="true"><figure><img src="../imagens/adm-exame-regiao.png" alt="Exame físico da região da cabeça"><figcaption><p>Exame físico da região da cabeça</p></figcaption></figure></div>
{% endstep %}

{% step %}
### Registre o plano e salve

<div data-with-frame="true"><figure><img src="../imagens/adm-diagnosticos.png" alt="Diagnósticos, plano e anotação" width="560"><figcaption><p>Diagnósticos, plano e anotação</p></figcaption></figure></div>

1. **Diagnósticos e plano de enfermagem:** o diagnóstico principal vem da consulta. Registre outro diagnóstico, se houver, o plano e a implementação.
2. **Anotação de enfermagem:** o registro da admissão.
3. Clique em **Salvar admissão**. O leito fica ocupado e as abas de evolução são liberadas.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
Os dados dos cartões só são gravados ao clicar em **Salvar admissão**. **Concluir**, dentro do cartão, apenas fecha o formulário.
{% endhint %}

{% hint style="info" %}
Para corrigir a admissão, altere os campos e salve de novo. Cada alteração fica registrada com seu nome e o horário.
{% endhint %}
