<template>
<ion-page>
<ion-header>
<ion-toolbar>
<ion-title>Authentication</ion-title>
</ion-toolbar>
</ion-header>
<ion-content class="ion-padding">
<div>
  <div class="form-group pb-3">
    <label for="exampleInputEmail1">Email address</label>
    <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
  </div>
  <div class="form-group pb-3">
    <label for="exampleInputPassword1">Password</label>
    <input type="password" class="form-control" id="exampleInputPassword1" placeholder="Password">
  </div>
</div>
</ion-content>
<ion-footer>
<ion-toolbar>
<ion-button slot="end" class="w-50" @click="()=>{ $router.push('/Act-1')}">Sign In</ion-button>
</ion-toolbar>
</ion-footer>
</ion-page>
</template>
<script lang="ts">

import { defineComponent } from 'vue';
import { IonTitle, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter } from '@ionic/vue';

export default defineComponent({
    name: "IndexScreen",
    components: { IonTitle, IonButton, IonToolbar, IonHeader, IonPage, IonContent, IonFooter }
    });

    </script>
