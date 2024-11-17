<template>
<ion-page>
<ion-header>
<ion-toolbar>
<ion-title>Act-2</ion-title>
</ion-toolbar>
</ion-header>
<ion-content class="ion-no-padding">
<ion-list>
<ion-item lines="full">
<ion-icon slot="start" :icon="logoIonic"></ion-icon>
<ion-label>
<h3><strong>Act-1: IonList, IonItem, IonIcon, IonLabel</strong></h3>
<p><small>Learn to use IonList, IonItem, IonIcon, IonLabel componets</small></p>
</ion-label>
</ion-item>
<ion-item lines="full" @click="()=>{ $router.push('/Act-2') }" >
<ion-icon slot="start" :icon="logoIonic"></ion-icon>
<ion-label>
<h3><strong>Act-2: IonCard, IonCardContent</strong></h3>
<p><small>Learn to use IonCard, IonCardContent componets</small></p>
</ion-label>
</ion-item>
<ion-item lines="full" @click="()=>{ $router.push('/Act-3') }" >
<ion-icon slot="start" :icon="logoIonic"></ion-icon>
<ion-label>
<h3><strong>Act-3: Modal Implementation</strong></h3>
<p><small>Learn to use Modal componets</small></p>
</ion-label>
</ion-item>
</ion-list>
</ion-content>
</ion-page>
</template>
<script lang="ts">

import { defineComponent } from 'vue';
import { IonList, IonItem, IonIcon, IonLabel, IonTitle, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter } from '@ionic/vue';
import { logoIonic } from 'ionicons/icons';

export default defineComponent({
    name: "IndexScreen",
    components: { IonList, IonItem, IonIcon, IonLabel, IonTitle, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter },
    setup() {
    return {
     logoIonic
    }
    }

    });

    </script>
