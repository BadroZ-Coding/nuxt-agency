<template>
  <div class="services-page">
    <h1>Nos Services</h1>
    <div class="service" v-for="service in services" :key="service.title">
      <i :class="service.icon"></i>
      <h2>{{ service.title }}</h2>
      <p>{{ service.description }}</p>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      services: [
        {
          title: "Vente de Site Web",
          description: "Nous concevons des sites web professionnels et attrayants pour votre entreprise.",
          icon: "fas fa-desktop"
        },
        {
          title: "SEO",
          description: "Optimisez votre site web pour les moteurs de recherche afin d'attirer plus de trafic organique.",
          icon: "fas fa-search"
        },
        {
          title: "Ads",
          description: "Créez des campagnes publicitaires efficaces pour atteindre votre public cible.",
          icon: "fas fa-bullhorn"
        }
      ]
    };
  }
};
</script>

<style scoped>
.service {
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 5px;
  margin-bottom: 20px;
  transition: transform 0.3s ease;
}

.service:hover {
  transform: scale(1.05);
}

.service i {
  font-size: 24px;
  margin-bottom: 10px;
  display: block;
}
</style>