<template>
    <div class="index-page">
      <div class="banner">
        <h1 class="fade-in">Bienvenue chez Pulsar Agency</h1>
        <p class="fade-in">Nous sommes une agence spécialisée dans le marketing digital.</p>
        <p class="fade-in">Contactez-nous dès maintenant pour booster votre présence en ligne !</p>
      </div>
    </div>
  </template>
  
  <style scoped>
  .fade-in {
    animation: fadeIn 1s ease-out;
    opacity: 0;
  }
  
  @keyframes fadeIn {
    from {
      opacity: 0;
      transform: translateY(-20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  </style>