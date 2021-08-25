<template>
  <div>
    <b-form-group label-cols="4" label-cols-lg="2" label-size="lg" label-for="input-default">
      <b-form-input v-model="text" placeholder="Vorname"></b-form-input>
    </b-form-group>

    <b-form-group label-cols="4" label-cols-lg="2" label-size="lg" label-for="input-default">
      <b-form-input v-model="text" placeholder="Nachname"></b-form-input>
    </b-form-group>

    <b-form-group label-cols="4" label-cols-lg="2" label-size="lg" label-for="input-default">
    <b-form-input v-model="text" placeholder="EMail"></b-form-input>
    </b-form-group>

    <b-form-group label-cols="4" label-cols-lg="2" label-size="lg" label-for="input-default">
      <b-form-input v-model="text" placeholder="Text"></b-form-input>
    </b-form-group>


    <div class="button">
      <b-button variant="secondary">
        Senden
      </b-button>
    </div>

  </div>
</template>



<script>
export default {
  name: 'Contact'
}
</script>