---
layout: page
title: Context Aware Cooking Assistant
description: Designing a smart assistant to support continuous context switches in cooking by understanding user progress and environment through multimodal sensing
img: assets/img/cooking.png
importance: 2
category: research
related_publications: lin2023identifying
---

<div class="portfolio-case-study">
  
  <!-- TL;DR Hero Section -->
  <section class="tldr-hero">
    <div class="tldr-badge">TL;DR</div>
    <h1 class="hero-title">Deriving Design Needs for AI Cooking Assistants</h1>
    <div class="hero-subtitle">
      <p>Cooking involves constant context switching between understanding instructions and performing physical tasks in real-time. This research explored how to design multimodal cooking assistants that understand user progress, environmental context, and support natural interaction flows.</p>
    </div>
    
    <!-- Demo Section -->
    <div class="demo-section">
      <h3>Research Demo Video</h3>
      <div class="video-container">
        <iframe
          width="100%"
          height="315"
          src="https://www.youtube.com/embed/H57S8TY0hTA"
          title="Context Aware Cooking Assistant Research Demo"
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
        <h3>Cooking assistance requires understanding context, not just controlling media</h3>
        <p>Following cooking videos requires users to constantly alternate attention between understanding video instructions and performing those steps in their physical environment. Current video navigation tools treat this as a simple media control problem, ignoring the rich contextual information available in the cooking environment.</p>
      </div>
      
      <div class="problem-details">
        <div class="problem-point">
          <h4>Context switching creates cognitive overhead</h4>
          <p>Users must mentally track their progress, map video instructions to their specific setup, and troubleshoot differences between what they see on screen vs. their kitchen reality.</p>
        </div>
        
        <div class="problem-point">
          <h4>How to design effective systems</h4>
          <p>Many existing cooking assistants and research efforts focus on agents that only process video. However, with recent advances in intelligent multimodal agent systems, we can now envision agents that offer contextually relevant assistance. The challenge lies in how to design such systems effectively.</p>
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
        <div class="role-icon">🔬</div>
        <h4>Wizard-of-Oz Study Design</h4>
        <p>Designed and conducted a controlled study simulating AI-powered contextual assistance through human operators</p>
      </div>
      <div class="role-card">
        <div class="role-icon">📊</div>
        <h4>Interaction Analysis</h4>
        <p>Analyzed 30+ hours of cooking sessions to understand query patterns, workflow alignment, and assistant needs</p>
      </div>
      <div class="role-card">
        <div class="role-icon">🎨</div>
        <h4>Design Framework</h4>
        <p>Derived design principles for context-aware assistants that extend beyond the cooking domain</p>
      </div>
    </div>
  </section>

  <!-- Research Approach -->
  <section class="approach-section">
    <div class="section-header">
      <h2>User Study</h2>
    </div>

    <div class="media-placeholder media-placeholder-large">
      <img src="{{ '/assets/img/cooking.png' | relative_url }}" alt="Wizard-of-oz study setup showing researcher and participant perspectives">
      <p>Wizard-of-oz study setup: researcher could see participant's cooking environment while controlling shared video interface</p>
    </div>
    
    <div class="approach-content">
      <div class="research-goal">
        <h3>Research Goal</h3>
        <p class="goal-text">How can we design context-aware assistants that support users as they switch focus between following procedural video instructions and performing cooking tasks in real-time?</p>
        <ul class="goal-questions">
          <li>What types of contextual information enable more effective cooking assistance?</li>
          <li>How do users naturally interact with environment-aware assistants during hands-on tasks?</li>
          <li>What design patterns from cooking assistance can generalize to other procedural domains?</li>
        </ul>
      </div>

      <div class="two-column">
        <div class="method-card">
          <div class="method-title">Study Protocol</div>
          <p><strong>Video conference setup:</strong> Participants joined from home kitchens, researchers controlled shared video screen</p>
          <p><strong>Environmental awareness simulation:</strong> Researchers could see participant's cooking space and context in real-time</p>
          <p><strong>Natural interaction:</strong> Participants encouraged to ask any questions they would want from an ideal cooking assistant</p>
        </div>
        <div class="method-card">
          <div class="method-title">Data Capture</div>
          <p><strong>Multi-stream recording:</strong> User video, audio, all verbal interactions, and environmental sounds</p>
          <p><strong>Recipe selection:</strong> Participants chose unfamiliar but interesting dishes from 5 options, selected own YouTube videos</p>
          <p><strong>Session structure:</strong> 1-hour cooking sessions with pre/post surveys and demographic data</p>
        </div>
      </div>

      <div class="stats-grid">
        <div class="stat-card">
          <span class="stat-number">30</span>
          <div class="stat-label">Participants (average-intermediate cooks)</div>
        </div>
        <div class="stat-card">
          <span class="stat-number">5</span>
          <div class="stat-label">Standardized recipe categories</div>
        </div>
        <div class="stat-card">
          <span class="stat-number">100%</span>
          <div class="stat-label">Home kitchen environments</div>
        </div>
      </div>

      <div class="design-decision">
        <div class="design-decision-label">
          <strong>⚠️ Technical Decision</strong>
        </div>
        <p>Used wizard-of-oz methodology rather than full AI implementation to focus on interaction patterns and user needs without being constrained by current AI limitations. This allowed us to simulate ideal contextual awareness and study user expectations.</p>
      </div>
    </div>
  </section>

  <!-- UX Analysis Framework -->
  <section class="analysis-section">
    <div class="section-header">
      <h2>UX Analysis Framework</h2>
    </div>
    
    <div class="analysis-content">
      <div class="analysis-process">
        <div class="process-step">
          <div class="step-number">01</div>
          <div class="step-content">
            <h4>Open Coding & Thematic Analysis</h4>
            <p>Two researchers independently performed line-by-line open coding on session transcripts and survey responses using established thematic analysis methods. Initial themes included "asking to replay video near end of cooking step" and "interactions requiring multimodal sensing."</p>
          </div>
        </div>
        
        <div class="process-step">
          <div class="step-number">02</div>
          <div class="step-content">
            <h4>Interaction Categorization Framework</h4>
            <p>Systematically grouped all user interactions into distinct categories based on intent, context, and required assistant capabilities. Categories emerged from data rather than predetermined frameworks.</p>
            
            <div class="media-placeholder media-placeholder-small">
              <img src="{{ '/assets/img/ordered_manipulation.png' | relative_url }}" alt="Framework showing categorization of user interactions">
              <p>Interaction categorization framework derived from thematic analysis</p>
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">03</div>
          <div class="step-content">
            <h4>User Persona Development</h4>
            <p>Used human-centered design methods to collaboratively build user personas based on cooking expertise, interaction patterns, and assistant usage preferences. Personas reached through researcher consensus and validation against participant data.</p>
            
            <div class="media-placeholder media-placeholder-small">
              <img src="{{ '/assets/img/personas.png' | relative_url }}" alt="User personas derived from cooking interaction patterns">
              <p>Data-driven user personas showing distinct interaction and assistance needs</p>
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">04</div>
          <div class="step-content">
            <h4>Task Flow & Interaction Mapping</h4>
            <p>Derived typical cooking task flows and mapped where context switches and assistant interactions naturally occurred. Identified predictable patterns across different cooking styles and expertise levels.</p>
            
            <div class="media-placeholder media-placeholder-large">
              <img src="{{ '/assets/img/big_flow.png' | relative_url }}" alt="Example cooking task flow showing context switch points">
              <p>Example cooking task flow highlighting natural context switch points and assistant intervention opportunities</p>
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">05</div>
          <div class="step-content">
            <h4>Persona-Based Interaction Analysis</h4>
            <p>Created comprehensive interaction profiles by mapping each participant's query patterns to derived personas, revealing distinct usage patterns and assistant needs across user types.</p>
            
            <div class="media-placeholder media-placeholder-large">
              <img src="{{ '/assets/img/interaction_persona.png' | relative_url }}" alt="Bar chart showing interaction patterns grouped by persona">
              <p>Bar chart analysis: participant interactions categorized and grouped by derived personas</p>
            </div>
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
        <div class="insight-title">Users form distinct query patterns based on environmental context</div>
        <div class="insight-content">
          <p>Analysis revealed three primary query categories that emerged naturally during context-aware cooking assistance:</p>
          <ul class="insight-list">
            <li><strong>Progress queries:</strong> "Did I add enough salt?" "Is this the right consistency?"</li>
            <li><strong>Adaptation queries:</strong> "I don't have a stand mixer, what should I do?" "My pan is smaller than in the video"</li>
            <li><strong>Timing queries:</strong> "How much longer should this simmer?" "When should I start the next step?"</li>
          </ul>
          <p>These query types rarely occur with traditional video controls, suggesting environmental awareness unlocks new interaction possibilities.</p>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">2</div>
        <div class="insight-title">Workflow alignment varies dramatically between users despite similar goals</div>
        <div class="insight-content">
          <p>While users had different interaction preferences and query patterns, their overall workflow structure showed surprising consistency:</p>
          <ul class="insight-list">
            <li>All users followed similar preparation → execution → validation cycles</li>
            <li>Context switches occurred at predictable points (ingredient prep, technique changes, timing decisions)</li>
            <li>Environmental queries clustered around decision points and skill-adaptation moments</li>
          </ul>
          <p>This suggests context-aware systems can predict when assistance will be needed, even across diverse user preferences.</p>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">3</div>
        <div class="insight-title">Multimodal sensing enables proactive rather than reactive assistance</div>
        <div class="insight-content">
          <p>Environmental awareness allowed the system to anticipate user needs before explicit requests:</p>
          <ul class="insight-list">
            <li>Computer vision detected when ingredients were missing or substituted</li>
            <li>Audio cues indicated technique struggles (e.g., inadequate whisking sounds)</li>
            <li>Sensor data revealed timing issues (oven preheating, pan temperature)</li>
            <li>Combined signals enabled contextually relevant suggestions at optimal moments</li>
          </ul>
          <p>Users reported feeling "understood" by the system rather than simply "controlled," leading to higher task confidence and learning outcomes.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Design Implications -->
  <section class="next-steps-section">
    <div class="section-header">
      <h2>Design Implications & Future Work</h2>
    </div>
    
    <div class="implications-table-container">
      <table class="implications-table">
        <thead>
          <tr>
            <th>Design Goal</th>
            <th>Technical Implementation</th>
            <th>Broader Applications</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="goal-cell">
              <strong>Support task completion flow recognition</strong>
            </td>
            <td class="actions-cell">
              <ul class="action-list">
                <li>Develop computer vision models for cooking state recognition</li>
                <li>Implement temporal reasoning for multi-step procedure tracking</li>
                <li>Create adaptive timing models based on user skill and environmental factors</li>
              </ul>
            </td>
            <td class="vision-cell">
              Procedural assistance systems for manufacturing, healthcare protocols, educational labs, and repair/maintenance tasks.
            </td>
          </tr>
          <tr>
            <td class="goal-cell">
              <strong>Accommodate diverse user queries and characteristics</strong>
            </td>
            <td class="actions-cell">
              <ul class="action-list">
                <li>Build multimodal interaction frameworks (voice, gesture, visual)</li>
                <li>Develop user modeling for skill adaptation and preference learning</li>
                <li>Create context-aware natural language understanding for domain-specific queries</li>
              </ul>
            </td>
            <td class="vision-cell">
              Adaptive AI tutoring systems that accommodate different learning styles, physical abilities, and expertise levels across domains.
            </td>
          </tr>
          <tr>
            <td class="goal-cell">
              <strong>Leverage multimodal sensing of environment</strong>
            </td>
            <td class="actions-cell">
              <ul class="action-list">
                <li>Integrate IoT sensors with computer vision and audio processing</li>
                <li>Develop sensor fusion algorithms for environmental state estimation</li>
                <li>Create privacy-preserving edge computing for real-time analysis</li>
              </ul>
            </td>
            <td class="vision-cell">
              Smart environments that understand human activity and provide contextual assistance in homes, workplaces, and public spaces.
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </section>

  <!-- Key Insight -->
  <section class="insight-section">
    <div class="insight-content">
      <div class="insight-icon">💡</div>
      <div class="insight-text">
        <h3>Reflection</h3>
        <p>This work demonstrates that effective AI assistance requires understanding not just user intent, but environmental context and task progression. The multimodal sensing approach and interaction patterns identified extend beyond cooking to any domain involving procedural guidance in physical environments.</p>
        <div class="insight-goals">
          <div class="insight-goal">
            <strong>Technical contribution:</strong> Multimodal fusion framework for real-time environmental understanding
          </div>
          <div class="insight-goal">
            <strong>Interaction design:</strong> Context-aware query patterns that inform natural language interfaces
          </div>
          <div class="insight-goal">
            <strong>Broader impact:</strong> Design principles for AI assistants in physical, procedural domains
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

