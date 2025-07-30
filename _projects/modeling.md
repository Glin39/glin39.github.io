---
layout: page
title: Modeling Wearable and Physiological Data Relationships
description: Investigating how consumer wearables can capture hormonal and metabolic variations across the menstrual cycle through continuous multimodal sensing and statistical modeling
img: assets/img/wearable_physiology.png
importance: 1
category: research
related_publications: lin2024wrist, lin2023blood
---

<div class="portfolio-case-study">
  
  <!-- TL;DR Hero Section -->
  <section class="tldr-hero">
    <div class="tldr-badge">TL;DR</div>
    <h1 class="hero-title">Unlocking Physiological Insights from Consumer Wearables</h1>
    <div class="hero-subtitle">
      <p>This research investigated whether consumer wearables can reliably capture complex physiological variations across the menstrual cycle. Through two complementary studies, I demonstrated that continuous sensing from smartwatches and glucose monitors can reveal meaningful hormonal and metabolic patterns, opening new possibilities for accessible health monitoring.</p>
    </div>
    
    <!-- Research Overview -->
    <div class="research-overview">
      <h3>Two-Phase Research Program</h3>
      <div class="phase-grid">
        <div class="phase-card">
          <div class="phase-number">1</div>
          <h4>Temperature-Hormone Relationships</h4>
          <p>Investigating correlations between wrist-worn temperature sensors and daily hormone fluctuations across menstrual cycles</p>
        </div>
        <div class="phase-card">
          <div class="phase-number">2</div>
          <h4>Glucose-Cycle Dynamics</h4>
          <p>Examining blood glucose variations and their relationship to menstrual phases using continuous glucose monitoring</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Research Metrics Strip -->
  <div class="metrics-strip">
    <div class="metric-item">
      <span class="metric-number">49</span>
      <div class="metric-label">Total Participants</div>
    </div>
    <div class="metric-item">
      <span class="metric-number">~180~</span>
      <div class="metric-label">Menstrual Cycles Analyzed</div>
    </div>
    <div class="metric-item">
      <span class="metric-number">3500+</span>
      <div class="metric-label">Days of Wearable Data</div>
    </div>
    <div class="metric-item">
      <span class="metric-number">~50</span>
      <div class="metric-label">Tracked Signals Per Participant</div>
    </div>
  </div>

  <!-- Problem Statement -->
  <section class="problem-section">
    <div class="section-header">
      <h2>The Problem</h2>
    </div>
    <div class="problem-content">
      <div class="problem-statement">
        <h3>Limited accessibility of hormonal and metabolic health monitoring</h3>
        <p>Understanding physiological variations across the menstrual cycle typically requires expensive clinical testing and infrequent sampling. Consumer wearables generate continuous data streams, but their potential for capturing meaningful hormonal and metabolic patterns remains largely unexplored in in-the-wild longitudinal studies.</p>
      </div>
      
      <div class="problem-details">
        <div class="problem-point">
          <h4>Clinical testing is inaccessible and sparse</h4>
          <p>Traditional hormone testing requires clinical visits, is expensive, and provides only snapshot measurements rather than continuous tracking of physiological changes throughout menstrual cycles.</p>
        </div>
        
        <div class="problem-point">
          <h4>Untapped potential of consumer devices</h4>
          <p>Modern wearables continuously collect temperature, glucose, and activity data, but we lack systematic understanding of how these signals relate to underlying hormonal and metabolic processes across reproductive health cycles.</p>
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
        <div class="role-icon">📊</div>
        <h4>Statistical Modeling</h4>
        <p>Designed and implemented hierarchical linear mixed-effects models to analyze hormone-temperature and glucose-cycle relationships</p>
      </div>
      <div class="role-card">
        <div class="role-icon">🔬</div>
        <h4>Longitudinal Study Design</h4>
        <p>Coordinated 3-month data collection protocol with multimodal sensing across 49 participants</p>
      </div>
      <div class="role-card">
        <div class="role-icon">📈</div>
        <h4>Signal Processing</h4>
        <p>Developed preprocessing pipelines for continuous physiological data including filtering, interpolation, and peak detection</p>
      </div>
    </div>
  </section>

  <!-- Research Approach -->
  <section class="approach-section">
    <div class="section-header">
      <h2>Research Approach</h2>
    </div>

    <div class="approach-content">
      <div class="research-goal">
        <h3>Research Goal</h3>
        <p class="goal-text">Can consumer wearables provide clinically meaningful insights into hormonal and metabolic variations across the menstrual cycle through continuous, accessible monitoring?</p>
        <ul class="goal-questions">
          <li>How do wrist-worn temperature measurements correlate with daily hormone fluctuations?</li>
          <li>What are the temporal relationships between hormone peaks and physiological signal changes?</li>
          <li>How does blood glucose vary systematically across menstrual cycle phases?</li>
          <li>What confounding factors must be controlled for in consumer device studies?</li>
        </ul>
      </div>

      <div class="two-column">
        <div class="method-card">
          <div class="method-title">Phase 1: Temperature-Hormone Study</div>
          <p><strong>Devices:</strong> Dexcom G6 CGM,, Fitbit Sense (WST), Mira Plus (LH, E3G hormones)</p>
          <p><strong>Duration:</strong> 3 months continuous collection per participant</p>
          <p><strong>Analysis:</strong> Linear mixed-effects models with random slopes/intercepts, quadratic terms, hormone interactions</p>
          <p><strong>Outcome:</strong> 45 participants, 123 analyzable cycles</p>
        </div>
        <div class="method-card">
          <div class="method-title">Phase 2: Glucose-Cycle Study</div>
          <p><strong>Devices:</strong> Dexcom G6 CGM, Fitbit Sense, Mira Plus</p>
          <p><strong>Duration:</strong> 3 months with daily self-report diaries</p>
          <p><strong>Analysis:</strong> Univariate and multivariate models controlling for step count, food cravings, fatigue, sleep</p>
          <p><strong>Outcome:</strong> 49 participants, 149 analyzable cycles</p>
        </div>
      </div>

      <div class="stats-grid">
        <div class="stat-card">
          <span class="stat-number">98.3%</span>
          <div class="stat-label">Fitbit Data Completeness</div>
        </div>
        <div class="stat-card">
          <span class="stat-number">86.8%</span>
          <div class="stat-label">CGM Data Completeness</div>
        </div>
        <div class="stat-card">
          <span class="stat-number">90.3%</span>
          <div class="stat-label">Self-Report Completeness</div>
        </div>
      </div>

      <div class="design-decision">
        <div class="design-decision-label">
          <strong>⚠️ Technical Decision</strong>
        </div>
        <p>Used validated consumer devices (Fitbit Sense, Dexcom G6, Mira Plus) rather than clinical-grade equipment to evaluate real-world accessibility. All devices, in prior literature, showed strong correlations with clinical methods: Fitbit PBT ±0.23°C vs. clinical thermometry, Dexcom 98.7% accuracy vs. lab glucose, Mira 99% ovulation prediction accuracy.</p>
      </div>
    </div>
  </section>

  <!-- Technical Analysis Framework -->
  <section class="analysis-section">
    <div class="section-header">
      <h2>Technical Analysis Framework</h2>
    </div>
    
    <div class="analysis-content">
      <div class="analysis-process">
        <div class="process-step">
          <div class="step-number">01</div>
          <div class="step-content">
            <h4>Data Preprocessing & Signal Processing</h4>
            <p>Applied systematic preprocessing with different approaches for temperature vs. glucose data. Temperature signals required noise reduction due to sensor variability, while glucose data needed cycle-aware temporal modeling to capture periodic patterns. </p>
            
            <div class="code-block">
              <strong>Temperature Signal Processing (Phase 1):</strong>
              <ul class="tech-list">
                <li>5th-order Butterworth low-pass filter with 10% cutoff frequency</li>
                <li>Linear interpolation for temporal standardization (1 sample/day)</li>
                <li>Peak detection via "three-over-six rule" (≥0.2°C elevation for ≥3 days)</li>
                <li>Hormone peak identification: Local maxima >1.3× E3G, >2.2× LH baseline ratios</li>
              </ul>
            </div>

            <div class="code-block">
              <strong>Glucose Signal Processing (Phase 2):</strong>
              <ul class="tech-list">
                <li>Daily median calculation from 5-minute CGM readings (288 samples/day)</li>
                <li>LOESS smoothing for trend visualization across normalized cycles</li>
                <li>Restricted cubic spline analysis for periodic pattern detection</li>
                <li>Quality control: ≥18 hours continuous data per day requirement</li>
              </ul>
            </div>
          </div>
        </div>
        
        <div class="process-step">
          <div class="step-number">02</div>
          <div class="step-content">
            <h4>LOESS Smoothing & Temporal Visualization</h4>
            <p>Implemented LOESS (Locally Estimated Scatterplot Smoothing) regression to visualize physiological trends across normalized menstrual cycles. This non-parametric approach revealed biphasic patterns without assuming specific functional forms.</p>
            <p>LOESS-smoothed trends revealing biphasic patterns in temperature (Phase 1) and glucose (Phase 2) across normalized menstrual cycles</p>

            <div class="media-placeholder media-placeholder-large">
              <img src="{{ '/assets/img/loess.jpeg' | relative_url }}" alt="LOESS smoothed trends showing temperature patterns across menstrual cycles">
            </div>
            <div class="media-placeholder media-placeholder-large">
              <img src="{{ '/assets/img/loess_g.png' | relative_url }}" alt="LOESS smoothed trends showing glucose patterns across menstrual cycles">
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">03</div>
          <div class="step-content">
            <h4>Periodic Spline Analysis & Cycle Modeling</h4>
            <p>To analyze daily glucose variation across the menstrual cycle, a generalized linear model (GLM) was fitted using restricted cubic splines (RCS). Knots were empirically determined from the data using <code>rcspline.eval()</code>, providing five internal knots that flexibly capture non-linear trends in glucose levels across the normalized cycle timeline.</p>

            
            <div class="spline-analysis">
              <strong>Model Specification:</strong>
              <div class="spline-formula">
                median_glucose ~ rcs(cycle_percent_shift, knots = c(...))
              </div>
            </div>

            <p>Custom plotting was applied using the <code>plot_model()</code> function to visualize the spline-predicted relationship between cycle progression (%) and median daily glucose levels (mmol/L). Plot aesthetics were standardized using <code>set_theme()</code> to ensure consistency across figures, with enhanced label visibility and axis clarity.</p>

            <div class="spline-analysis">
              <strong>Visualization:</strong>
              <div class="spline-formula">
                plot_model(model_cs_per, type = "pred", axis.title = c("Progress Through the Menstrual Cycle (%)", "Daily Median Glucose Levels (mmol/L)"))
              </div>
            </div>

            <div class="media-placeholder media-placeholder-large">
              <img src="{{ '/assets/img/glucose_periodicspline.png' | relative_url }}" alt="Restricted cubic spline fit showing glucose variation across normalized cycle progression">
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">04</div>
          <div class="step-content">
            <h4>Hierarchical Mixed-Effects Modeling</h4>
            <p>Implemented phase-specific linear mixed-effects models with different structures for temperature vs. glucose analyses. Temperature models focused on hormone-physiology relationships, while glucose models emphasized phase-based comparisons. All results of models were reported according to β-coefficients, 95% CI, and the significance of each relationship within models, considering a statistical significance threshold of p<0.05. I applied Holm-Bonferroni adjustments to correct for multiple comparisons. </p>
            
            <div class="model-specification">
              <strong>Example Temperature Model Structure (Phase 1):</strong>
              <div class="model-formula">
                WST ~ E3G + LH + E3G² + LH² + E3G×LH + confounds + (1+cycle|participant_id)
              </div>
              <ul class="tech-list">
                <li>Hormone predictors centered by individual participant means</li>
                <li>Quadratic terms to capture non-linear relationships</li>
                <li>Interaction terms between estrogen and luteinizing hormone</li>
                <li>Random slopes for cycle effects within participants</li>
              </ul>
            </div>

            <div class="model-specification">
              <strong>Example Glucose Model Structure (Phase 2):</strong>
              <div class="model-formula">
                glucose ~ phase + E3G + confounds + (1|participant_id)
              </div>
              <ul class="tech-list">
                <li>Phase as categorical predictor (late-follicular reference)</li>
                <li>Linear hormone effects (E3G as continuous predictor)</li>
                <li>Systematic confound testing and multivariate adjustment</li>
                <li>Random intercepts only (no cycle-level random effects)</li>
              </ul>
            </div>
          </div>
        </div>

        <div class="process-step">
          <div class="step-number">05</div>
          <div class="step-content">
            <h4>Confound Control & Multivariate Analysis</h4>
            <p>Systematically tested potential confounders including demographics, physical activity, stress, sleep quality, and food cravings. Built multivariate models to isolate hormone-physiology relationships from lifestyle factors. Also built models stratified by phases.</p>
            <div class="confound-analysis">
              <strong>Confounding Variables Tested:</strong>
              <div class="confound-grid">
                <div class="confound-category">
                  <h5>Physiological</h5>
                  <ul>
                    <li>Daily step count</li>
                    <li>Sleep duration/quality</li>
                    <li>Heart rate variability</li>
                  </ul>
                </div>
                <div class="confound-category">
                  <h5>Behavioral</h5>
                  <ul>
                    <li>Self-reported physical activity</li>
                    <li>Food cravings (6-point scale)</li>
                    <li>Stress levels</li>
                  </ul>
                </div>
                <div class="confound-category">
                  <h5>Demographic</h5>
                  <ul>
                    <li>Age, BMI, height, weight</li>
                    <li>Cycle length variability</li>
                    <li>Previous contraceptive use</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <div class="process-step">
          <div class="step-number">06</div>
          <div class="step-content">
            <h4>Temporal Alignment Analysis</h4>
            <p>Built peak detection algorithms to identify hormone surges and corresponding physiological responses. Calculated temporal offsets between hormone peaks and temperature changes.</p>
            <div class="media-placeholder media-placeholder-large">
              <img src="{{ '/assets/img/boxplottemp.jpeg' | relative_url }}" alt="Temporal alignment between hormone peaks and physiological signals">
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
        <div class="insight-title">Consumer wearables capture clinically meaningful hormone-temperature relationships</div>
        <div class="insight-content">
          <p>Wrist-worn temperature sensors successfully detected biphasic patterns correlating with hormonal fluctuations:</p>
          <ul class="insight-list">
            <li><strong>Linear LH-temperature relationship:</strong> β = -0.002°C per mIU/mL (p < 0.001, CI: [-0.004, -0.0009])</li>
            <li><strong>Phase-specific E3G effects:</strong> Higher estrogen → lower WST during ovulation (quadratic term significant)</li>
            <li><strong>Temporal alignment:</strong> WST nadirs occurred 2.3±4.5 days before E3G peaks, WST peaks 8.2±4.2 days after</li>
            <li><strong>Robust to confounds:</strong> Relationships persisted after controlling for glucose, activity, stress, and sleep quality</li>
          </ul>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">2</div>
        <div class="insight-title">Glucose exhibits systematic biphasic variation across menstrual cycles</div>
        <div class="insight-content">
          <p>Continuous glucose monitoring revealed consistent metabolic patterns synchronized with reproductive cycles:</p>
          <ul class="insight-list">
            <li><strong>Phase-specific elevation:</strong> Luteal phase glucose 0.16 mmol/L higher than late-follicular (p < 0.001)</li>
            <li><strong>Ovulation increase:</strong> Significant 0.08 mmol/L elevation during fertile window (p < 0.05)</li>
            <li><strong>Estrogen correlation:</strong> Higher E3G levels → lower glucose (β = -0.0003, p < 0.01)</li>
            <li><strong>Behavioral interactions:</strong> Food cravings amplified glucose elevation during luteal phase</li>
          </ul>
        </div>
      </div>

      <div class="insight-card">
        <div class="insight-number">3</div>
        <div class="insight-title">Individual variability requires personalized modeling approaches</div>
        <div class="insight-content">
          <p>Hierarchical modeling revealed substantial between-person differences requiring individualized baselines:</p>
          <ul class="insight-list">
            <li><strong>Timing variability:</strong> Hormone-temperature alignments varied ±4.5 days between individuals</li>
            <li><strong>Cycle length effects:</strong> Relationships scaled with individual cycle duration (28.0±8.7 days)</li>
            <li><strong>Random effects significance:</strong> Individual intercepts and slopes essential for model validity</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Technical Results -->
  <section class="results-section">
    <div class="section-header">
      <h2>Quantitative Results</h2>
    </div>
    
    <div class="results-table-container">
      <table class="results-table">
        <thead>
          <tr>
            <th>Analysis</th>
            <th>Significant Relationships</th>
            <th>Statistical Significance</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="analysis-cell">
              <strong>Phase 1: WST-Hormone Models</strong>
            </td>
            <td class="relationships-cell">
              <ul class="result-list">
                <li>Linear LH → WST (full cycle)</li>
                <li>Quadratic LH → WST (full cycle, luteal)</li>
                <li>Quadratic E3G → WST (ovulation)</li>
                <li>E3G × LH interaction (full cycle)</li>
              </ul>
            </td>
            <td class="significance-cell">
              <ul class="result-list">
                <li>p < 0.001</li>
                <li>p < 0.01</li>
                <li>p < 0.05</li>
                <li>p < 0.001</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td class="analysis-cell">
              <strong>Phase 2: Glucose-Cycle Models</strong>
            </td>
            <td class="relationships-cell">
              <ul class="result-list">
                <li>Ovulation phase elevation</li>
                <li>Luteal phase elevation</li>
                <li>Estrogen correlation</li>
                <li>Step count (protective)</li>
              </ul>
            </td>
            <td class="significance-cell">
              <ul class="result-list">
                <li>p < 0.05</li>
                <li>p < 0.001</li>
                <li>p < 0.01</li>
                <li>p < 0.001</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td class="analysis-cell">
              <strong>Confound Control</strong>
            </td>
            <td class="relationships-cell">
              <ul class="result-list">
                <li>Sleep issues → higher WST</li>
                <li>High activity → lower WST</li>
                <li>Food cravings → higher glucose</li>
                <li>Demographics: non-significant</li>
              </ul>
            </td>
            <td class="significance-cell">
              <ul class="result-list">
                <li>p < 0.05</li>
                <li>p < 0.05</li>
                <li>p < 0.001</li>
                <li>p > 0.05</li>
              </ul>
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
        <h3>Research Impact</h3>
        <p>This work demonstrates that consumer wearables can capture clinically meaningful physiological variations. The hierarchical modeling approach and longitudinal design provide a template for evaluating other consumer health technologies in reproductive health contexts.</p>
        <div class="insight-goals">
          <div class="insight-goal">
            <strong>Technical contribution:</strong> Longitudinal analysis of consumer wearable accuracy for hormone and metabolic tracking
          </div>
          <div class="insight-goal">
            <strong>Clinical impact:</strong> Evidence base for accessible reproductive and metabolic health monitoring
          </div>
          <div class="insight-goal">
            <strong>Methodological framework:</strong> Statistical approaches for consumer device validation in health applications
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

