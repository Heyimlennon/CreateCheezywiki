---
title: Create Cheezy Wiki
---

# 🧀 Create Cheezy Mod Wiki

Welcome to the official wiki for the **Create Cheezy** Minecraft mod!

> 🍞 Create Cheezy is an addon for the [Create Mod](https://www.curseforge.com/minecraft/mc-mods/create) that adds **new cheese items and blocks to make your game more delicious and i hope you enjoy!

## 🔗 Downloads

- 📦 CurseForge: [Create Cheezy on CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-cheezy)
- 🧰 Requires: [Create Mod](https://www.curseforge.com/minecraft/mc-mods/create)

## 📖 Contents

- [Getting Started](getting-started.md)
- [Items & Blocks](items.md)
- [Crafting Recipes](recipes.md)
- [Developer](developer.md)

---

## 🧀 What is Create Cheezy?

Create Cheezy expands the Create Mod by introducing:

- CHEESE more cheese items
- And more

---

## 👨‍💻 Contributing

Found a bug or want to contribute to the wiki?  
Open an issue or pull request on [[Discord](https://discord.gg/YYU5TcRzsm). and message me 

---

## 📬 Contact the Developer (Offline Form)

<!-- UI-Only Contact Form - Not connected to email service -->
<button onclick="toggleForm()" style="padding: 10px 20px; font-size: 16px;">Contact Me</button>

<div id="contactForm" style="display: none; flex-direction: column; gap: 10px; background: #f9f9f9; padding: 20px; margin-top: 10px; border: 1px solid #ccc; border-radius: 10px; max-width: 400px;">
  <input id="emailInput" type="email" placeholder="Your email" required style="padding: 10px; border-radius: 5px; border: 1px solid #ccc;" />
  <textarea id="messageInput" placeholder="Write your message here..." required style="padding: 10px; border-radius: 5px; border: 1px solid #ccc; min-height: 100px;"></textarea>
  
  <button onclick="handleForm()" style="padding: 10px; background: #007bff; color: white; border: none; border-radius: 5px;">Send Message</button>
</div>

<script>
  function toggleForm() {
    const form = document.getElementById("contactForm");
    form.style.display = form.style.display === "flex" ? "none" : "flex";
  }

  function handleForm() {
    const email = document.getElementById("emailInput").value;
    const message = document.getElementById("messageInput").value;
    alert("Thanks! You entered:\nEmail: " + email + "\nMessage: " + message);
    // Here you could send this info to a backend or Discord webhook in the future
  }
</script>
