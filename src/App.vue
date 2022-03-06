<template>
  <Header />
  <div class="w-full flex">
    <!-- <DcHeros /> -->
    <Calendar />
  </div>
</template>

<script>
import Header from './components/AppHeader';
// import DcHeros from './components/DcHeros';
import Calendar from './components/Calendar';
export default {
  name: 'App',
  components: { Header, Calendar },
};
</script>
