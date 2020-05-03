<template>
  <q-page class="flex flex-center">
    <div class="profile-background col-lg-4">
        <img src="~assets/me.jpg" alt="Alex" class="profile-image">
    </div>
  </q-page>
</template>

<style scoped>
.profile-image {
  width: 10rem;
  border-radius:50%;
  margin:2.5rem auto;
  box-shadow:1px 1px 0.7rem rgba(0,0,0,0.2)
}
</style>

<script>
export default {
  name: 'PageIndex'
}
</script>
