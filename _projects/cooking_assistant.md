---
layout: page
title: Context Aware Cooking Assistant
description: Designing a smart assistant to support continuous context switches in cooking by understanding user progress and environment through multimodal sensing
img: assets/img/cooking.png
importance: 2
category: research
related_publications: lin2023identifying
---

<div class="case-study">
  
  <!-- Hero Section -->
  <section class="hero-section">
    <div class="hero-content">
      <h2>The Problem</h2>
      <p>How might we design a context-aware assistant to support users as they switch focus between following procedural video instructions and performing cooking tasks?</p>
    </div>
    <div class="hero-image">
      <img src="{{ '/assets/img/cooking.png' | relative_url }}" alt="Context Aware Cooking Assistant Interface" class="hero-image">
    </div>
  </section>

  <!-- Context Section -->
  <section class="context-section">
    <div class="row">
      <div class="col-md-8">
        <h3>Context & Background</h3>
        <p>Following how-to cooking videos requires users to alternate their attention between understanding video instructions and performing those steps in real time. Supporting this continuous context switching with intelligent assistance has been largely unexplored. Current video navigation tools do not account for users' environment or progress, limiting their effectiveness.</p>
      </div>
      <div class="col-md-4">
        <div class="project-details">
          <h4>Project Details</h4>
          <ul class="project-info">
            <li><strong>Timeline:</strong> 2021 </li>
            <li><strong>Role:</strong> Lead Researcher </li>
            <li><strong>Methods:</strong> User study, wizard-of-oz prototyping, interaction analysis</li>
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
          <h4>User Study</h4>
          <p>Conducted a study with 30 participants performing an hour-long cooking task while interacting with a hands-free wizard-of-oz system aware of their cooking progress and environmental context.</p>
        </div>
      </div>
      <div class="process-step">
        <div class="step-number">02</div>
        <div class="step-content">
          <h4>Interaction Analysis</h4>
          <p>Analyzed session scripts to identify user query differences and workflow alignment similarities, revealing under-studied interaction needs beyond basic video navigation.</p>
        </div>
      </div>
      <div class="process-step">
        <div class="step-number">03</div>
        <div class="step-content">
          <h4>Design Implications</h4>
          <p>Derived design implications for an assistant capable of understanding task completion flow, personal user characteristics, and supporting nonvoice-based queries within and beyond the cooking domain.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Study 1 -->
  <section class="study-section">
    <h3>Study: Multimodal Context Awareness in Cooking</h3>
    <div class="row">
      <div class="col-md-6">
        <h4>Research Goal</h4>
        <p>Explore how a context-aware assistant can support users navigating video instructions and performing cooking tasks through multimodal sensing.</p>
        
        <h4>Key Findings</h4>
        <p>Identified a dichotomy between participant query differences and workflow alignment similarities, highlighted the need for AI beyond simple video navigation, and showed the importance of multimodal environmental sensing to support user queries.</p>
      </div>
      <div class="col-md-6">
        <img src="{{ '/assets/img/cooking_gif.gif' | relative_url }}" alt="Cooking Assistant Study Visualization" class="img-fluid rounded">
      </div>
      <iframe
        width="100%"
        height="400"
        src="https://www.youtube.com/embed/H57S8TY0hTA"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
      </iframe>
    </div>
  </section>

  <!-- Design Implications -->
  <section class="next-steps-section">
    <h3>Design Implications & Next Steps</h3>
    <table>
        <tr>
          <th>Design Goal</th>
          <th>Short-Term Actions</th>
          <th>Long-Term Vision</th>
        </tr>
      <tbody>
        <tr>
          <td>Support task completion flow recognition</td>
          <td>
            - Develop models to track cooking progress in real time<br>
            - Integrate progress awareness into assistant responses
          </td>
          <td>
            A cooking assistant that seamlessly adapts to user progress, providing timely and relevant guidance without disrupting task flow.
          </td>
        </tr>
        <tr>
          <td>Accommodate diverse user queries and characteristics</td>
          <td>
            - Enable handling of nonvoice queries<br>
            - Personalize assistant behavior based on user preferences and needs
          </td>
          <td>
            Adaptive AI that understands individual user traits, accommodates various interaction modes, and offers personalized support during cooking.
          </td>
        </tr>
        <tr>
          <td>Leverage multimodal sensing of environment</td>
          <td>
            - Implement environmental sensors (e.g., kitchen tools, gestures)<br>
            - Contextualize user queries with sensed environmental data
          </td>
          <td>
            A smart assistant that integrates multimodal context to provide accurate and proactive assistance beyond video navigation.
          </td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Impact -->
  <section class="impact-section">
    <h3>Summary</h3>
    <div class="row">
        <p>This research reveals the challenges users face when switching attention between video instructions and performing cooking tasks, emphasizing the need for context-aware assistants that understand both task progress and environmental cues.</p>
        
        <p>The findings motivate future design of smart cooking assistants that support natural interaction flows, accommodate diverse queries, and leverage multimodal sensing to enhance user experience and efficiency.</p>
      </div>
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