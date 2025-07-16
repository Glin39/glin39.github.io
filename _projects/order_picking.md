---
layout: page
title: Order Picking
description: Exploring how head-worn displays can support alternating attention tasks like warehouse order picking.
img: assets/img/order_picking.gif
importance: 3
category: research
related_publications: lin2021towards, lin2021comparing
---

<div class="case-study">

  <!-- Hero Section -->
  <section class="hero-section">
    <div class="hero-content">
      <h2>The Problem</h2>
      <p>How might we use head-worn displays (HWDs) to support warehouse workers in alternating attention tasks like order picking, where they need to switch between digital information and real-world physical interaction?</p>
    </div>
    <div class="hero-image">
      <img src="{{ '/assets/img/order_picking.gif' | relative_url }}" alt="Order Picking with Head-Worn Displays" class="hero-image">
    </div>
  </section>

  <!-- Context Section -->
  <section class="context-section">
    <div class="row">
      <div class="col-md-8">
        <h3>Context & Background</h3>
        <p>Order picking is the task of retrieving items from specific locations in a warehouse to fulfill orders. With over 750,000 warehouses globally supporting trillions of dollars in commerce, small gains in picking efficiency can yield large operational benefits. Order picking also presents a valuable testbed for evaluating HWD usability in alternating attention tasks, where workers must shift focus between digital guidance and physical object interaction.</p>
      </div>
      <div class="col-md-4">
        <div class="project-details">
          <h4>Project Details</h4>
          <ul class="project-info">
            <li><strong>Timeline:</strong>2021 </li>
            <li><strong>Role:</strong> Lead researcher </li>
            <li><strong>Methods:</strong> Comparative user studies, HWD prototyping, quantitative evaluations</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Process Overview -->
  <section class="process-section">
    <h3>Research Process</h3>
    <div class="process-timeline">
      <div class="process-step">
        <div class="step-number">01</div>
        <div class="step-content">
          <h4>Display Position Study</h4>
          <p>Using the Magic Leap One, we evaluated four interface positions in the visual field—center-center, center-right, bottom-center, and bottom-right—during a sparse picking task that required users to walk between pick shelves. The study aimed to determine which display placement supported the most efficient task performance with minimal cognitive burden.</p>
        </div>
      </div>
      <div class="process-step">
        <div class="step-number">02</div>
        <div class="step-content">
          <h4>Device Comparison Study</h4>
          <p>We compared three major HWDs—Magic Leap One, Microsoft Hololens, and Google Glass Explorer Edition—against paper pick lists, the industry standard. Each device offered unique interaction styles and display affordances, providing insight into how hardware design affects worker efficiency and comfort during mobile tasks.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Study 1: Display Placement -->
  <section class="study-section">
    <h3>Study 1: Optimal Display Placement</h3>
    <div class="row">
      <div class="col-md-6">
        <h4>Objective</h4>
        <p>Identify the most effective placement for order picking instructions within the HWD visual field to support minimal interruption and efficient task switching.</p>

        <h4>Findings</h4>
        <p>Participants showed a preference for bottom-center and center-right positions, which balanced visibility and peripheral distraction. Center-center placement, while always visible, often occluded the real-world view. Bottom-right was least preferred due to frequent head and eye movements required.</p>
      </div>
      <div class="col-md-6">
        <img src="{{ '/assets/img/positions.gif' | relative_url }}" alt="Visual Field Positions" class="img-fluid rounded">
      </div>  
    </div>
  </section>

  <!-- Study 2: Device Comparison -->
  <section class="study-section">
    <h3>Study 2: Comparing HWDs with Industry Standards</h3>
    <div class="row">
      <div class="col-md-6">
        <h4>Objective</h4>
        <p>Understand how different HWD designs compare to each other and to traditional methods (paper pick lists) in terms of speed, accuracy, and user comfort.</p>

        <h4>Findings</h4>
        <p>Magic Leap and Hololens, with their spatial tracking and large displays, supported better spatial awareness but were heavier and more physically fatiguing over time. Google Glass, while lightweight and less immersive, enabled quicker transitions between digital and physical contexts. Despite the advantages of digital displays, some participants preferred the familiarity and simplicity of paper lists in high-pressure scenarios.</p>
      </div>
      <div class="col-md-6">
        <img src="{{ '/assets/img/devices.gif' | relative_url }}" alt="Device Comparison" class="img-fluid rounded">
      </div>  
    </div>
  </section>

  <!-- Design Implications -->
  <section class="next-steps-section">
    <h3>Reflections & Implications</h3>
    <p>These studies highlight that HWDs can significantly enhance task performance for mobile, attention-shifting work like order picking—when display placement and hardware ergonomics are carefully considered. The future of warehouse optimization will require a thoughtful match between device type, user experience, and task flow. While no single HWD was ideal across all metrics, each offered unique trade-offs that could be tuned for specific deployment scenarios.</p>
  </section>

  <!-- Impact -->
  <section class="impact-section">
    <h3>Summary</h3>
    <div class="row">
        <p>This work contributes to understanding how head-worn display positioning and device design affect efficiency in industrial tasks like order picking. Our findings offer actionable insights for deploying wearable technology in warehouses, bridging the gap between human-centered design and logistical performance.</p>
    </div>
  </section>

