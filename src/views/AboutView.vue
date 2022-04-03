<template>
  <Header/>
  <Table/>
  <Footer/>
</template>

<script>
import Table from '@/components/Table.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/footer.vue'
export default {
  components: { 
    Table,
    Header,
    Footer, 
    },
  
}
</script>
