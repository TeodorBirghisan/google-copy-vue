<template>
    <div class="container">
      <Header />
      <Search />
      <Footer />
    </div>
</template>

<script>
import Header from '../src/components/Header';
import Search from '../src/components/Search';
import Footer from '../src/components/Footer';

export default {
  name: 'App',
  components: {
    Header,
    Search,
    Footer,
  }
}
</script>

<style>
.container {
  background-color: #eeeeee;
  display: inline;
  width: 100%;
}
</style>
