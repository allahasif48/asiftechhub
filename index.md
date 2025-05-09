---
layout: home
title: Welcome
---

<section class="hero">
  <div class="hero-content">
    <h1>Hi, I'm <span class="highlight">Asifali Shaik</span> ✨</h1>
    <p class="subtitle">DevOps Engineer | Cloud Enthusiast | Tech Blogger</p>
    <p>I design scalable infrastructures using AWS, Kubernetes, Terraform, and more. On this site, you'll find my tech blogs, detailed DevOps project walkthroughs, and tutorials.</p>
    <a href="/projects" class="btn">View My Projects</a>
    <a href="/blog" class="btn btn-outline">Read My Blog</a>
  </div>
  <div class="hero-image">
    <img src="/assets/images/hero-image.jpg" alt="Asifali Shaik" />
  </div>
</section>

<section class="features">
  <div class="feature">
    <h2>🚀 Projects</h2>
    <p>Explore my hands-on DevOps projects with real-world architectures, CI/CD pipelines, and cloud deployments.</p>
    <a href="/projects">Explore Projects →</a>
    <img src="/assets/images/projects.jpg" alt="Projects" class="feature-image" />
  </div>
  <div class="feature">
    <h2>📜 Blog</h2>
    <p>Dive into tutorials, lessons learned, and step-by-step guides on DevOps tools and practices.</p>
    <a href="/blog">Read Blog →</a>
    <img src="/assets/images/blog.jpg" alt="Blog" class="feature-image" />
  </div>
  <div class="feature">
    <h2>📞 Contact</h2>
    <p>Let's collaborate! Reach out to discuss projects, job opportunities, or mentoring.</p>
    <a href="/contact">Contact Me →</a>
    <img src="/assets/images/contact.jpg" alt="Contact" class="feature-image" />
  </div>
</section>

<section class="about">
  <h2>About Me</h2>
  <p>I am passionate about building and automating infrastructure using cutting-edge tools and technologies. With experience in cloud services, CI/CD pipelines, and Kubernetes, I help teams scale and optimize their workflows.</p>
  <div class="about-image">
    <img src="/assets/images/about.jpg" alt="Asifali Shaik" />
  </div>
</section>

<style>
.hero {
  display: flex;
  justify-content: space-between;
  padding: 4rem 2rem;
  background-color: #111827;
  color: white;
  border-radius: 10px;
  margin-bottom: 2rem;
}

.hero .hero-content {
  max-width: 50%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.hero .hero-image {
  max-width: 40%;
}

.hero h1 {
  font-size: 2.5rem;
  font-weight: bold;
}

.hero .highlight {
  color: #4ade80;
}

.hero .subtitle {
  font-size: 1.25rem;
  color: #9ca3af;
}

.hero .btn {
  background: #4ade80;
  padding: 1rem 2rem;
  margin-top: 1rem;
  border-radius: 50px;
  color: white;
  text-decoration: none;
}

.hero .btn-outline {
  background: transparent;
  border: 2px solid #4ade80;
  color: #4ade80;
}

.features {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  gap: 2rem;
  padding: 2rem;
}

.feature {
  background: #1f2937;
  color: white;
  border-radius: 12px;
  padding: 1.5rem;
  flex: 1 1 300px;
  text-align: center;
}

.feature h2 {
  color: #4ade80;
}

.feature a {
  color: #93c5fd;
  text-decoration: underline;
}

.feature-image {
  width: 100%;
  margin-top: 1rem;
  border-radius: 8px;
  height: auto;
}

.about {
  text-align: center;
  padding: 2rem;
  background: #2d3748;
  color: white;
  border-radius: 10px;
  margin-top: 2rem;
}

.about-image {
  margin-top: 1rem;
}

.about img {
  max-width: 100%;
  border-radius: 8px;
  height: auto;
}
</style>
