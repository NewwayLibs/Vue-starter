<template>
    <ul>
      <li><router-link :to="{ name: 'home'}">Home</router-link></li>
      <li><router-link :to="{ name: 'contacts'}">Contacts</router-link></li>
      <li><router-link :to="{ name: 'pages', params: { page: 'about' }}">Pages - about</router-link></li>
    </ul>
</template>

<script>
export default {
  name: 'Links'
}
</script>
