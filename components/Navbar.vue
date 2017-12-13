<template>
<div class="container">
	<nav class="navbar is-transparent is-12" role="navigation">
	  <button class="button navbar-burger" data-target="navMenu">
	   <span></span>
	   <span></span>
	   <span></span>
	  </button>
	   <div class="navbar-menu" id="navMenu">
		  <div class="navbar-star">
		  	<a class="navbar-item">
			 Home
		  	</a>
		  	<a class="navbar-item">
			 Profesional
		  	</a>
		  	<a class="navbar-item">
			 Experiencia
		  	</a>
		  	<a class="navbar-item">
			 Portafolio
		  	</a>
		  	<a class="navbar-item">
			 Contacto
		  	</a>
		  </div>
	   </div>
	</nav>
</div>
</template>
<script>
document.addEventListener('DOMContentLoaded', function () {
  // Get all "navbar-burger" elements
  var $navbarBurgers = Array.prototype.slice.call(document.querySelectorAll('.navbar-burger'), 0)
  // Check if there are any navbar burgers
  if ($navbarBurgers.length > 0) {
    // Add a click event on each of them
    $navbarBurgers.forEach(function ($el) {
      $el.addEventListener('click', function () {
        // Get the target from the "data-target" attribute
        var target = $el.dataset.target
        var $target = document.getElementById(target)
        // Toggle the class on both the "navbar-burger" and the "navbar-menu"
        $el.classList.toggle('is-active')
        $target.classList.toggle('is-active')
      })
    })
  }
})
</script>