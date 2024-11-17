<template>
<ion-page>
<ion-header>
<ion-toolbar>
<ion-title>Act-1</ion-title>
</ion-toolbar>
</ion-header>
<ion-content class="ion-padding">
<ion-card>
    <ion-card-header>
      <ion-card-title>Fitness</ion-card-title>
      <ion-card-subtitle>Body Workout</ion-card-subtitle>
    </ion-card-header>
   <ion-card-content>
    "Consistency in your workout routine builds strength, improves endurance, and boosts overall well-being."
    </ion-card-content>
  </ion-card>
  <ion-card>
   <img src="https://media.self.com/photos/57dc36e30d97fce032117bde/4:3/w_2560%2Cc_limit/GettyImages-660493375.jpg" />
    <ion-card-content>
      "Every rep, every set, brings you one step closer to your fitness goals."
    </ion-card-content>
  </ion-card>
</ion-content>
</ion-page>
</template>
<script lang="ts">

import { defineComponent } from 'vue';
import { IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle, IonTitle, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter } from '@ionic/vue';

export default defineComponent({
    name: "IndexScreen",
    components: { IonTitle, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter }
    });

    </script>