/* Design Implications Table */
.implications-table-container {
  background: var(--card-bg);
  border-radius: 16px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
  overflow: hidden;
  border: 1px solid var(--border-color);
}

.implications-table {
  width: 100%;
  border-collapse: collapse;
}

.implications-table th {
  padding: 24px 20px;
  text-align: left;
  font-weight: 600;
  font-size: 1.1rem;
}

.implications-table td {
  padding: 24px 20px;
  border-bottom: 1px solid var(--border-color);
  vertical-align: top;
}

.implications-table tr:last-child td {
  border-bottom: none;
}

.implications-table tr:nth-child(even) {
  background: rgba(37, 99, 235, 0.02);
}

.goal-cell {
  border-right: 1px solid var(--border-color);
  width: 25%;
}

.goal-cell strong {
  color: var(--primary-color);
  font-size: 1.05rem;
  line-height: 1.4;
}

.actions-cell {
  width: 40%;
  border-right: 1px solid var(--border-color);
}

.vision-cell {
  width: 35%;
  font-style: italic;
  color: var(--text-light);
  line-height: 1.5;
}

.action-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.action-list li {
  padding: 6px 0;
  position: relative;
  padding-left: 20px;
  color: var(--text-light);
}

.action-list li:before {
  content: "→";
  color: var(--primary-color);
  font-weight: bold;
  position: absolute;
  left: 0;
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