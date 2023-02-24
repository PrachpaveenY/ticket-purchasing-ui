<template>
  <div class="">
      <TheHeader :title="title"/>
      <div class="container">
       <page-card>
         <page-button @click="switchTab('TicketPurchasingFull')" :mode="setLoginActiveTab">Ticket Purchasing Full</page-button>
         <page-button @click="switchTab('TicketListDelivery')" :mode="setRegisterActiveTab">TicketList Delivery</page-button>
         <page-button @click="switchTab('Payment')" :mode="setRegisterActiveTab">Payment</page-button>
         <page-button @click="switchTab('SummaryTotal')" :mode="setRegisterActiveTab">Summary Total</page-button>
       </page-card>
       <keep-alive>
          <component :is="selectedTab"></component>
       </keep-alive>
      </div>
  </div>
  
  
</template>

<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TicketPurchasingFull from './components/Auth/TicketPurchasingFull.vue';
import TicketListDelivery from './components/Auth/TicketList-Delivery.vue';
import Payment from './components/Auth/Payment.vue';
import SummaryTotal from './components/Auth/SummaryTotal.vue';

export default {
  name : 'App',
  components:{
      TheHeader,
      TicketPurchasingFull,
      TicketListDelivery,
      Payment,
      SummaryTotal,
  },
  data() {
      return {
          title: 'Ticket Purchasing UI',
          selectedTab : TicketPurchasingFull,
      }
  },
  methods:{
      switchTab(tab){
          this.selectedTab = tab;
      }
  },
  computed:{
      // เซ็ตเป็นค่าว่างเมื่อคลิก
      setLoginActiveTab(){
          return this.selectedTab !== 'TicketPurchasingFull' ? '' : 'default';
      },
      setRegisterActiveTab(){
          return this.selectedTab !== 'TicketListDelivery' ? '' : 'default';
      },
      setRegisterActiveTab(){
          return this.selectedTab !== 'Payment' ? '' : 'default';
      },
      setRegisterActiveTab(){
          return this.selectedTab !== 'SummaryTotal' ? '' : 'default';
      },
  }
}

</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:wght@200&display=swap');

* {
  margin: 0;
  box-sizing: border-box;
  font-family: 'Nunito Sans', sans-serif;
}

.container {
  width: 90%;
  margin: 0 auto;
}

/* body, html {} */
</style>
