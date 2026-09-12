---
title: "Contact"
---

<form action="https://api.web3forms.com/submit" method="POST" style="display: flex; flex-direction: column; gap: 16px; max-width: 480px;">
  <input type="hidden" name="access_key" value="55a98a83-52a6-4ecb-974a-fe014153d299">
  <input type="hidden" name="redirect" value="https://oliver-yee.com/thank-you/">
  <label style="display: flex; flex-direction: column; gap: 6px;">
    Name
    <input type="text" name="name" required style="padding: 8px; border: 1px solid #ccc;">
  </label>
  <label style="display: flex; flex-direction: column; gap: 6px;">
    Email
    <input type="email" name="email" required style="padding: 8px; border: 1px solid #ccc;">
  </label>
  <label style="display: flex; flex-direction: column; gap: 6px;">
    Message
    <textarea name="message" required rows="6" style="padding: 8px; border: 1px solid #ccc;"></textarea>
  </label>
  <button type="submit" style="padding: 10px 20px; background: #000; color: #fff; border: none; cursor: pointer; width: fit-content;">
    Send
  </button>
</form>
