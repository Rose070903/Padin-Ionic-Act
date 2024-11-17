<template>
<ion-page>
<ion-header>
<ion-toolbar>
<ion-title>Act-3</ion-title>
</ion-toolbar>
</ion-header>
<ion-content class="ion-padding">
<ion-button @click="()=>{ open = true; }" expand="block">Open</ion-button>
<ion-modal :is-open="open" ref="modal" trigger="open-modal">
      <ion-header>
        <ion-toolbar>
          <ion-buttons slot="start">
            <ion-button @click="()=>{ open = false; }">Cancel</ion-button>
          </ion-buttons>
          <ion-title>Welcome</ion-title>
          <ion-buttons slot="end">
            <ion-button :strong="true">Confirm</ion-button>
          </ion-buttons>
        </ion-toolbar>
      </ion-header>
      <ion-content class="ion-padding">
        <ion-item>
          <ion-input
            label="Enter your name"
            label-placement="stacked"
            ref="input"
            type="text"
            placeholder="Your name"
          ></ion-input>
        </ion-item>
      </ion-content>
    </ion-modal>
</ion-content>
</ion-page>
</template>
<script lang="ts">

import { defineComponent } from 'vue';
import { IonButtons, IonModal, IonTitle, IonItem, IonInput, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter } from '@ionic/vue';

export default defineComponent({
    name: "IndexScreen",
    components: { IonButtons, IonModal, IonTitle, IonItem, IonInput, IonTitle, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter },
    data() {
        return {
            open: false
        }
    }
    });

    </script>
