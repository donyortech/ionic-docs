```html
<template>
  <ion-header>
    <ion-toolbar>
      <ion-title>Inline Toast</ion-title>
    </ion-toolbar>
  </ion-header>
  <ion-content class="ion-padding">
    <ion-button id="open-toast" expand="block">Open</ion-button>
    <p>This toast example uses triggers to automatically open a toast when the button is clicked.</p>
    <ion-toast trigger="open-toast" message="This toast will disappear after 5 seconds" :duration="5000"></ion-toast>
  </ion-content>
</template>

<script lang="ts">
  import {
    IonButton,
    IonHeader,
    IonContent,
    IonToolbar,
    IonTitle,
    IonToast,
  } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: {
      IonButton,
      IonHeader,
      IonContent,
      IonToolbar,
      IonTitle,
      IonToast,
    },
  });
</script>
```
