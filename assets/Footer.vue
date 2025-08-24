<template>
  <footer class="footer">
    <div class="powered">Powered by <a href="https://workers.cloudflare.com/" target="_blank"
        rel="noopener noreferrer">Cloudflare Workers</a></div>

    <div style="margin:10px 0;">© 2025 军旅旧事云盘. All rights reserved.</div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>


<style scoped>
.footer {
  margin-top: 30px;
  text-align: center;
  padding: 20px;
  background-color: #ffffff77;
  font-size: 16px;
  border-radius: 12px; /* Adjusted for a cleaner look with less content */
}

.powered {
  color: #444;
}

.powered a {
  color: #444;
  text-decoration: none;
}

.powered a:hover {
  color: #222;
}
</style>
