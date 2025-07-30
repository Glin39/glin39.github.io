---
layout: page
title: Head-Worn Displays for Order Picking
description: Evaluating how display positioning and device characteristics affect efficiency, accuracy, and comfort in warehouse picking tasks through controlled user studies
img: assets/img/order_picking.gif
importance: 3
category: research
related_publications: lin2021towards, lin2021comparing
---

<div class="portfolio-case-study">
  
  <!-- TL;DR Hero Section -->
  <section class="tldr-hero">
    <div class="tldr-badge">TL;DR</div>
    <h1 class="hero-title">Optimizing Head-Worn Displays for Industrial Tasks</h1>
    <div class="hero-subtitle">
      <p>Order picking in warehouses requires constant attention switching between digital instructions and physical tasks. Through two controlled studies, we evaluated how HWD positioning and device characteristics affect worker performance, revealing critical design principles for wearable technology in industrial environments.</p>
    </div>
  </section>

  <!-- Metrics Strip -->
  <div class="metrics-strip">
    <div class="metric-item">
      <div class="metric-number">42</div>
      <div class="metric-label">Participants across 2 studies</div>
    </div>
    <div class="metric-item">
      <div class="metric-number">1,600</div>
      <div class="metric-label">Pick paths completed</div>
    </div>
    <div class="metric-item">
      <div class="metric-number">4</div>
      <div class="metric-label">HWD conditions tested</div>
    </div>
    <div class="metric-item">
      <div class="metric-number">3</div>
      <div class="metric-label">Popular HWDs Compared</div>
    </div>
  </div>

  <!-- Problem Statement -->
  <section class="problem-section">
    <div class="section-header">
      <h2>The Problem</h2>
    </div>
    <div class="problem-content">
      <div class="problem-statement">
        <h3>Industrial wearable deployment requires understanding human factors, not just technical capabilities</h3>
        <p>With over 750,000 warehouses globally supporting trillions in commerce, small efficiency gains in order picking yield massive operational benefits. While head-worn displays promise to enhance worker guidance, their effectiveness depends critically on display positioning, device ergonomics, and interaction design.</p>
      </div>
      
      <div class="problem-details">
        <div class="problem-point">
          <h4>Display positioning affects cognitive load</h4>
          <p>Workers must switch attention between digital instructions and physical environment. Poor display placement can create visual occlusion, neck strain, and increased task completion time.</p>
        </div>
        
        <div class="problem-point">
          <h4>Device characteristics have complex trade-offs</h4>
          <p>Weight, field of view, frame rate, and form factor each impact usability differently. Understanding these trade-offs is crucial for successful deployment in demanding industrial environments.</p>
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
        <div class="role-icon">🏗️</div>
        <h4>Realistic Environment Design</h4>
        <p>Built warehouse-scale picking environment with 7 shelving units, 525 books, and industry-standard spatial layouts for ecological validity</p>
      </div>
      <div class="role-card">
        <div class="role-icon">📐</div>
        <h4>Controlled Experiments</h4>
        <p>Designed counterbalanced studies with TSP-optimized pick paths, standardized interfaces, and comprehensive performance metrics</p>
      </div>
      <div class="role-card">
        <div class="role-icon">📊</div>
        <h4>Statistical Analysis</h4>
        <p>Applied repeated measures ANOVA, post-hoc testing, and preference ranking analysis to derive actionable design principles</p>
      </div>
    </div>
  </section>

  <!-- Research Approach Overview -->
  <section class="approach-section">
    <div class="section-header">
      <h2>Research Approach</h2>
    </div>

    <div class="media-placeholder media-placeholder-large">
      <img src="{{ '/assets/img/order_picking.gif' | relative_url }}" alt="Order picking environment showing participant using Magic Leap with shelving layout">
    </div>
    
    <div class="approach-content">
      <div class="research-goal">
        <h3>Research Goals</h3>
        <p class="goal-text">How do head-worn display positioning and device characteristics affect efficiency, accuracy, and comfort in attention-switching industrial tasks like order picking?</p>
        <ul class="goal-questions">
          <li>Which display positions in the visual field minimize cognitive overhead during mobile tasks?</li>
          <li>How do different HWD form factors (weight, FOV, frame rate) impact worker performance?</li>
          <li>What design principles can optimize HWDs for industrial deployment?</li>
        </ul>
      </div>

      <div class="two-column">
        <div class="method-card">
          <div class="method-title">Environment Setup</div>
          <p><strong>Realistic scale:</strong> 7 shelving units (A-G) with 6.5ft spacing, mimicking warehouse layouts</p>
          <p><strong>Standardized materials:</strong> 525 books with 100 pickable items, consistent visual complexity</p>
          <p><strong>Optimized paths:</strong> Traveling Salesman Problem (TSP) algorithm ensured consistent pick path lengths</p>
        </div>
        <div class="method-card">
          <div class="method-title">Interface Design</div>
          <p><strong>Screen-stabilized UI:</strong> Fixed-position interfaces with consistent proportions across devices</p>
          <p><strong>Dual-view system:</strong> Environment view for navigation, shelf view for precise picking</p>
          <p><strong>Standardized control:</strong> Unified input method across all HWD conditions</p>
        </div>
      </div>

      <div class="design-decision">
        <div class="design-decision-label">
          <strong>⚙️ Technical Decision</strong>
        </div>
        <p>Used Held-Karp algorithm with Dijkstra's optimization to generate TSP tours ensuring all pick paths had equivalent difficulty and travel distance. This controlled for spatial cognitive load, isolating the effect of display variables on performance.</p>
      </div>
    </div>
  </section>

  <!-- Phase 1: Display Positioning -->
  <section class="analysis-section">
    <div class="section-header">
      <h2>Phase 1: Display Positioning Study</h2>
    </div>
    
    <div class="analysis-content">
      <div class="research-goal">
        <h3>Objective</h3>
        <p class="goal-text">Determine optimal interface positioning within Magic Leap One's visual field to minimize task interference and cognitive load during sparse picking tasks.</p>
      </div>

      <div class="analysis-process">
        <div class="process-step">
          <div class="step-number">01</div>
          <div class="step-content">
            <h4>Experimental Design</h4>
            <p><strong>Participants:</strong> 12 volunteers (ages 19-27, 7 female, 8 first-time pickers, all right-eye dominant)</p>
            <p><strong>Conditions:</strong> 4 display positions tested - center-center, center-right, bottom-center, bottom-right</p>
            <p><strong>Protocol:</strong> 20 training + 20 testing pick paths (5 per position), counterbalanced Latin square design</p>
            
            <div class="media-placeholder media-placeholder-small">
              <img src="{{ '/assets/img/ui.png' | relative_url }}" alt="Four display positions tested in visual field">
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">02</div>
          <div class="step-content">
            <h4>Performance Metrics & Analysis</h4>
            <p><strong>Quantitative measures:</strong> Task completion time, picking accuracy, NASA-TLX workload scores</p>
            <p><strong>Statistical analysis:</strong> Repeated measures ANOVA with Greenhouse-Geisser correction, pairwise t-tests with Benjamini-Hochberg adjustment</p>
            
            <div class="media-placeholder media-placeholder-small">
              <img src="{{ '/assets/img/time.png' | relative_url }}" alt="Time per pick path for each position in seconds">
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">03</div>
          <div class="step-content">
            <h4>Key Statistical Findings</h4>
            <p><strong>Accuracy differences:</strong> Center-center significantly outperformed bottom-right (T = -4.190, p = 0.006) and center-right (T = -2.600, p = 0.0375)</p>
            <p><strong>User preferences:</strong> Center-center rated significantly better than bottom-right for speed (Z = -2.067, p = 0.020), comfort (Z = -2.305, p = 0.011), and learnability</p>
            <p><strong>Surprising finding:</strong> No significant differences in task completion time between positions, suggesting stopping behavior masked timing advantages</p>
            
            <div class="media-placeholder media-placeholder-small">
              <img src="{{ '/assets/img/workload.png' | relative_url }}" alt="Difference in average weighted NASA TLX between all positions and Center-Center (mean = 47.5)">
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Phase 2: Device Comparison -->
  <section class="analysis-section">
    <div class="section-header">
      <h2>Phase 2: Multi-Device Comparison Study</h2>
    </div>
    
    <div class="analysis-content">
      <div class="research-goal">
        <h3>Objective</h3>
        <p class="goal-text">Compare three major HWDs against industry-standard paper pick lists to understand how device characteristics impact picking performance and user experience.</p>
      </div>

      <div class="analysis-process">
        <div class="process-step">
          <div class="step-number">01</div>
          <div class="step-content">
            <h4>Device Specifications & Setup</h4>
            
            <div class="data-table">
              <table>
                <thead>
                  <tr>
                    <th>Device</th>
                    <th>Weight</th>
                    <th>FOV</th>
                    <th>Resolution</th>
                    <th>Frame Rate</th>
                    <th>Form Factor</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td><strong>Google Glass</strong></td>
                    <td>42g</td>
                    <td>12°H × 8.3°V</td>
                    <td>640×360</td>
                    <td>120 fps</td>
                    <td>Monocular, lightweight</td>
                  </tr>
                  <tr>
                    <td><strong>Magic Leap One</strong></td>
                    <td>316g + 345g pack</td>
                    <td>~30°H × 20°V</td>
                    <td>1270×800/eye</td>
                    <td>120 fps</td>
                    <td>Binocular, body-worn processor</td>
                  </tr>
                  <tr>
                    <td><strong>HoloLens</strong></td>
                    <td>635g</td>
                    <td>~34°H × 23°V</td>
                    <td>1270×800/eye</td>
                    <td>60 fps</td>
                    <td>Binocular, all-in-one</td>
                  </tr>
                  <tr>
                    <td><strong>Paper</strong></td>
                    <td>~5g</td>
                    <td>Full field</td>
                    <td>N/A</td>
                    <td>N/A</td>
                    <td>Traditional pick list</td>
                  </tr>
                </tbody>
              </table>
            </div>

            <p><strong>Participants:</strong> 12 volunteers (ages 19-23, 11 male, 10 first-time pickers, 9 right-eye dominant)</p>
            <p><strong>Standardized control:</strong> Twiddler3 wireless keyboard for consistent input across all HWD conditions</p>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">02</div>
          <div class="step-content">
            <h4>Performance Analysis</h4>
            <p><strong>Statistical approach:</strong> Repeated measures ANOVA with Greenhouse-Geisser correction, one-tailed t-tests with Benjamini-Hochberg adjustment</p>
            <p><strong>Training protocol:</strong> 20 training paths until performance plateaued (around path 10), then 20 testing paths</p>
            
            <div class="media-placeholder media-placeholder-large">
              <img src="{{ '/assets/img/comGraph2.png' | relative_url }}" alt=" Average time required to complete a pick path. The red line denotes when learning effects plateau (left).
