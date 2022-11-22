<template>
  <div class="q-mt-xl container">
    <fieldset class="row">
      <div class="col-xs-12 col-md-7 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Nome" />
      </div>
      <div class="col-xs-12 col-md-2 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Gênero" />
      </div>
      <div class="col-xs-12 col-md-3 q-mt-sm q-mb-sm">
        <q-input filled v-model="text" label="Nascimento: dd/mm/aaaa" />
      </div>
      <div class="col-xs-12 col-md-6 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="E-mail" />
      </div>
      <div class="col-xs-12 col-md-6 q-mt-sm q-mb-sm">
        <q-input filled v-model="text" label="Observação" />
      </div>
    </fieldset>

    <fieldset class="row">
      <legend class="text-h6 text-weight-bold">Endereço</legend>
      <div class="col-xs-12 col-md-2 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="CEP" />
      </div>
      <div class="col-xs-12 col-md-6 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Logradouro" />
      </div>
      <div class="col-xs-12 col-md-1 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Número" />
      </div>
      <div class="col-xs-12 col-md-3 q-mt-sm q-mb-sm">
        <q-input filled v-model="text" label="Complemento" />
      </div>
      <div class="col-xs-12 col-md-4 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Bairro" />
      </div>
      <div class="col-xs-12 col-md-4 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Cidade" />
      </div>
      <div class="col-xs-12 col-md-2 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Estado" />
      </div>
      <div class="col-xs-12 col-md-2 q-mt-sm q-mb-sm">
        <q-input filled v-model="text" label="País" />
      </div>
    </fieldset>

    <fieldset class="row">
      <legend class="text-h6 text-weight-bold">Telefones</legend>
      <div class="col-xs-12 col-md-3 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Residencial" />
      </div>
      <div class="col-xs-12 col-md-3 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Comercial" />
      </div>
      <div class="col-xs-12 col-md-3 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="Celular" />
      </div>
      <div class="col-xs-12 col-md-2 q-mt-sm q-mb-sm q-pr-md">
        <q-input filled v-model="text" label="CPF" />
      </div>
      <div class="col-xs-12 col-md-1 q-mt-sm q-mb-sm">
        <q-input filled v-model="text" label="RG" />
      </div>
    </fieldset>

    <div class="row">
      <q-btn color="primary" label="NOVO CADASTRO" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Recepcao",
  setup() {},
};
</script>
<style scoped>
fieldset {
  border: none;
}

.container {
  margin-right: 6%;
  margin-left: 6%;
}
</style>
