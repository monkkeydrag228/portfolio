<template>
  <div>
    <header>
      <ul>
        <li><a @click="scrollToSection('about')">About me</a></li>
        <li><a @click="scrollToSection('projects')">My projects</a></li>
        <li><a @click="scrollToSection('contacts')">Contact</a></li>
      </ul>
    </header>
    
  </div>
</template>

<script>
export default {
  methods: {
  scrollToSection(sectionId) {
    const sectionElement = this.$refs[sectionId];
    if (sectionElement && sectionElement.$el) {
      sectionElement.$el.scrollIntoView({ behavior: 'smooth', block: 'start' });
    }
  }
}
}
</script>

<style scoped>
ul {
  background: transparent;
  list-style: none;
  display: flex;
  padding-top: 30px;  
}

ul li a {
  font-family: "Roboto Condensed", sans-serif;
  font-weight: 400;
  font-style: normal;
  font-size: 22px;
  text-decoration: none;
  color: inherit;
  padding: 10px 20px;
  border-radius: 5px;
  background-color: #007bff;
  color: #ffffff;
  box-shadow: 0px 3px 5px rgba(0, 0, 0, 0.2);
  transition: box-shadow 0.3s ease, transform 0.3s ease;
}

ul li a:hover {
  box-shadow: 0px 5px 10px rgba(0, 0, 0, 0.3);
  text-indent: 10px;
}

ul li a:focus {
  box-shadow: 1px 10px 20px rgba(0, 0, 0, 0.3);
  transform: translateY(2px);
}

ul li a:active {
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.4);
  transform: translateY(1px);
}
</style>
