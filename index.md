---
layout: page
title: "Welcome"
permalink: /
---

<section class="hero">
  <div class="hero-content">
    <h1>Hi, I'm <span class="highlight">Asifali Shaik</span> 👋</h1>
    <p class="subtitle">DevOps Engineer | Cloud Enthusiast | Tech Blogger</p>
    <p>
      I design and implement scalable DevOps solutions using AWS, Kubernetes, Terraform, Jenkins, and more.
      Explore my projects, read my technical blog, or connect with me!
    </p>
    <div class="hero-buttons">
      <a href="/projects" class="btn">🚀 View Projects</a>
      <a href="/blog" class="btn btn-outline">📚 Read Blog</a>
    </div>
  </div>
  <div class="hero-image">
    <img src="/assets/images/hero-light.png" alt="Asifali Shaik" />
  </div>
</section>

<section class="features">
  <div class="feature">
    <h2>🔧 Projects</h2>
    <p>Real-world DevOps projects with complete architecture, CI/CD pipelines, and automation scripts.</p>
    <a href="/projects">Explore Projects →</a>
  </div>
  <div class="feature">
    <h2>📝 Blog</h2>
    <p>Read insightful articles on cloud, DevOps tools, productivity tips, and engineering practices.</p>
    <a href="/blog">Read Blog →</a>
  </div>
  <div class="feature">
    <h2>📬 Contact</h2>
    <p>Reach out for collaboration, hiring, or to say hello. I’m always open to new ideas.</p>
    <a href="/contact">Contact Me →</a>
  </div>
</section>

<style>
.hero {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  padding: 3rem 2rem;
  background: #f9fafb;
  border-radius: 16px;
}
.hero-content {
  flex: 1;
  padding: 1rem;
}
.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: #111827;
}
.hero .highlight {
  color: #3b82f6;
}
.hero .subtitle {
  color: #6b7280;
  font-size: 1.25rem;
  margin-bottom: 1rem;
}
.hero-buttons .btn {
  padding: 0.75rem 1.5rem;
  background: #3b82f6;
  color: #fff;
  text-decoration: none;
  border-radius: 8px;
  margin-right: 1rem;
}
.hero-buttons .btn-outline {
  background: transparent;
  border: 2px solid #3b82f6;
  color: #3b82f6;
}
.hero-image {
  flex: 1;
  padding: 1rem;
  text-align: center;
}
.hero-image img {
  max-width: 100%;
  height: auto;
  border-radius: 12px;
}
.features {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  padding: 3rem 1rem;
}
.feature {
  flex: 1 1 300px;
  margin: 1rem;
  padding: 1.5rem;
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
}
.feature h2 {
  color: #2563eb;
}
.feature a {
  color: #2563eb;
  text-decoration: none;
  font-weight: bold;
}
</style>
