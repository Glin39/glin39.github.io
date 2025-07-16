---
layout: page
title: Captioning on Glass
description: Exploring real-time captioning using head-worn displays like Google Glass to support d/Deaf and hard-of-hearing users in both stationary and mobile tasks.
img: assets/img/captioning.gif
importance: 3
category: research
related_publications: tu2020conversational, tu2020towards
---

<div class="case-study">

  <!-- Hero Section -->
  <section class="hero-section">
    <div class="hero-content">
      <h2>The Problem</h2>
      <p>How might we provide real-time captioning in both static and dynamic environments to support people with hearing loss using more natural and accessible interfaces?</p>
    </div>
    <div class="hero-image">
      <img src="{{ '/assets/img/captioning.gif' | relative_url }}" alt="Captioning on Google Glass" class="hero-image">
    </div>
  </section>

  <!-- Context Section -->
  <section class="context-section">
    <div class="row">
      <div class="col-md-8">
        <h3>Context & Background</h3>
        <p>The World Health Organization estimates that by 2050, 1 in every 10 people will have disabling hearing loss. While captioning on smartphones has grown more common, these devices are not always practical—especially in mobile contexts where hands-free use and subtlety are essential. Head-worn displays (HWDs), like Google Glass, offer new opportunities to provide discreet and accessible real-time captioning for d/Deaf and Hard of Hearing (DHH) individuals.</p>
      </div>
      <div class="col-md-4">
        <div class="project-details">
          <h4>Project Details</h4>
          <ul class="project-info">
            <li><strong>Timeline:</strong> 2020 </li>
            <li><strong>Role:</strong> Co-lead Researcher</li>
            <li><strong>Methods:</strong> Iterative prototyping, comparative user studies, quantitative methods</li>
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
          <h4>Prototype Development</h4>
          <p>Built multiple captioning prototypes across both head-worn displays (Google Glass, Vuzix Blade) and smartphones. Focused on latency, readability, and user comfort.</p>
        </div>
      </div>
      <div class="process-step">
        <div class="step-number">02</div>
        <div class="step-content">
          <h4>Stationary Task Study</h4>
          <p>Participants performed a block-assembly task while receiving real-time captions either on a smartphone or a head-worn display. We measurened their engagement, comfort, and comprehension accuracy in each condition.</p>
        </div>
      </div>
      <div class="process-step">
        <div class="step-number">03</div>
        <div class="step-content">
          <h4>Mobile Name Detection Study</h4>
          <p>To address real-world challenges faced by DHH individuals, we tested caption delivery while participants navigated an office space, responding to greetings (e.g., hearing their name). We compared HWDs and smartphones in terms of response time and usability.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Study 1: Stationary Task -->
  <section class="study-section">
    <h3>Study 1: Captioning During a Stationary Task</h3>
    <div class="row">
        <h4>Objective</h4>
        <p>Evaluate user comprehension and experience when receiving captions on different devices while focusing on an assembly task.</p>

        <h4>Findings</h4>
        <p>Participants using HWDs reported reduced head movement, better engagement with their task, and a more natural experience compared to phone users. However, comfort and display readability varied depending on device design and text layout.</p>

      <iframe
        width="100%"
        height="400"
        src="https://www.youtube.com/embed/1ylnGQ7kLJM"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>
  </section>

  <!-- Study 2: Mobile Context -->
  <section class="study-section">
    <h3>Study 2: On-the-Go Name Awareness</h3>
    <div class="row">
        <h4>Objective</h4>
        <p>Support name awareness in mobile environments to prevent missed social cues and communication breakdowns among DHH users.</p>

        <h4>Findings</h4>
        <p>Head-worn display users reacted faster and with more confidence when detecting their names compared to smartphone users, highlighting the benefits of always-in-sight interfaces in dynamic settings.</p>
    </div>
  </section>

  <!-- Design Implications -->
  <section class="next-steps-section">
    <h3>Reflections & Implications</h3>
    <p>This project demonstrated the promise of head-worn displays for enabling accessible, real-time captioning in both stationary and mobile situations. While smartphones remain ubiquitous, HWDs offer hands-free, contextually integrated caption delivery that can improve social and task-related communication for DHH users. Future work may explore how to improve display readability, comfort for extended wear, and integration with modern ASR systems in noisy or outdoor environments.</p>
  </section>

  <!-- Impact -->
  <section class="impact-section">
    <h3>Summary</h3>
    <div class="row">
        <p>Captioning on Glass explores how to deliver timely and accessible information to users with hearing loss using head-worn displays. Through controlled studies, we found that HWDs improve reaction time, reduce visual distraction, and enhance comfort in dynamic environments. This work contributes to the design of assistive technologies that support more inclusive and equitable communication experiences.</p>
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