<template>
    <footer class="footer">
      <div class="container">
        <p>&copy; 2024 My Vue App. Tüm hakları saklıdır.</p>
        <nav>
          <a href="/about">Hakkında</a> |
          <a href="/privacy">Gizlilik Politikası</a> |
          <a href="/contact">İletişim</a>
        </nav>
      </div>
    </footer>
  </template>
  
  <script lang="ts">
  export default {
    name: "FooterComponent",
  };
  </script>
  
  <style scoped>
  .footer {
    background-color: #f8f9fa;
    padding: 20px 0;
    text-align: center;
    font-size: 14px;
    color: #6c757d;
  }
  
  .footer .container a {
    color: #007bff;
    text-decoration: none;
    margin: 0 10px;
  }
  
  .footer .container a:hover {
    text-decoration: underline;
  }
  </style>
  