<script lang="ts">
  const src = `https://picsum.photos/720?t=${Math.floor(Math.random() * 100)}`;
</script>

<div>
  <img {src} alt="Random" />
</div>
