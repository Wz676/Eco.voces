---
title: "Información y Visión"
date: 2026-03-17
description: "Conoce más sobre nuestro proyecto de reciclaje en la UBA."
layout: "simple"
---

<div style="max-width: 1200px; margin: 50px auto; padding: 0 20px;">
  <h1 style="text-align: center; margin-bottom: 3rem;">Nuestra Misión Ecológica</h1>

  {{< description title="¿Por qué Reciclar?" image="img/image1.jpg" >}}
  Aquí explicamos la importancia del reciclaje dentro de la Universidad Bicentenaria de Aragua. Los desechos tecnológicos y plásticos son un problema creciente.
  {{< /description >}}

  {{< description title="Nuestro Plan de Acción" image="img/image2.jpg" reverse="true" >}}
  A través de la ingeniería de sistemas, proponemos soluciones inteligentes para la clasificación de residuos en el campus.
  {{< /description >}}

</div>

<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  setTimeout(function() {
      AOS.init({ duration: 1000, easing: 'ease-out-cubic', once: true, offset: 80 });
  }, 100); 
</script>