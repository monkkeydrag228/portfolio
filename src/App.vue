<template>
  <div>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">

    <!-- Навигационная панель -->
    <navbar-view />

    <!-- Основное содержимое страницы, включая маршрутизатор и секции -->
    <router-view />

    <!-- Секция "About Me" -->
    <about-me-vue ref="aboutMeSection" />

    <!-- Секция "My Projects" -->
    <my-projects ref="projectsSection" />

    <!-- Секция "Contacts" -->
    <contacts-view ref="contactsSection" />
  </div>
</template>

<script>
import NavbarView from '@/view/NavbarView.vue';
import AboutMeVue from './view/AboutMe.vue';
import MyProjects from './view/MyProjects.vue';
import ContactsView from './view/ContactsView.vue';

export default {
  methods: {
    scrollToSection(sectionId) {
      const sectionElement = this.$refs[sectionId];
      if (sectionElement && sectionElement.$el) {
        sectionElement.$el.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    }
  },
  components: {
    NavbarView,
    AboutMeVue,
    MyProjects,
    ContactsView
  }
};
</script>

<style>
body {
  background: no-repeat linear-gradient(135deg, rgba(19, 12, 134, 1) 0%, rgba(92, 92, 255, 1) 50%, rgba(0, 212, 255, 1) 100%);
  padding: 0 !important;
  height: 100%;
  overflow-x: hidden;
}

* {
  margin: 0 auto;
}
</style>
  d