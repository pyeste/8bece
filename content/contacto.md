---
title: "Contacto"
description: "Ponte en contacto con nosotras."
draft: false
---

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 2rem; margin-top: 1.5rem;">

<div>
<h3>¡Hablemos!</h3>
<p>¿Tienes alguna duda o propuesta? Escríbenos directamente o utiliza el formulario.</p>

<h4>📧 Correo Electrónico</h4>
<p style="margin-bottom:0.5rem;"><a href="mailto:desdenmail.duck.com">desdenmail@duck.com</a></p>

</div>
</div>

<div>
<h3>Envíanos un mensaje</h3>

<form action="https://formspree.io/f/xljewbop" method="POST" style="display: flex; flex-direction: column; gap: 1rem;">

<div>
<label style="display:block; font-weight:600; margin-bottom:0.3rem;">Nombre completo</label>
<input type="text" name="name" required placeholder="Tu nombre" style="width: 100%; padding: 0.6rem; border-radius: 6px; border: 1px solid var(--tertiary); background: var(--entry); color: var(--primary);">
</div>

<div>
<label style="display:block; font-weight:600; margin-bottom:0.3rem;">Email de contacto</label>
<input type="email" name="email" required placeholder="tu@email.com" style="width: 100%; padding: 0.6rem; border-radius: 6px; border: 1px solid var(--tertiary); background: var(--entry); color: var(--primary);">
</div>

<div>
<label style="display:block; font-weight:600; margin-bottom:0.3rem;">Asunto</label>
<input type="text" name="subject" placeholder="¿En qué podemos ayudarte?" style="width: 100%; padding: 0.6rem; border-radius: 6px; border: 1px solid var(--tertiary); background: var(--entry); color: var(--primary);">
</div>

<div>
<label style="display:block; font-weight:600; margin-bottom:0.3rem;">Mensaje</label>
<textarea name="message" rows="4" required placeholder="Escribe aquí tu mensaje..." style="width: 100%; padding: 0.6rem; border-radius: 6px; border: 1px solid var(--tertiary); background: var(--entry); color: var(--primary); font-family: inherit;"></textarea>
</div>

<button type="submit" class="btn-contacto">
  Enviar Mensaje
</button>

</form>
</div>

</div>