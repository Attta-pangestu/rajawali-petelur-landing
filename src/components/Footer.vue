<template>
    <footer class="footer">
      <div class="footer-content">
        <p>© 2024 Rajawali Farm</p>
        <p class="credit">Designed & Developed by <span class="developer-name">Atha Rizki Pangestu</span></p>
        <div class="social-links">
          <a href="https://github.com/YourGithub" target="_blank" rel="noopener noreferrer">GitHub</a>
          <a href="https://linkedin.com/in/YourLinkedIn" target="_blank" rel="noopener noreferrer">LinkedIn</a>
        </div>
      </div>
    </footer>
  </template>
  
  <style scoped>
  .footer {
    background-color: #2c3e50;
    color: white;
    padding: 2rem 0;
    margin-top: auto;
  }
  
  .footer-content {
    max-width: 1200px;
    margin: 0 auto;
    text-align: center;
    padding: 0 1rem;
  }
  
  .credit {
    margin: 0.5rem 0;
  }
  
  .developer-name {
    color: #ffd700;
    font-weight: bold;
  }
  
  .social-links {
    margin-top: 1rem;
  }
  
  .social-links a {
    color: white;
    text-decoration: none;
    margin: 0 1rem;
    transition: color 0.3s ease;
  }
  
  .social-links a:hover {
    color: #ffd700;
  }
  </style>