<template lang="html">
  <div id="favourite_countries">
    <h2>Favourite Countries</h2>
    <ul>
      <li v-for="country in favouriteCountry">
        <p>Country: {{country.name}}</p>
        <p>Population: {{country.population}}</p>
      </li>
    </ul>

  </div>
</template>

<script>
export default {
  name: 'favourite-countries',
  props: ['favouriteCountry']
}
</script>

<style lang="css" scoped>
</style>
