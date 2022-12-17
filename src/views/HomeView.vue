<template>
  <div class="home container">
    <div class="row">
      <div class="col-sm-12 col-md-6">
        <loginView />
      </div>

      <div class="col-sm-12 col-md-6">
        <screenView />
      </div>
    </div>
  </div>
</template>

<script>
  import loginView from '@/components/login.vue';
  import screenView from '@/components/screen.vue';

  export default{
    name: 'HomeView',
    components: {
      loginView,
      screenView
    }
  }
</script>