Average Task Times Per Condition During Testing (center). Average Error Rates Per Condition (right).">
            </div>
            <p><strong>Key findings:</strong> Only Google Glass achieved significantly faster task times than paper. Only HoloLens achieved significantly better accuracy. Magic Leap and HoloLens rated significantly less comfortable than paper.</p>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- Key Findings -->
  <section class="findings-section">
    <div class="section-header">
      <h2>Key Findings</h2>
    </div>
    
    <div class="insights-grid">
      <div class="insight-card">
        <div class="insight-number">1</div>
        <div class="insight-title">Display positioning creates measurable trade-offs between accuracy and comfort</div>
        <div class="insight-content">
          <p>Center-center positioning achieved the best accuracy but created visual occlusion issues. Bottom-right had the worst performance due to frequent head movements.</p>
          <ul class="insight-list">
            <li><strong>Statistical significance:</strong> Center-center vs bottom-right accuracy (T = -4.190, p = 0.006)</li>
            <li><strong>User preference:</strong> Center-center rated significantly better for learnability across all non-center positions</li>
            <li><strong>Unexpected finding:</strong> No significant time differences despite comfort variations</li>
          </ul>
          <p>This suggests workers adapt their behavior (stopping to read) to compensate for poor display placement, masking timing differences while maintaining accuracy impacts.</p>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">2</div>
        <div class="insight-title">Device weight and form factor trump display quality for sustained use</div>
        <div class="insight-content">
          <p>Google Glass (42g) achieved the only significant speed improvement over paper, despite having the lowest resolution and smallest FOV among HWDs tested.</p>
          <ul class="insight-list">
            <li><strong>Speed advantage:</strong> Glass significantly faster than paper (p = 0.04), while heavier devices showed no improvement</li>
            <li><strong>Comfort impact:</strong> Magic Leap (661g total) and HoloLens (635g) rated significantly less comfortable than paper</li>
            <li><strong>Movement restriction:</strong> Magic Leap's body-worn processor limited natural movement during picking</li>
            <li><strong>Frame rate effects:</strong> HoloLens' 60fps caused motion-induced dizziness in participants</li>
          </ul>
          <p>Results suggest that for mobile industrial tasks, ergonomic design may be more critical than display fidelity.</p>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">3</div>
        <div class="insight-title">Different HWDs optimize for different performance dimensions</div>
        <div class="insight-content">
          <p>No single device excelled across all metrics, revealing distinct optimization strategies:</p>
          <ul class="insight-list">
            <li><strong>Google Glass:</strong> Optimized for speed and comfort through lightweight design</li>
            <li><strong>HoloLens:</strong> Optimized for accuracy through high FOV and detailed displays (fewer errors than paper)</li>
            <li><strong>Magic Leap:</strong> Balanced approach with moderate performance across all metrics</li>
            <li><strong>Trade-off patterns:</strong> Large FOV improved accuracy but increased eye strain and context switching time</li>
          </ul>
          <p>This suggests deployment decisions should prioritize the most critical performance dimension for specific use cases rather than seeking general-purpose solutions.</p>
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
        <p>This research demonstrates that successful HWD deployment in industrial settings requires understanding complex interactions between human factors, device characteristics, and task demands. The findings challenge assumptions about display quality and reveal that ergonomic design is required for sustained use.</p>
        <div class="insight-goals">
          <div class="insight-goal">
            <strong>Methodological contribution:</strong> Systematic framework for evaluating HWDs in realistic industrial contexts
          </div>
          <div class="insight-goal">
            <strong>Design insights:</strong> Evidence-based principles for display positioning and device selection
          </div>
          <div class="insight-goal">
            <strong>Broader impact:</strong> Human factors considerations for next-generation wearable technology deployment
          </div>
        </div>
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

  .process-step {
    flex-direction: column;
    align-items: center;
    text-align: center;
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