---
title: Form
date: 2022-11-12T21:27:38.156Z
tags: FORM
---
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>NOME: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>EMAIL: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role\[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>