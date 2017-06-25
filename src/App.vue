<template>
  <v-app>
    <v-navigation-drawer></v-navigation-drawer>

    <!--navBar !-->

     <v-toolbar style="background-color: #FFFFFF">
      <v-toolbar-side-icon dark></v-toolbar-side-icon>
      <v-toolbar-title class="hidden-sm-and-down">Barrel On</v-toolbar-title>
      <v-text-field prepend-icon="search" label="Search..." hide-details single-line dark></v-text-field>
    </v-toolbar>

    <!--navBar !-->

  <main>

    <div id="example-5" style= "margin-top:5%">

    <v-layout row-sm column child-flex-sm>

       <!--sideBar !-->

        <v-card flat>
        
         </v-card>

        <!--sideBar !--> 

      <v-card style="margin-bottom:20%">
          <v-card-row img="/public/engaged.jpg" height="300px"></v-card-row>
            <v-card-text class="black--text" style="background-color:#FFFFFF; padding-bottom:0px">
              <a> Organic Coffee </a>
              <v-spacer></v-spacer>
              <p style="margin-bottom: 0px"> $3.00 </p>
              
            </v-card-text>
            
          <v-card-row actions style="background-color:#FFFFFF">
            
            <v-btn flat class="black--text">Buy on Amazon</v-btn>
              <v-spacer></v-spacer>
            <v-btn icon>
              <v-icon class="black--text">add_circle</v-icon>
            </v-btn>
          </v-card-row>
      </v-card>

      <v-card flat>
        
      </v-card>

    </v-layout>
  </div>
    </main>
  <v-footer></v-footer>
</v-app>
 </template> 



<script>
  export default {
    data () {
      return {
        clipped: false,
        drawer: true,
        fixed: false,
        items: [
          { icon: 'bubble_chart', title: 'Inspire' }
        ],
        miniVariant: false,
        right: true,
        rightDrawer: false,
        title: 'Vuetify.js'
      }
    }
  }
</script>

<style lang="stylus">
  @import './stylus/main'
</style>
