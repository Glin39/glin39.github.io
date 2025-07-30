---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 2
---

<div class="projects-container">
<div class="hero-case-study">
  <div class="case-study-content">
    <div class="case-study-header">
      <h2>Multimodal Health Sensing</h2>
      <p class="case-study-subtitle">Designing tools to support personalized, holistic health understanding using menstrual health as a case study.</p>
    </div>
    
    <div class="case-study-preview">
      <div class="preview-section">
        <div class="preview-item">
          <h4>🎯 Problem</h4>
          <p>Users struggle to make sense of fragmented, complex health data due to tools not supporting holistic understanding or personal context</p>
        </div>
        <div class="preview-item">
          <h4>🔬 Approach</h4>
          <p>Designed and deployed a prototype app integrating user-tracked hormones, wearables, and reflections to support multimodal menstrual health sensemaking</p>
        </div>
        <div class="preview-item">
          <h4>📊 Impact</h4>
          <p>Highlighted the challenges of interpreting complex multimodal data and offered design implications to help users align personal mental models with physiological signals</p>
        </div>
      </div>
      
      <div class="case-study-metrics">
        <div class="metric">
          <span class="metric-number">3</span>
          <span class="metric-label">User Studies</span>
        </div>
        <div class="metric">
          <span class="metric-number">80+</span>
          <span class="metric-label">Participants</span>
        </div>
        <div class="metric">
          <span class="metric-number">6500+</span>
          <span class="metric-label">Days of Health Data Tracked</span>
        </div>
      </div>
    </div>
    
    <div class="case-study-cta">
      <a href="{{ '/projects/menstrual_health/' | relative_url }}" class="cta-button primary">View Full Case Study</a>
    </div>
  </div>
  
  <div class="case-study-visual">
    <img src="{{ '/assets/img/app_gif.gif' | relative_url }}" alt="Menstrual Health Tracking Interface" class="hero-image">
  </div>
</div>

<div class="research-grid">
  <!-- Dynamic Jekyll projects integration -->
  {%- assign featured_projects = site.projects | where: "featured", true | sort: "importance" -%}
  {%- if featured_projects.size > 0 -%}
    {%- for project in featured_projects limit: 3 -%}
    <div class="research-card">
      <div class="card-header">
        {%- if project.img -%}
          <img src="{{ project.img | relative_url }}" alt="{{ project.title }}" class="card-image">
        {%- else -%}
          <img src="{{ '/assets/img/default-project.png' | relative_url }}" alt="{{ project.title }}" class="card-image">
        {%- endif -%}
        <div class="card-badge">{{ project.category | default: "Research" }}</div>
      </div>
      <div class="card-content">
        <h3>{{ project.title }}</h3>
        <p>{{ project.description }}</p>
        {%- if project.tags -%}
        <div class="card-tech">
          {%- for tag in project.tags -%}
          <span class="tech-tag">{{ tag }}</span>
          {%- endfor -%}
        </div>
        {%- endif -%}
      </div>
      <div class="card-footer">
        <a href="{{ project.url | relative_url }}" class="card-link">Learn More →</a>
      </div>
    </div>
    {%- endfor -%}
  {%- else -%}
    <!-- Fallback to manual projects if no featured projects exist -->
    <div class="research-card">
      <div class="card-header">
        <img src="{{ '/assets/img/cooking.png' | relative_url }}" alt="Cooking Assistant" class="card-image">
      </div>
      <div class="card-content">
        <h3>Smart Cooking Assistant</h3>
        <p>Context-aware AI assistant for hands-free cooking interactions and video tutorial support</p>
        <div class="card-tech">
          <span class="tech-tag">Multimodal Assistants</span>
          <span class="tech-tag">UX Research</span>
          <span class="tech-tag">Applied AI</span>
        </div>
      </div>
      <div class="card-footer">
        <a href="{{ '/projects/cooking_assistant/' | relative_url }}" class="card-link">Learn More →</a>
      </div>
    </div>
    <div class="research-card">
      <div class="card-header">
        <img src="{{ '/assets/img/loess.jpeg' | relative_url }}" alt="Loess of WST" class="card-image">
      </div>
      <div class="card-content">
        <h3>Modeling Wearable and Physiological Data Relationships</h3>
        <p>Building models to capture physiological variations across the menstrual cycle</p>
        <div class="card-tech">
          <span class="tech-tag">Wearables</span>
          <span class="tech-tag">Multimodal Sensing</span>
          <span class="tech-tag">Statistical and Machine Learning</span>
        </div>
      </div>
      <div class="card-footer">
        <a href="{{ '/projects/modeling/' | relative_url }}" class="card-link">Learn More →</a>
      </div>
    </div>
    <div class="research-card">
      <div class="card-header">
        <img src="{{ '/assets/img/order_picking.gif' | relative_url }}" alt="Order Picking AR" class="card-image">
      </div>
      <div class="card-content">
        <h3>Industrial AR for Warehouses</h3>
        <p>Optimizing order picking efficiency through head-worn display positioning and interface design</p>
        <div class="card-tech">
          <span class="tech-tag">Head-Worn Displays</span>
          <span class="tech-tag">Interface Design</span>
          <span class="tech-tag">Statistical Analysis</span>
        </div>
      </div>
      <div class="card-footer">
        <a href="{{ '/projects/order_picking/' | relative_url }}" class="card-link">Learn More →</a>
      </div>
    </div>
    <div class="research-card">
      <div class="card-header">
        <img src="{{ '/assets/img/captioning.gif' | relative_url }}" alt="Captioning on Glass" class="card-image">
      </div>
      <div class="card-content">
        <h3>Accessible Real-Time Captioning</h3>
        <p>Captioning on Glass (CoG) for deaf and hard-of-hearing users using head-worn displays such as Google Glass</p>
        <div class="card-tech">
          <span class="tech-tag">Head-Worn Displays</span>
          <span class="tech-tag">Accessibility</span>
          <span class="tech-tag">Statistical Analysis</span>
        </div>
      </div>
      <div class="card-footer">
        <a href="{{ '/projects/captioning/' | relative_url }}" class="card-link">Learn More →</a>
      </div>
    </div>

    
  {%- endif -%}
