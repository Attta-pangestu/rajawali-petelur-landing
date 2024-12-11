<template>
  <div class="blog-container">
    <h1 class="blog-title">Blog Rajawali Farm</h1>
    
    <div class="blog-grid">
      <!-- Blog Card 1 -->
      <div class="blog-card">
        <img src="@/assets/blog1.jpg" alt="Peternakan Ayam Modern" class="blog-image">
        <div class="blog-content">
          <h2>Peternakan Ayam Modern di Era Digital</h2>
          <p class="blog-date">11 Desember 2024</p>
          <p class="blog-excerpt">
            Bagaimana teknologi modern membantu meningkatkan produktivitas peternakan ayam...
          </p>
          <a href="#" class="read-more">Baca Selengkapnya</a>
        </div>
      </div>

      <!-- Blog Card 2 -->
      <div class="blog-card">
        <img src="@/assets/blog2.jpg" alt="Kualitas Telur" class="blog-image">
        <div class="blog-content">
          <h2>Tips Memilih Telur Berkualitas</h2>
          <p class="blog-date">10 Desember 2024</p>
          <p class="blog-excerpt">
            Panduan lengkap cara memilih telur yang segar dan berkualitas...
          </p>
          <a href="#" class="read-more">Baca Selengkapnya</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.blog-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem;
}

.blog-title {
  text-align: center;
  color: #2c3e50;
  margin-bottom: 2rem;
  font-size: 2.5rem;
}

.blog-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}

.blog-card {
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.blog-card:hover {
  transform: translateY(-5px);
}

.blog-image {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.blog-content {
  padding: 1.5rem;
}

.blog-content h2 {
  color: #2c3e50;
  margin-bottom: 0.5rem;
  font-size: 1.25rem;
}

.blog-date {
  color: #666;
  font-size: 0.9rem;
  margin-bottom: 1rem;
}

.blog-excerpt {
  color: #555;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.read-more {
  display: inline-block;
  color: #a06729;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s ease;
}

.read-more:hover {
  color: #7c4e1e;
}

@media (max-width: 768px) {
  .blog-container {
    padding: 1rem;
  }
  
  .blog-title {
    font-size: 2rem;
  }
}
</style>