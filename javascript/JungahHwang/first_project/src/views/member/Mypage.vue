<template>
  <v-card class="primary mt-8 mb-10">
   
    <v-row>
      <v-col cols="12" md="6">
        <read-info></read-info>
      </v-col>
      <v-col cols="12" md="6">
        <recent-board></recent-board>

      </v-col>
    </v-row>
      
    
  </v-card>

</template>


<script>
import ReadInfo from '@/components/member/ReadInfo'
import RecentBoard from '@/components/member/RecentBoard'


export default {
  components: {
    ReadInfo,
    RecentBoard
  }
}
</script>