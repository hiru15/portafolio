<template lang="pug">
div.container
  Navbar
  div.columns
    div.column.is-10.is-offset-1.contenedor
      div.columns
        div.column.is-3.is-offset-2.espacio-text
          h2.title Contacto
          p.text I'm a paragraph. Click here to add your own text and edit me. I’m a great place for you to tell a story and let your users know a little more about you.
        div.column.is-4.is-offset-1.espacio 
         div.columns
          div.column.is-6.field
            div.control
              input.input(placeholder="Nombre")
          div.column.is-6.field
            div.control
              input.input(placeholder="Email")
         div.columns
          div.column.is-12.field
            div.control
              input.input(placeholder="Asunto")
         div.columns
          div.column.is-12.field
            div.control
              textarea.textarea(placeholder="Mensaje")
         div.columns
          div.column.is-12.field
            div.control
              button.button.is-success.is-large Enviar
      div.columns
        div.column.is-5.is-offset-5
          a.fa.fa-facebook.icon.has-text-white(href="https://www.facebook.com/ehlpiphex")
          a.fa.fa-instagram.icon.has-text-white(href="https://www.facebook.com/ehlpiphex")
  nuxt
</template>

<script>
import Navbar from '~/components/Navbar.vue'
export default {
  components: {
    Navbar
  }
}
</script>

<style>
.is-large{
  width: 100%;
}
.contenedor{
  background: #201B3F;
  margin-top: 20px;
}
.espacio-text{
  margin-top: 65px;
}
.espacio{
  margin-top: 65px;
  margin-bottom: 40px;
}
.title {
  font-size: 28px;
  color: #fff;
}
.text{
  color: #fff;
  text-align: justify;
}
</style>