</div>
<style>
.case-study {
  max-width: 1200px;
  margin: 0 auto;
  padding: 0 20px;
}

.case-study section {
  margin-bottom: 60px;
  padding-bottom: 40px;
  border-bottom: 1px solid var(--global-divider-color);
}

.case-study section:last-child {
  border-bottom: none;
}

.hero-section {
  display: flex;
  align-items: flex-start;
  gap: 40px;
  margin-bottom: 80px;
}

.hero-content h2 {
  font-size: 2.5rem;
  color: var(--global-text-color);
  margin-bottom: 20px;
}

.hero-content p {
  font-size: 1.2rem;
  line-height: 1.6;
  color: var(--global-text-color);
  opacity: 0.8;
}

.hero-image img {
  max-width: 600px;
  width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
}
.project-details {
  background: var(--global-card-bg-color);
  padding: 30px;
  border-radius: 8px;
  border-left: 4px solid var(--global-theme-color);
  border: 1px solid var(--global-divider-color);
}

.project-info {
  list-style: none;
  padding: 0;
  margin: 0;
}

.project-info li {
  margin-bottom: 10px;
  padding-bottom: 10px;
  border-bottom: 1px solid var(--global-divider-color);
}

.project-info li:last-child {
  border-bottom: none;
}

.process-timeline {
  display: flex;
  flex-direction: column;
  gap: 40px;
}

.process-step {
  display: flex;
  align-items: flex-start;
  gap: 30px;
}

.step-number {
  background: var(--global-theme-color);
  color: var(--global-bg-color);
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

.step-content h4 {
  margin-bottom: 10px;
  color: var(--global-text-color);
}

.study-section {
  background: var(--global-card-bg-color);
  padding: 40px;
  border-radius: 8px;
  margin-bottom: 40px;
  border: 1px solid var(--global-divider-color);
}

.study-section h4 {
  color: var(--global-text-color);
  margin-bottom: 20px;
}

.solution-features {
  margin-top: 40px;
}

.feature {
  text-align: center;
  padding: 20px;
}

.feature h4 {
  margin: 20px 0 10px 0;
  color: var(--global-text-color);
}

.metrics {
  background: var(--global-card-bg-color);
  padding: 30px;
  border-radius: 8px;
  border-left: 4px solid var(--global-theme-color);
  border: 1px solid var(--global-divider-color);
}

.metrics ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.metrics li {
  margin-bottom: 10px;
  padding-bottom: 10px;
  border-bottom: 1px solid var(--global-divider-color);
}

.metrics li:last-child {
  border-bottom: none;
}

.impact-section {
  background: linear-gradient(135deg, var(--global-theme-color) 0%, rgba(var(--global-theme-color-rgb), 0.8) 100%);
  color: var(--global-bg-color);
  padding: 60px 40px;
  border-radius: 8px;
  margin: 60px 0;
  border: 1px solid var(--global-divider-color);
}

.next-steps-section {
  text-align: center;
  padding: 40px;
  background: var(--global-card-bg-color);
  border-radius: 8px;
  border: 1px solid var(--global-divider-color);
}

@media (max-width: 768px) {
  .hero-section {
    flex-direction: column;
    text-align: center;
  }
  
  .hero-content h2 {
    font-size: 2rem;
  }
  
  .process-step {
    flex-direction: column;
    text-align: center;
  }
  
  .step-number {
    margin: 0 auto;
  }
}
</style>