</div>

<div class="hackathon-section">
  <h2>Innovation & Hackathon Projects</h2>
  <div class="hackathon-grid">
    {%- assign hackathon_projects = site.projects | where: "category", "hackathon" -%}
    {%- if hackathon_projects.size > 0 -%}
      {%- for project in hackathon_projects -%}
      <div class="hackathon-item">
        <div class="hackathon-image">
          <img src="{{ project.img | relative_url }}" alt="{{ project.title }}" class="hackathon-img">
          <div class="hackathon-overlay">
            <h4>{{ project.title }}</h4>
            <p>{{ project.description }}</p>
            {%- if project.tags -%}
            <div class="hackathon-tech">
              {%- for tag in project.tags -%}
              <span>{{ tag }}</span>
              {%- endfor -%}
            </div>
            {%- endif -%}
          </div>
        </div>
        <a href="{{ project.external_url | default: project.url | relative_url }}" target="_blank" class="hackathon-link">
          {%- if project.external_url -%}View on {{ project.platform | default: "External Site" }}{%- else -%}Learn More{%- endif -%}
        </a>
      </div>
      {%- endfor -%}
    {%- else -%}
      <!-- Fallback hackathon projects -->
      <div class="hackathon-item">
        <div class="hackathon-image">
          <img src="{{ '/assets/img/wondarland.png' | relative_url }}" alt="wondARland AR Social Experience" class="hackathon-img">
          <div class="hackathon-overlay">
            <h4>wondARland</h4>
            <p>AR Social Experience</p>
            <div class="hackathon-tech">
              <span>ARCore</span>
              <span>Unity</span>
              <span>C#</span>
            </div>
          </div>
        </div>
        <a href="https://devpost.com/software/wondarland-7lx4st" target="_blank" class="hackathon-link">View on Devpost</a>
      </div>

      <div class="hackathon-item">
        <div class="hackathon-image">
          <img src="{{ '/assets/img/pitch.jpg' | relative_url }}" alt="Personalized interview guidance" class="hackathon-img">
          <div class="hackathon-overlay">
            <h4>Pitch</h4>
            <p>Personalized Interview Guidance</p>
            <div class="hackathon-tech">
              <span>Speech Recognition</span>
              <span>Google Cloud</span>
              <span>APIs</span>
            </div>
          </div>
        </div>
        <a href="https://devpost.com/software/pitch-me" target="_blank" class="hackathon-link">View on Devpost</a>
      </div>

      <div class="hackathon-item">
        <div class="hackathon-image">
          <img src="{{ '/assets/img/ubi.png' | relative_url }}" alt="Ubi Translation Service" class="hackathon-img">
          <div class="hackathon-overlay">
            <h4>Ubi</h4>
            <p>Real-time Translation</p>
            <div class="hackathon-tech">
              <span>Speech Recognition</span>
              <span>NLP</span>
              <span>APIs</span>
            </div>
          </div>
        </div>
        <a href="https://devpost.com/software/ubivoice" target="_blank" class="hackathon-link">View on Devpost</a>
      </div>

      <div class="hackathon-item">
        <div class="hackathon-image">
          <img src="{{ '/assets/img/scan.png' | relative_url }}" alt="Scan" class="hackathon-img">
          <div class="hackathon-overlay">
            <h4>Scan</h4>
            <p>AR bills and coins recognition</p>
            <div class="hackathon-tech">
              <span>Computer Vision</span>
              <span>Augmented Reality</span>
            </div>
          </div>
        </div>
        <a href="https://devpost.com/software/can" target="_blank" class="hackathon-link">View on Devpost</a>
      </div>
    {%- endif -%}
  </div>