/* Research Overview Styling */
.research-overview {
  margin-top: 40px;
  padding-top: 40px;
  border-top: 2px solid rgba(255, 255, 255, 0.2);
}

.research-overview h3 {
  font-size: 1.5rem;
  margin-bottom: 25px;
  font-weight: 500;
  opacity: 0.95;
  color: var(--hero-text-color);
  text-align: center;
}

.phase-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 25px;
}

.phase-card {
  background: rgba(255, 255, 255, 0.1);
  padding: 25px;
  border-radius: 12px;
  backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  text-align: center;
}

.phase-number {
  background: rgba(255, 255, 255, 0.2);
  color: var(--hero-text-color);
  width: 40px;
  height: 40px;
  border-radius: 30%;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 1rem;
  margin-bottom: 15px;
}

.phase-card h4 {
  color: var(--hero-text-color);
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 10px;
}

.phase-card p {
  color: var(--hero-text-color);
  font-size: 0.95rem;
  opacity: 0.9;
  margin: 0;
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

/* Technical Elements */
.code-block, .model-specification, .confound-analysis {
  background: var(--background-light);
  padding: 20px;
  border-radius: 8px;
  margin: 16px 0;
  border-left: 3px solid var(--primary-color);
}

.code-block strong, .model-specification strong, .confound-analysis strong {
  color: var(--primary-color);
  display: block;
  margin-bottom: 12px;
  font-size: 1.05rem;
}

.model-formula {
  background: white;
  padding: 12px 16px;
  border-radius: 6px;
  font-family: 'Monaco', 'Consolas', monospace;
  font-size: 0.9rem;
  color: var(--primary-dark);
  margin: 8px 0;
  border: 1px solid var(--border-color);
}

.tech-list {
  list-style: none;
  padding: 0;
  margin: 8px 0 0 0;
}

.tech-list li {
  padding: 4px 0;
  position: relative;
  padding-left: 16px;
  color: var(--card-text-color);
  font-size: 0.95rem;
}

.tech-list li:before {
  content: "•";
  color: var(--primary-color);
  font-weight: bold;
  position: absolute;
  left: 0;
}

.confound-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 20px;
  margin-top: 12px;
}

