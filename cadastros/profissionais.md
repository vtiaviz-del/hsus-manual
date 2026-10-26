---
description: Cadastro dos profissionais e dos acessos ao sistema.
icon: users
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

# Profissionais

Em **Cadastros › Profissionais** o administrador cadastra quem usa o sistema: os dados de cada profissional, a função, o registro no conselho e o acesso (login, senha e nível).

<div data-with-frame="true"><figure><img src="../.gitbook/assets/profissionais-lista.png" alt="Cadastros › Profissionais"><figcaption><p>Cadastros › Profissionais</p></figcaption></figure></div>

1. **Indicadores:** total, ativos, médicos ativos e inativos.
2. **Busca:** por nome, login, CPF, CNS ou CBO.
3. **Filtros:** **Todos**, **Ativos** e **Inativos**.
4. **Lista:** cada profissional com o cargo, o CBO ou o conselho, o login, o nível de acesso e a situação.
5. **Novo:** abre o formulário para um profissional novo.

## Cadastrar um profissional

{% stepper %}
{% step %}
### Preencha os dados pessoais e a função

Clique em **Novo**.

<div data-with-frame="true"><figure><img src="../.gitbook/assets/profissionais-novo.png" alt="Dados pessoais e função"><figcaption><p>Dados pessoais e função</p></figcaption></figure></div>

1. **Dados pessoais:** nome completo e, se tiver, CNS e CPF. O CNS e o CBO do médico saem no laudo de AIH e na produção.
2. **Função:** escolha o **cargo** (para os mais comuns, o **CBO** é preenchido sozinho). Para médicos e enfermagem, preencha o **conselho** (CRM, COREN…), o **número de registro** e a **UF**: são obrigatórios porque saem ao lado do nome em cada registro do prontuário.
{% endstep %}

{% step %}
### Defina o acesso

<div data-with-frame="true"><figure><img src="../.gitbook/assets/profissionais-acesso.png" alt="Acesso ao sistema"><figcaption><p>Acesso ao sistema</p></figcaption></figure></div>

1. **Login:** o nome de usuário para entrar.
2. **Nível de acesso:** Administrador, Médico, Enfermagem ou Recepção. Veja o que cada um acessa em [Perfis de acesso](../primeiros-passos/perfis-de-acesso.md).
3. **Senha** (mínimo de 6 caracteres), repetida em **Confirmar senha**.
4. **Status:** **Ativo** para liberar o acesso.
{% endstep %}

{% step %}
### Salve

Clique em **Salvar**. O profissional já pode entrar no sistema.
{% endstep %}
{% endstepper %}

## Trocar a senha ou desativar

* Para definir uma senha nova, abra o profissional, digite a nova senha nos dois campos e salve. Com os campos de senha em branco, a senha atual é mantida.
* A senha é guardada de forma criptografada: nem o administrador consegue vê-la.
* Quem deixa o hospital deve ser marcado como **Inativo**. Inativos não conseguem entrar no sistema, mas os registros feitos por eles continuam no prontuário com o nome deles.

{% hint style="warning" %}
O sistema sempre exige **pelo menos um administrador ativo**. Não é possível desativar ou rebaixar o último.
{% endhint %}
