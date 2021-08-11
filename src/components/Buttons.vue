<template>
  <div>
    <b-dropdown no-caret> <!-- no-caret for not showing the dropdown sign-->
      <template #button-content>
        <b-icon icon="list"></b-icon> Menu
      </template>
      <!-- für den Abstand zwischen den Varianten
      <b-dropdown-divider></b-dropdown-divider>
      -->
      <b-dropdown-item-button>
        <b-icon icon="person-fill"></b-icon>
        AboutMe</b-dropdown-item-button>
      <b-dropdown-item-button>
        <b-icon icon="file-earmark"></b-icon>
        Projects</b-dropdown-item-button>
      <b-dropdown-item-button>
        <b-icon icon="envelope"></b-icon>
        Contact</b-dropdown-item-button>
    </b-dropdown>
  </div>
</template>

<script>
export default {
}
</script>



<style scoped>

</style>