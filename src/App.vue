<template>
  <div id="app">
    <Header />
  </div>
</template>

<script>
import Header from './components/Header'
export default {
  name: 'App',
  components: {
    Header
  },
  data() {
    return [
      {
        id: 1,
        name: 'Daniel Blitchman',
        email: 'daniel.blitchmat@gmail.com',
        role: ['Admin', 'User'],
        status: true 
      },
      {
        id: 2,
        name: 'Daniel Blitchman',
        email: 'daniel.blitchmat@gmail.com',
        role: 'Admin',
        status: false 
      },
      {
        id: 3,
        name: 'Daniel Blitchman',
        email: 'daniel.blitchmat@gmail.com',
        role:  'User',
        status: true 
      },
      {
        id: 4,
        name: 'Daniel Blitchman',
        email: 'daniel.blitchmat@gmail.com',
        role: 'Admin',
        status: true 
      },
      {
        id: 5,
        name: 'Daniel Blitchman',
        email: 'daniel.blitchmat@gmail.com',
        role:  'User',
        status: true 
      },
      {
        id: 6,
        name: 'Daniel Blitchman',
        email: 'daniel.blitchmat@gmail.com',
        role:  'User',
        status: true 
      }

    ]
  }

  }

</script>

<style>

</style>
