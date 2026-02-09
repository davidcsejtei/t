<template>
  <div>
    <footer>
      <p>&copy; {{ new Date().getFullYear() }} All rights reserved.</p>
    </footer>
  </div>
</template>

<style scoped>
footer {
  position: fixed;
  bottom: 0;
  left: 0;
  width: 100%;
  padding: 1rem;
  text-align: center;
  background-color: #f8f8f8;
  border-top: 1px solid #e0e0e0;
}

footer p {
  margin: 0;
  font-size: 0.875rem;
  color: #666;
}
</style>