</div>

</div>

<style>
.projects-container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 2rem 0;
}

/* Hero Case Study Styles */
.hero-case-study {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  border-radius: 20px;
  padding: 3rem;
  margin: 2rem 0 4rem 0;
  display: grid;
  grid-template-columns: 2fr 1fr;
  gap: 3rem;
  align-items: center;
  color: white;
}

.case-study-header h2 {
  font-size: 2.5rem;
  margin-bottom: 1rem;
  color: white;
}

.case-study-subtitle {
  font-size: 1.2rem;
  opacity: 0.9;
  margin-bottom: 2rem;
  color: white;
}

.preview-section {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-bottom: 2rem;
}

.preview-item h4 {
  color: #ffd700;
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}

.preview-item p {
  font-size: 0.95rem;
  line-height: 1.5;
  opacity: 0.9;
  color: white;
}

.case-study-metrics {
  display: flex;
  gap: 2rem;
  margin-bottom: 2rem;
}

.metric {
  text-align: center;
}

.metric-number {
  display: block;
  font-size: 2rem;
  font-weight: bold;
  color: #ffd700;
}

.metric-label {
  font-size: 0.9rem;
  opacity: 0.8;
  color: white;
}

.hero-image {
  width: 100%;
  height: auto;
  border-radius: 15px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.3);
}

.cta-button.primary {
  background: white;
  color: #667eea;
  padding: 1rem 2rem;
  border-radius: 30px;
  text-decoration: none;
  font-weight: 600;
  display: inline-block;
  transition: all 0.3s ease;
  font-size: 1.1rem;
}

.cta-button.primary:hover {
  transform: translateY(-2px);
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
  color: #667eea;
  text-decoration: none;
}

/* Research Cards Grid */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin: 3rem 0;
}

.research-card {
  background: white;
  border-radius: 15px;
  overflow: hidden;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: all 0.3s ease;
  border: 1px solid #e0e0e0;
}

.research-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(0,0,0,0.15);
}

.card-header {
  position: relative;
  height: 200px;
  overflow: hidden;
}

.card-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.card-badge {
  position: absolute;
  top: 1rem;
  right: 1rem;
  background: rgba(255,255,255,0.9);
  color: #667eea;
  padding: 0.5rem 1rem;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
}

.card-content {
  padding: 1.5rem;
}

.card-content h3 {
  color: #333;
  margin-bottom: 1rem;
  font-size: 1.3rem;
}

.card-content p {
  color: #666;
  line-height: 1.6;
  margin-bottom: 1rem;
}

.card-tech {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1rem;
}

.tech-tag {
  background: #e3f2fd;
  color: #1976d2;
  padding: 0.3rem 0.8rem;
  border-radius: 12px;
  font-size: 0.8rem;
  font-weight: 500;
}

.card-footer {
  padding: 0 1.5rem 1.5rem;
}

.card-link {
  color: #667eea;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.3s ease;
}

.card-link:hover {
  color: #5a6fd8;
  text-decoration: none;
}

/* Hackathon Section */
.hackathon-section {
  margin-top: 4rem;
  padding-top: 2rem;
  border-top: 2px solid #f0f0f0;
}

.hackathon-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.hackathon-item {
  text-align: center;
}

.hackathon-image {
  position: relative;
  border-radius: 15px;
  overflow: hidden;
  height: 200px;
  margin-bottom: 1rem;
  cursor: pointer;
  transition: transform 0.3s ease;
}

.hackathon-image:hover {
  transform: scale(1.05);
}

.hackathon-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.hackathon-overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background: linear-gradient(transparent, rgba(0,0,0,0.8));
  color: white;
  padding: 1.5rem;
  transform: translateY(100%);
  transition: transform 0.3s ease;
}

.hackathon-image:hover .hackathon-overlay {
  transform: translateY(0);
}

.hackathon-overlay h4 {
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}

.hackathon-overlay p {
  margin-bottom: 1rem;
  opacity: 0.9;
}

.hackathon-tech {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  justify-content: center;
}

.hackathon-tech span {
  background: rgba(255,255,255,0.2);
  padding: 0.2rem 0.6rem;
  border-radius: 10px;
  font-size: 0.8rem;
}

.hackathon-link {
  color: #667eea;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.3s ease;
}

.hackathon-link:hover {
  color: #5a6fd8;
  text-decoration: none;
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero-case-study {
    grid-template-columns: 1fr;
    padding: 2rem;
    gap: 2rem;
  }
  
  .case-study-header h2 {
    font-size: 2rem;
  }
  
  .preview-section {
    grid-template-columns: 1fr;
  }
  
  .case-study-metrics {
    justify-content: center;
  }
  
  .research-grid {
    grid-template-columns: 1fr;
  }
  
  .hackathon-grid {
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  }
}
</style>