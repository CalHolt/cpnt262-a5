<script>
  import "../app.css";
</script>
<body class="flex flex-col min-h-screen">
  
<header class="bg-black flex justify-between p-2">
  <div class="text-white"> <a href="/">Logo</a></div>
  <nav>
    <ul class="flex justify-around gap-4">
      <li class="text-sky-500">
          <a href="/gallery">Gallery</a>
      </li>
      <li class="text-red-500">
        <a href="/store">Store</a>
      </li>
      <li class="text-yellow-500">
        <a href="/contact">Contact</a>
      </li>
    </ul>
  </nav>
</header>
<main class="p-2">
  <slot />

</main>
<footer class="bg-black text-white text-center p-4 mt-auto">
  <p>&copy;<strong> 2023 Cal Holt</strong></p>
</footer>
</body>