.confound-category h5 {
  color: var(--primary-color);
  font-size: 1rem;
  margin-bottom: 8px;
  font-weight: 600;
}

.confound-category ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.confound-category li {
  padding: 2px 0;
  font-size: 0.9rem;
  color: var(--card-text-color);
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

/* Results Table */
.results-table-container {
  background: var(--card-bg);
  border-radius: 16px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
  overflow: hidden;
  border: 1px solid var(--border-color);
  margin: 20px 0;
}

.results-table {
  width: 100%;
  border-collapse: collapse;
}

.results-table th {
  background: var(--primary-color);
  color: white;
  padding: 20px 16px;
  text-align: left;
  font-weight: 600;
  font-size: 1rem;
}

.results-table td {
  padding: 20px 16px;
  border-bottom: 1px solid var(--border-color);
  vertical-align: top;
}

.results-table tr:last-child td {
  border-bottom: none;
}

.results-table tr:nth-child(even) {
  background: rgba(37, 99, 235, 0.02);
}

.analysis-cell {
  width: 25%;
  border-right: 1px solid var(--border-color);
}

.analysis-cell strong {
  color: var(--primary-color);
  font-size: 1.05rem;
}

.relationships-cell {
  width: 30%;
  border-right: 1px solid var(--border-color);
}

.effects-cell {
  width: 30%;
  border-right: 1px solid var(--border-color);
}

.significance-cell {
  width: 15%;
}

.result-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.result-list li {
  padding: 4px 0;
  font-size: 0.9rem;
  color: var(--card-text-color);
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
  background: var(--primary-color);
  color: white;
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

/* Limitations Section */
.limitations-content {
  display: grid;
  gap: 30px;
  margin-top: 20px;
}

.limitation-category {
  background: var(--card-bg);
  padding: 28px;
  border-radius: 12px;
  border: 1px solid var(--border-color);
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.04);
}

.limitation-category h4 {
  color: var(--primary-color);
  font-size: 1.2rem;
  font-weight: 600;
  margin-bottom: 16px;
}

.limitation-list {
  list-style: none;
  padding: 0;
  margin: 0;
}

.limitation-list li {
  padding: 8px 0;
  border-bottom: 1px solid var(--border-color);
  color: var(--card-text-color);
}

.limitation-list li:last-child {
  border-bottom: none;
}

.limitation-list strong {
  color: var(--primary-color);
  font-weight: 600;
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
  
  .phase-grid {
    grid-template-columns: 1fr;
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

  .confound-grid {
    grid-template-columns: 1fr;
  }

  .results-table th,
  .results-table td {
      padding: 16px 12px;
      font-size: 0.9rem;
  }

  .results-table tr {
      display: block;
      margin-bottom: 20px;
      border: 1px solid var(--border-color);
      border-radius: 12px;
      overflow: hidden;
  }

  .results-table td {
      display: block;
      border-right: none;
      border-bottom: 1px solid var(--border-color);
  }

  .results-table td:last-child {
      border-bottom: none;
  }

  .analysis-cell {
      background: var(--primary-color) !important;
  }

  .analysis-cell strong {
      color: white !important;
  }

  .implications-table th,
  .implications-table td {
      padding: 16px 12px;
      font-size: 0.9rem;
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
  
  .process-step {
    flex-direction: column;
    gap: 20px;
  }
  
  .step-number {
    width: 50px;
    height: 50px;
    align-self: center;
  }
}
</style>