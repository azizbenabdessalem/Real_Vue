<!DOCTYPE html>
<html>
<head>
  <title>Vue Events Example</title>
  <script src="https://unpkg.com/vue@3"></script>
</head>
<body>

<div id="app">

  <!-- Le parent affiche le message -->
  <h2>{{ message }}</h2>

  <!-- Le parent écoute l'événement updateMessage -->
  <my-component @updateMessage="updateMessage"></my-component>

</div>

<script>

// 🎯 Définition du composant enfant
const MyComponent = {
  template: `
    <div>
      <button @click="changeMessage">Change Message</button>
    </div>
  `,
  methods: {
    changeMessage() {
      const newMessage = "Hello from the child component!";
      
      // L'enfant envoie un événement au parent
      this.$emit('updateMessage', newMessage);
    }
  }
};

// 🎯 Création de l'application (parent)
Vue.createApp({

  data() {
    return {
      message: "Initial message from parent component."
    }
  },

  methods: {
    // Méthode exécutée quand l'événement est reçu
    updateMessage(newMessage) {
      this.message = newMessage;
    }
  }

})
.component('my-component', MyComponent)
.mount('#app');

</script>

</body>
</html>
