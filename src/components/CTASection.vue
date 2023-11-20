<template>
    <div class="cta-section">
      <h2>Ready to Get Started?</h2>
      <p>Contact me for collaboration!</p>
      <button @click="showContactForm">Contact Now</button>
    </div>
  </template>
  
  <script>
  export default {
    name: "CTASection",
    methods: {
      showContactForm() {
        alert("Contact form will be displayed here.");
      },
    },
  };
  </script>
  
  <style scoped>
  .cta-section {
    text-align: center;
    padding: 50px;
    background-color: #f0f0f0;
  }
  </style>
  