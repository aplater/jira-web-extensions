<template>
  <div>
    <img alt="Vue logo" src="../assets/logo.png">
    <Dashboard msg="Welcome to Your TEAM DASHBOARD"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Dashboard from '@/components/Dashboard.vue'

export default {
  name: 'teamDashboard',
  components: {
    Dashboard
  }
}
</script>
