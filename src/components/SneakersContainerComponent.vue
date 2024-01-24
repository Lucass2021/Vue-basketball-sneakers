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
                    <SneakerComponent/>
                    <SneakerComponent/>
                    <SneakerComponent/>
                    <SneakerComponent/>
                </div>
            </q-tab-panel>
  
            <q-tab-panel name="lebron">
              <div class="text-h6">Alarms</div>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
            </q-tab-panel>
  
            <q-tab-panel name="kobe">
              <div class="text-h6">Movies</div>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
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

.card-container .cards{
    display: flex;
}

</style>
  