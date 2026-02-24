---
title: "Eco.Voces"
layout: "simple"
---

{{< slider media="media/001.png,media/002.png,media/003.png" >}}

<h2 id="vision" style="text-align: center; margin-top: 2rem;"></h2>

<div style="max-width: 1000px; margin: 0 auto; padding: 0 20px;"> 

<h2 id="descripcion" style="text-align: center; margin-top: 4rem; margin-bottom: 3rem; font-size: 2.5rem;"></h2>

{{< description title="Protegiendo Nuestro Entorno" media="media/001.png" >}}
Como estudiantes, entendemos que la tecnología y la naturaleza deben coexistir en perfecto equilibrio. Nuestro proyecto busca generar conciencia sobre los ecosistemas locales, desde nuestras costas hasta nuestras comunidades urbanas. Cada pequeña acción, sumada, genera un impacto sistémico positivo.
{{< /description >}}

{{< description title="Tecnología para el Cambio" media="media/002.png" reverse="true" >}}
No solo hablamos de ecología; aplicamos el pensamiento estructurado para resolver problemas ambientales. A través de Eco.Voces, combinamos análisis de datos, interactividad y educación digital para empoderar a nuestra comunidad y construir un futuro más sostenible.
{{< /description >}}

</div>


<div style="max-width: 1200px; margin: 0 auto; padding: 0 20px; margin-bottom: 5rem;">

<h2 id="video" style="text-align: center; margin-top: 5rem; margin-bottom: 2rem; font-size: 2.5rem;">Galería Multimedia</h2>

{{< youtubegallery ids="MkRZGat1hks,K15rvmw2WwI,IPFokO5aTAk" >}}

</div>

<link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
<script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
<script>
  // 稍微延迟 0.1 秒启动，确保前面的图文和背景已经完全加载
  setTimeout(function() {
      AOS.init({
        duration: 1000,       // 动画持续 1 秒，极其丝滑
        easing: 'ease-out-cubic',
        once: true,           // 只在第一次滑到时执行
        offset: 80            // 距离屏幕底部 80px 时精准触发
      });
  }, 100); 
</script>