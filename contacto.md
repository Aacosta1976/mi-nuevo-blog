---
layout: base
title: Contacto
permalink: /contacto/
---

<h1>Formulario de contacto</h1>
<p>Puedes dejarme un mensaje usando el siguiente formulario:</p>

<div class="form-wrapper">
  <form action="https://formspree.io/f/tu-codigo-aqui" method="POST" class="contact-form">
    <div class="form-group">
      <label for="nombre">Nombre</label>
      <input type="text" id="nombre" name="nombre" placeholder="Tu nombre completo" required>
    </div>

    <div class="form-group">
      <label for="email">Correo electrónico</label>
      <input type="email" id="email" name="_replyto" placeholder="ejemplo@correo.com" required>
    </div>

    <div class="form-group">
      <label for="mensaje">Mensaje</label>
      <textarea id="mensaje" name="mensaje" rows="5" placeholder="Escribe tu mensaje aquí..." required></textarea>
    </div>

    <button type="submit">Enviar mensaje</button>
  </form>
</div>
