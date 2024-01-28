<template>
    <div class="container">
        <div class="about-section">
            <h2>Lacing up into greatness</h2>
            <p>Beyond the court, it's more than a label – it's the language of basketball excellence.</p>
        </div>

      <div class="q-gutter-y-md">
        <q-card>
          <q-tabs
            v-model="tab"
            class="text-dark"
            align="justify"
            narrow-indicator
          >
            <q-tab name="jordan" label="Jordan's" />
            <q-tab name="lebron" label="LeBron's" />
            <q-tab name="kobe" label="Kobe's" />
          </q-tabs>
  
          <q-separator />
  
          <q-tab-panels v-model="tab" animated class="card-container">
            <q-tab-panel name="jordan">
              <div class="cards">
                <div class="row">
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Jordan 1 Mid Dutch Green" 
                      brand="Air Jordan Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Jordan 1 Mid Dutch Green" 
                      brand="Air Jordan Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Jordan 1 Mid Dutch Green" 
                      brand="Air Jordan Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                </div>
                <div class="row">
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Jordan 1 Mid Dutch Green" 
                      brand="Air Jordan Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Jordan 1 Mid Dutch Green" 
                      brand="Air Jordan Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Jordan 1 Mid Dutch Green" 
                      brand="Air Jordan Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                </div>
              </div>
            </q-tab-panel>

  
            <q-tab-panel name="lebron">
              <div class="cards">
                <div class="row">
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Lebron 1 Mid Dutch Green" 
                      brand="Air Lebron Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Lebron 1 Mid Dutch Green" 
                      brand="Air Lebron Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Lebron 1 Mid Dutch Green" 
                      brand="Air Lebron Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                </div>
                <div class="row">
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Lebron 1 Mid Dutch Green" 
                      brand="Air Lebron Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Lebron 1 Mid Dutch Green" 
                      brand="Air Lebron Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Lebron 1 Mid Dutch Green" 
                      brand="Air Lebron Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                </div>
              </div>
            </q-tab-panel>
  
            <q-tab-panel name="kobe">
              <div class="cards">
                <div class="row">
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Mamba 1 Mid Dutch Green" 
                      brand="Air Mamba Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Mamba 1 Mid Dutch Green" 
                      brand="Air Mamba Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Mamba 1 Mid Dutch Green" 
                      brand="Air Mamba Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                </div>
                <div class="row">
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Mamba 1 Mid Dutch Green" 
                      brand="Air Mamba Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Mamba 1 Mid Dutch Green" 
                      brand="Air Mamba Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                  <div class="col-lg-4 col-md-4 col-sm-12">
                    <SneakerComponent 
                      :img="require('@/assets/sneakers/jordan/jordan-green.png')" 
                      name="Air Mamba 1 Mid Dutch Green" 
                      brand="Air Mamba Shoes" 
                      price="R$ 1199,99"
                    />
                  </div>
                </div>
              </div>
            </q-tab-panel>
          </q-tab-panels>
        </q-card>
      </div>
    </div>
  </template>
  
<script setup>
    import { ref } from 'vue'
    import SneakerComponent from './SneakerComponent.vue';

    const tab = ref('jordan')

</script>

<style>
.container{
    padding:50px;
}

.about-section{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 50px;
}

.about-section h2{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    font-size: 36px;
}

.about-section p{
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 18px;
}

.cards .row{
  margin: 100px 0px;
}

@media only screen and (max-width: 1000px) {
  .cards{
    overflow-x: hidden;
  }

  .cards .row{
    margin: 50px 0px;
  }

  .q-tab-panel{
    padding:0px !important;
  }
}

@media only screen and (max-width: 1000px) {
  .card-container .row .col-lg-4{
    width: 100%;
  }

  .q-tabs--horizontal .q-tabs__arrow--right{
    display: none !important;
  }
  .q-tabs--horizontal .q-tabs__arrow--left{
    display: none !important;
  }
}

@media only screen and (max-width: 568px) {
  .about-section h2{
    font-size: 26px;
  }

  .about-section p{
    font-size: 16px;
    text-align: center;
  }
}

</style>
  