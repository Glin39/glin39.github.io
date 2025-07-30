---
layout: page
title: Captioning on Glass
description: Exploring real-time captioning using head-worn displays like Google Glass to support d/Deaf and hard-of-hearing users in both stationary and mobile tasks.
img: assets/img/captioning.gif
importance: 3
category: research
related_publications: tu2020conversational, tu2020towards
---

<div class="portfolio-case-study">
  
  <!-- TL;DR Hero Section -->
  <section class="tldr-hero">
    <div class="tldr-badge">TL;DR</div>
    <h1 class="hero-title">Real-Time Captioning for Head-Worn Displays</h1>
    <div class="hero-subtitle">
      <p>Designing accessible captioning interfaces that support d/Deaf and hard-of-hearing users across static and dynamic environments using Google Glass and other head-worn display technologies.</p>
    </div>
    
    <!-- Demo Section -->
    <div class="demo-section">
      <h3>Research Demo Video</h3>
      <div class="video-container">
        <iframe
          width="100%"
          height="315"
          src="https://www.youtube.com/embed/1ylnGQ7kLJM"
          title="Captioning on Google Glass Research Demo"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen>
        </iframe>
      </div>
    </div>
  </section>

  <!-- Problem Statement -->
  <section class="problem-section">
    <div class="section-header">
      <h2>The Problem</h2>
    </div>
    <div class="problem-content">
      <div class="problem-statement">
        <h3>Current captioning solutions don't support natural interaction in dynamic environments</h3>
        <p>By 2050, the WHO estimates 1 in 10 people will have disabling hearing loss. While smartphone captioning has become more common, these solutions require users to look down at devices, creating barriers in mobile contexts where hands-free use and environmental awareness are essential for safety and social interaction.</p>
      </div>
      
      <div class="problem-details">
        <div class="problem-point">
          <h4>Visual attention fragmentation disrupts task flow</h4>
          <p>Users must constantly shift focus between their environment, the person speaking, and caption displays on handheld devices, creating cognitive overhead and missing critical contextual information.</p>
        </div>
        
        <div class="problem-point">
          <h4>Mobile scenarios require hands-free accessibility</h4>
          <p>Navigation, workplace tasks, and social interactions demand solutions that don't occupy users' hands or require them to break eye contact with their environment and conversation partners.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- My Role -->
  <section class="role-section">
    <div class="section-header">
      <h2>What I Did</h2>
    </div>
    <div class="role-grid">
      <div class="role-card">
        <div class="role-icon">🛠️</div>
        <h4>Prototype Development</h4>
        <p>Built cross-platform captioning prototypes for Google Glass and Vuzix Blade, optimizing for latency and readability</p>
      </div>
      <div class="role-card">
        <div class="role-icon">🔬</div>
        <h4>Comparative User Studies</h4>
        <p>Designed and conducted controlled experiments comparing HWD vs. smartphone captioning across stationary and mobile contexts</p>
      </div>
      <div class="role-card">
        <div class="role-icon">📊</div>
        <h4>Interaction Design Analysis</h4>
        <p>Analyzed user behavior patterns, response times, and comfort metrics to derive design principles for accessible HWD interfaces</p>
      </div>
    </div>
  </section>

  <!-- Research Approach -->
  <section class="approach-section">
    <div class="section-header">
      <h2>Experimental Design & Methodology</h2>
    </div>

    <div class="media-placeholder media-placeholder-large">
      <img src="{{ '/assets/img/captioning.gif' | relative_url }}" alt="Captioning interface on Google Glass showing real-time text overlay">
      <p>Real-time captioning interface prototype running on Google Glass Enterprise Edition</p>
    </div>
    
    <div class="approach-content">
      <div class="research-goal">
        <h3>Research Hypothesis</h3>
        <p class="goal-text">Head-worn displays provide statistically significant improvements in response time, cognitive workload, and task performance compared to smartphone-based captioning in both stationary and mobile contexts.</p>
        <ul class="goal-questions">
          <li>H₁: HWDs will demonstrate faster response times and lower cognitive workload in controlled tasks</li>
          <li>H₂: Mobile navigation scenarios will show greater performance advantages for HWDs vs. smartphones</li>
          <li>H₃: Subjective preference measures will favor HWD modalities across comfort and usability dimensions</li>
        </ul>
      </div>

      <div class="two-column">
        <div class="method-card">
          <div class="method-title">Study 1: Controlled Assembly Task</div>
          <p><strong>Experimental design:</strong> Within-subjects comparison using balanced Latin square counterbalancing</p>
          <p><strong>Independent variables:</strong> Display modality (Google Glass EE2, Vuzix Blade, Razer Phone)</p>
          <p><strong>Dependent measures:</strong> NASA-TLX workload scores, task completion accuracy, head movement frequency</p>
          <p><strong>Controls:</strong> Noise-cancelling headphones, standardized instruction delivery, identical task complexity</p>
        </div>
        <div class="method-card">
          <div class="method-title">Study 2: Mobile Name Detection</div>
          <p><strong>Experimental design:</strong> Repeated measures with counterbalanced room navigation order</p>
          <p><strong>Task protocol:</strong> Multi-floor navigation with random name presentation (8-12s intervals)</p>
          <p><strong>Response metrics:</strong> Button-press reaction times, false positive rates, subjective workload</p>
          <p><strong>Environmental controls:</strong> Indoor lighting, standardized acoustic conditions, identical navigation distance</p>
        </div>
      </div>

      <div class="stats-grid">
        <div class="stat-card">
          <span class="stat-number">α=0.05</span>
          <div class="stat-label">Statistical significance threshold</div>
        </div>
        <div class="stat-card">
          <span class="stat-number">2×2</span>
          <div class="stat-label">Balanced Latin square design</div>
        </div>
      </div>

      <div class="design-decision">
        <div class="design-decision-label">
          <strong>Technical Implementation</strong>
        </div>
        <p>Microsoft Azure Cognitive Services Speech-to-Text API provided real-time transcription with custom post-processing pipeline. Cross-platform implementation ensured identical caption delivery timing across all devices.</p>
      </div>
    </div>
  </section>

  <!-- UX Analysis Framework -->
  <section class="analysis-section">
    <div class="section-header">
      <h2>Statistical Analysis Framework</h2>
    </div>
    
    <div class="analysis-content">
      <div class="analysis-process">
        <div class="process-step">
          <div class="step-number">01</div>
          <div class="step-content">
            <h4>NASA-TLX Workload Analysis</h4>
            <p>Conducted paired t-tests across six workload dimensions (mental, physical, temporal, performance, effort, frustration) with Bonferroni correction for multiple comparisons. Also calculated effect sizes (Cohen's d) and statistical power across workload dimensions. Achieved statistical significance for overall workload differences between HWD and smartphone conditions.</p>
            <div class="data-table">
              <table>
                <thead>
                  <tr>
                    <th>NASA TLX</th>
                    <th>Glass vs. Phone (n=12)</th>
                    <th>Vuzix vs. Phone (n=8)</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><strong>Overall</strong></td>
                    <td>p=0.003*, 1−β=0.778, d=0.983</td>
                    <td>p=0.016*, 1−β=0.614, d=0.967</td>
                  </tr>
                  <tr>
                    <td><strong>Mental</strong></td>
                    <td>p=0.019*</td>
                    <td>p=0.015*, 1−β=0.748, d=1.156</td>
                  </tr>
                  <tr>
                    <td><strong>Physical</strong></td>
                    <td>p=0.104</td>
                    <td>p=0.035*, 1−β=0.610, d=0.961</td>
                  </tr>
                  <tr>
                    <td><strong>Effort</strong></td>
                    <td>p=0.006*, 1−β=0.813*, d=1.034</td>
                    <td>p=0.430</td>
                  </tr>
                  <tr>
                    <td><strong>Frustration</strong></td>
                    <td>p=0.013*</td>
                    <td>p=0.306</td>
                  </tr>
                </tbody>
              </table>
            </div>
            <p style="font-size: 0.75em; margin-top: 0.5em;"><em>Note: p &lt; 0.05, 1−β &lt; 0.8</em></p>                    
            </div>
          </div>
        </div>
        
        <div class="process-step">
          <div class="step-number">02</div>
          <div class="step-content">
            <h4>Response Time Distribution Analysis</h4>
            <p>Used repeated measures ANOVA with device condition as within-subjects factor, controlling for learning effects through counterbalanced presentation order. Aggregate response times (left). Difference in TLX scores (negative indicates a lower HWD workload) (right).</p>
            
            <div class="media-placeholder media-placeholder-small">
              <img src="{{ '/assets/img/combinedgraphs.png' | relative_url }}" alt="Aggregate response times (left). Difference in TLX scores (negative indicates a lower HWD workload) (right).">
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Key Findings -->
  <section class="findings-section">
    <div class="section-header">
      <h2>Statistical Results & Findings</h2>
    </div>
    
    <div class="insights-grid">
      <div class="insight-card">
        <div class="insight-number">1</div>
        <div class="insight-title">Significant workload reduction with large effect sizes across modalities</div>
        <div class="insight-content">
          <p>Paired t-tests revealed statistically significant differences in cognitive workload measures between HWD and smartphone conditions:</p>
          <ul class="insight-list">
            <li><strong>Overall NASA-TLX:</strong> Google Glass vs. Phone (p=0.003, d=0.983, 1-β=0.778)</li>
            <li><strong>Mental workload:</strong> Vuzix vs. Phone (p=0.015, d=1.156, 1-β=0.748)</li>
            <li><strong>Effort reduction:</strong> Google Glass vs. Phone (p=0.006, d=1.034, 1-β=0.813)</li>
            <li><strong>Physical workload:</strong> Vuzix vs. Phone (p=0.035, d=0.961, 1-β=0.610)</li>
          </ul>
          <p>All significant results maintained statistical power above 0.60, with several exceeding the 0.80 threshold for adequate power.</p>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">2</div>
        <div class="insight-title">Substantial response time improvements in mobile detection tasks</div>
        <div class="insight-content">
          <p>Mobile name detection study demonstrated quantifiable performance advantages for HWD modalities:</p>
          <ul class="insight-list">
            <li><strong>Response time improvement:</strong> HWD mean 2.7s vs. Phone mean 4.3s (p=0.033)</li>
            <li><strong>Reduced variability:</strong> HWD σ=0.706s vs. Phone σ=2.222s (68% reduction in standard deviation)</li>
            <li><strong>Comfort preference:</strong> Significant preference for HWD comfort (p<0.001)</li>
            <li><strong>Consistent detection:</strong> Lower false negative rates in dynamic navigation contexts</li>
          </ul>
          <p>The 1.63-second improvement represents a 37% reduction in reaction time with substantially improved consistency.</p>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">3</div>
        <div class="insight-title">Device-specific performance characteristics influence user experience</div>
        <div class="insight-content">
          <p>Systematic performance benchmarking revealed platform-dependent trade-offs affecting user outcomes:</p>
          <ul class="insight-list">
            <li><strong>Speech recognition accuracy:</strong> Phone 96% > Vuzix 95% > Google Glass 86%</li>
            <li><strong>Display clarity trade-offs:</strong> Glass clarity reduced eyestrain vs. Vuzix fuzzy display complaints</li>
            <li><strong>Recognition error correlation:</strong> Glass frustration scores linked to 10% lower ASR accuracy</li>
            <li><strong>Physical comfort factors:</strong> Weight distribution and thermal comfort affected sustained usage</li>
          </ul>
          <p>Technical implementation choices directly impacted statistical outcomes, highlighting the importance of platform optimization.</p>
        </div>
      </div>
    </div>
  </section>


  <!-- Key Insight -->
  <section class="insight-section">
    <div class="insight-content">
      <div class="insight-icon">💡</div>
      <div class="insight-text">
        <h3>Reflection</h3>
        <p> This project demonstrated the promise of head-worn displays for enabling accessible, real-time captioning in both stationary and mobile situations. While smartphones remain ubiquitous, HWDs offer hands-free, contextually integrated caption delivery that can improve social and task-related communication for DHH users. Future work may explore how to improve display readability, comfort for extended wear, and integration with modern ASR systems in noisy or outdoor environments. </p>
      </div>
    </div>
  </section>
</div>

<style>
:root {
  /* Use Jekyll theme variables when available, fallback to neutral academic colors */
  --primary-color: var(--global-theme-color, #2563eb);
  --primary-light: var(--global-theme-color-light, #93c5fd);
  --primary-dark: var(--global-theme-color-dark, #1d4ed8);
  --secondary-color: var(--global-secondary-color, #B509AC);
  --text-color: var(--global-text-color, #374151);
  --text-light: var(--global-text-color-light, #6b7280);
  --background-light: var(--global-bg-color-light, #f9fafb);
  --border-color: var(--global-divider-color, #e5e7eb);
  --success-color: var(--global-success-color, #059669);
  --card-bg: var(--global-card-bg-color, #ffffff);
  --gradient-bg: linear-gradient(135deg, var(--primary-color) 0%, var(--primary-dark) 100%);
  
  /* Define explicit colors for light/dark mode handling */
  --hero-text-color: #ffffff;
  --card-text-color: #374151;
  --card-title-color: var(--primary-color);
  --insight-text-color: #ffffff;
  --warning-bg: #fef3c7;
  --warning-border: #f59e0b;
  --warning-text: #92400e;
}

.portfolio-case-study {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0;
  font-family: var(--global-font-family, -apple-system, BlinkMacSystemFont, 'Segoe UI', system-ui, sans-serif);
  line-height: 1.6;
  color: var(--text-color);
}

/* Demo Section Styling */
.demo-section {
  margin-top: 40px;
  padding-top: 40px;
  border-top: 2px solid rgba(255, 255, 255, 0.2);
}

.demo-section h3 {
  font-size: 1.5rem;
  margin-bottom: 25px;
  font-weight: 500;
  opacity: 0.95;
  color: var(--hero-text-color);
}

.video-container {
  position: relative;
  width: 100%;
  max-width: 600px;
  margin: 0 auto 25px;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
  background: rgba(255, 255, 255, 0.1);
  backdrop-filter: blur(10px);
}

.video-container iframe {
  display: block;
  border-radius: 12px;
}

/* TL;DR Hero Section */
.tldr-hero {
  text-align: center;
  padding: 60px 40px 80px;
  background: var(--gradient-bg);
  color: var(--hero-text-color);
  border-radius: 12px;
  margin-bottom: 60px;
  position: relative;
}

.tldr-badge {
  display: inline-block;
  background: rgba(255, 255, 255, 0.2);
  padding: 8px 16px;
  border-radius: 20px;
  font-weight: 600;
  font-size: 0.9rem;
  margin-bottom: 20px;
  backdrop-filter: blur(10px);
  color: var(--hero-text-color);
}

.hero-title {
  font-size: clamp(1.2rem, 2.3vw, 1.8rem);
  font-weight: 700;
  margin-bottom: 30px;
  line-height: 1.2;
  color: var(--hero-text-color);
}

.hero-subtitle {
  max-width: 800px;
  margin: 0 auto;
  font-size: 1.1rem;
  line-height: 1.7;
  opacity: 0.95;
  color: var(--hero-text-color);
}

.hero-subtitle p, strong {
  margin-bottom: 20px;
  color: var(--hero-text-color);
}

/* Metrics Strip */
.metrics-strip {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 30px;
  padding: 40px;
  background: var(--card-bg);
  border-radius: 12px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
  margin: -30px 20px 60px;
  position: relative;
  z-index: 2;
  border: 1px solid var(--border-color);
}

.metric-item {
  text-align: center;
}

.metric-number {
  font-size: 2.5rem;
  font-weight: 700;
  color: var(--primary-color);
  line-height: 1;
}

.metric-label {
  font-size: 0.9rem;
  color: var(--text-light);
  margin-top: 8px;
}

/* Section Styling */
.portfolio-case-study section {
  margin-bottom: 80px;
}

.section-header {
  display: flex;
  align-items: center;
  gap: 12px;
  margin-bottom: 40px;
}

.section-header h2 {
  font-size: 2.2rem;
  font-weight: 700;
  margin: 0;
  color: var(--text-color);
}

/* Problem Section */
.problem-content {
  display: grid;
  gap: 40px;
}

.problem-statement {
  background: var(--background-light);
  padding: 40px;
  border-radius: 16px;
  border-left: 5px solid var(--primary-color);
}

.problem-statement h3 {
  color: var(--primary-color);
  font-size: 1.4rem;
  margin-bottom: 20px;
  font-weight: 600;
}

.problem-details {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.problem-point {
  background: white;
  padding: 30px;
  border-radius: 12px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
  border: 1px solid var(--border-color);
}

.problem-point h4 {
  color: var(--primary-color);
  margin-bottom: 12px;
  font-weight: 600;
}

.problem-section p {
  color: #374151 !important;
}

/* Role Section */
.role-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 24px;
}

.role-card {
  background: var(--card-bg);
  padding: 30px;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
  border: 1px solid var(--border-color);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.role-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
}

.role-icon {
  font-size: 2.5rem;
  margin-bottom: 16px;
}

.role-card h4 {
  color: var(--primary-color);
  margin-bottom: 12px;
  font-weight: 600;
}

/* Research Approach */
.approach-content {
  background: var(--card-bg);
  padding: 40px;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
  border: 1px solid var(--border-color);
}

.research-goal {
  background: var(--background-light);
  padding: 28px;
  border-radius: 12px;
  border-left: 4px solid var(--primary-color);
  margin-bottom: 40px;
}

.research-goal h3 {
  color: var(--primary-color);
  margin-bottom: 16px;
  font-size: 1.3rem;
  font-weight: 600;
}

.goal-text {
  font-size: 1.1rem;
  margin-bottom: 16px;
  font-weight: 500;
  color: var(--card-text-color);
}

.goal-questions {
  list-style: none;
  padding: 0;
  margin: 0;
}

.goal-questions li {
  padding: 8px 0;
  position: relative;
  padding-left: 20px;
  color: var(--card-text-color);
}

.goal-questions li:before {
  content: "→";
  color: var(--primary-color);
  font-weight: bold;
  position: absolute;
  left: 0;
}

/* Two Column Layout */
.two-column {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 32px;
  margin: 24px 0;
}

.method-card {
  background: white;
  padding: 24px;
  border-radius: 12px;
  border: 1px solid var(--border-color);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
}

.method-card p, 
.method-card p strong {
  color: var(--card-text-color);
}

.method-title {
  font-weight: 600;
  color: var(--primary-color);
  margin-bottom: 12px;
  font-size: 1.1rem;
}

/* Stats Grid */
.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 20px;
  margin: 24px 0;
}

.stat-card {
  background: white;
  padding: 20px;
  border-radius: 12px;
  text-align: center;
  border: 1px solid var(--border-color);
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.04);
}

.stat-number {
  font-size: 2.2rem;
  font-weight: 700;
  color: var(--primary-color);
  display: block;
  line-height: 1;
}

.stat-label {
  font-size: 0.9rem;
  color: var(--card-text-color);
  margin-top: 8px;
}

/* Media Placeholders */
.media-placeholder {
  background: var(--background-light);
  border: 2px dashed var(--border-color);
  text-align: center;
  margin: 24px 0;
  color: var(--text-light);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap: 12px;
  border-radius: 12px;
}

.media-placeholder-large {
  min-height: 300px;
}

.media-placeholder-small {
  min-height: 200px;
}

.media-placeholder img {
  width: 100%;
  height: 100%;
  object-fit: contain;
  border-radius: 12px;
  display: block;
}

.media-placeholder p {
  font-style: italic;
  font-size: 0.9rem;
  margin: 8px 0 0 0;
}

.placeholder-content {
  text-align: center;
  padding: 20px;
}

.placeholder-content strong {
  color: var(--primary-color);
  font-size: 1.1rem;
  display: block;
  margin-bottom: 10px;
}

.placeholder-content th{
  color: black;
}

/* Design Decision Callout */
.design-decision {
  background: var(--warning-bg);
  padding: 24px;
  border-radius: 12px;
  border-left: 4px solid var(--warning-border);
  margin: 24px 0;
}

.design-decision-label {
  font-weight: 700;
  color: var(--warning-text);
  margin-bottom: 12px;
  display: flex;
  align-items: center;
  gap: 8px;
}

.design-decision p,
.design-decision strong {
  color: var(--warning-text);
  margin: 0;
}

/* Key Insights */
.insights-grid {
  display: grid;
  gap: 24px;
}

.insight-card {
  background: white;
  padding: 28px;
  border-radius: 12px;
  border: 1px solid var(--border-color);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
}

.insight-number {
  background: var(--primary-color);
  color: white;
  width: 32px;
  height: 32px;
  border-radius: 50%;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 0.9rem;
  margin-bottom: 16px;
}

.insight-title {
  font-size: 1.1rem;
  font-weight: 600;
  color: var(--primary-color);
  margin-bottom: 16px;
}

.insight-content p {
  color: var(--card-text-color);
  margin-bottom: 16px;
}

.insight-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.insight-list li {
  padding: 10px 0;
  border-bottom: 1px solid var(--border-color);
  position: relative;
  padding-left: 24px;
  color: var(--card-text-color);
}

.insight-list strong {
  color: var(--card-text-color);
}

.insight-list li:before {
  content: "✓";
  color: var(--success-color);
  font-weight: bold;
  position: absolute;
  left: 0;
}

.insight-list li:last-child {
  border-bottom: none;
}

/* Analysis Section Styles */
.analysis-section {
  margin-bottom: 80px;
}

.analysis-content {
  background: var(--card-bg);
  padding: 40px;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
  border: 1px solid var(--border-color);
}

.analysis-process {
  margin-top: 40px;
}

.process-step {
  display: flex;
  align-items: flex-start;
  gap: 30px;
  margin-bottom: 48px;
  padding-bottom: 40px;
  border-bottom: 1px solid var(--border-color);
}

.process-step:last-child {
  border-bottom: none;
  margin-bottom: 0;
  padding-bottom: 0;
}

.step-number {
  background: var(--primary-color);
  color: white;
  width: 60px;
  height: 60px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: bold;
  font-size: 1.2rem;
  flex-shrink: 0;
}

.step-content {
  flex: 1;
}

.step-content h4 {
  margin-bottom: 16px;
  color: var(--primary-color);
  font-size: 1.2rem;
  font-weight: 600;
}

.step-content p {
  color: var(--text-light);
  margin-bottom: 16px;
  line-height: 1.6;
}

/* Tables */
.data-table {
  width: 100%;
  border-collapse: collapse;
  margin: 20px 0;
  background: white;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
}

.data-table th {
  background: var(--primary-color);
  color: white;
  padding: 16px;
  text-align: left;
  font-weight: 600;
  font-size: 0.95rem;
}

.data-table td {
  padding: 16px;
  border-bottom: 1px solid var(--border-color);
  color: var(--card-text-color);
}

.data-table td strong {
  color: var(--card-text-color);
}

.data-table tr:last-child td {
  border-bottom: none;
}

.data-table tr:nth-child(even) {
  background: rgba(37, 99, 235, 0.02);
}

/* Insight Section */
.insight-section {
  background: var(--gradient-bg);
  color: white;
  border-radius: 12px;
  padding: 50px 40px;
  text-align: center;
}

.insight-section * {
  color: white !important;
}

.insight-content {
  display: flex;
  align-items: flex-start;
  gap: 30px;
  max-width: 800px;
  margin: 0 auto;
  color: white;
}

.insight-icon {
  font-size: 3rem;
  flex-shrink: 0;
}

.insight-text h3 {
  margin-bottom: 20px;
  font-size: 1.5rem;
  font-weight: 600;
}

.insight-goals {
  display: grid;
  gap: 15px;
  margin-top: 25px;
  text-align: left;
}

.insight-goal {
  background: rgba(255, 255, 255, 0.1);
  padding: 15px 20px;
  border-radius: 12px;
  backdrop-filter: blur(10px);
}

/* Responsive Design */
@media (max-width: 768px) {
  .portfolio-case-study {
    padding: 0 15px;
  }
  
  .tldr-hero {
    padding: 40px 20px 60px;
    margin-bottom: 40px;
  }
  
  .video-container {
    max-width: 100%;
    margin: 0 auto 20px;
  }
  
  .metrics-strip {
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
    padding: 30px 20px;
    margin: -20px 10px 40px;
  }
  
  .insight-content {
    flex-direction: column;
    text-align: center;
  }
  
  .two-column {
    grid-template-columns: 1fr;
    gap: 24px;
  }
  
  .stats-grid {
    grid-template-columns: repeat(2, 1fr);
  }

  .implications-table th,
  .implications-table td {
      padding: 16px 12px;
      font-size: 0.9rem;
  }

  .implications-table {
      font-size: 0.85rem;
  }

  .goal-cell,
  .actions-cell,
  .vision-cell {
      width: auto;
      display: block;
  }

  .implications-table tr {
      display: block;
      margin-bottom: 20px;
      border: 1px solid var(--border-color);
      border-radius: 12px;
      overflow: hidden;
  }

  .implications-table td {
      display: block;
      border-right: none;
      border-bottom: 1px solid var(--border-color);
  }

  .implications-table td:last-child {
      border-bottom: none;
  }

  .goal-cell {
      background: var(--primary-color) !important;
  }

  .goal-cell strong {
      color: white !important;
  }
}

@media (max-width: 480px) {
  .metrics-strip {
    grid-template-columns: 1fr;
  }
  
  .section-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 8px;
  }
}
</style>