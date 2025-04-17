---
layout: page
permalink: /contact/
title: Contact
description: If you wish to contact me fill in the form below
nav: true
nav_order: 7
---
<style>
  .input-group-text {
    margin-right: 0.5em;
  }
  button {
    background-color: var(--global-theme-color) !
  }

  /* Dark mode styles */
  @media (prefers-color-scheme: dark) {
    .input-group input,
    textarea,
    textarea.form-control {
      background-color: #aaa !important;
      color: #fff !important;
    }

    .input-group input:focus,
    textarea:focus,
    textarea.form-control:focus {
      background-color: #bbb !important;
      color: #000 !important;
    }
  }

  /* Light mode styles */
  @media (prefers-color-scheme: light) {
    .input-group input,
    textarea,
    textarea.form-control {
      background-color: #fff !important;
      color: #000 !important;
    }

    .input-group input:focus,
    textarea:focus,
    textarea.form-control:focus {
      background-color: #f9f9f9 !important;
      color: #000 !important;
    }
  }
</style>

<form method="post" action="https://forms.un-static.com/forms/1df193f73e588f6d05bf46e46694ae7db2002fcf" class="form-container">

  <div class="mb-3">
    <label for="name" class="form-label">Name</label>
    <div class="input-group">
      <span class="input-group-text"><i class="fa fa-user"></i></span>
      <input id="name" name="name" type="text" class="form-control" placeholder="Enter your name" required>
    </div>
  </div>

  <div class="mb-3">
    <label for="email" class="form-label">Email</label>
    <div class="input-group">
      <span class="input-group-text"><i class="fa fa-envelope"></i></span>
      <input id="email" name="email" type="email" class="form-control" placeholder="Your email address" required>
    </div>
  </div>

  <div class="mb-4">
    <label for="message" class="form-label">Message</label>
    <textarea id="message" name="message" rows="5" class="form-control" placeholder="Type your message here..." required></textarea>
  </div>

  <div class="d-grid">
    <button type="submit" class="btn btn-primary">Send Message</button>
  </div>
</form>

<div class="text-center mt-3">
  <small>(Powered by <a href="https://un-static.com" target="_blank" rel="nofollow">Un-static Forms</a>)</small>
</div>