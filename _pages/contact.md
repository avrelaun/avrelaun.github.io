---
permalink: /contact/
title: "Un projet, une question ?"
---

<form
  action="https://formspree.io/mzbjbryr"
  method="POST"
>
  <input type="hidden" name="_language" value="fr" />
  <label>
    Votre nom:
    <input type="text" name="name" required>
  </label>
  <label>
    Votre email:
    <input type="email" name="_replyto" required>
  </label>
  <label>
    C'est à quel sujet ?
    <select name="subject" required>
      <option value="" selected>-- Sujet --</option>
      <option value="freelance">J'ai une mission freelance à te proposer</option>
      <option value="individual">Je suis un particulier ayant un besoin informatique</option>
      <option value="other">J'ai quelque chose d'incroyable à te dire !</option>
    </select>
  </label>
  <label>
    Message:
    <textarea name="message" rows="10"></textarea>
  </label>

  <button type="submit">Envoyer</button>
</form>
