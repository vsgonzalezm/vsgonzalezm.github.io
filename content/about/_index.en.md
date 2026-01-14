---
title: "About Me"
date: 2026-01-14
draft: false
---

<style>
/* Foto de perfil - Geométrica con esquinas redondeadas */
.about-container {
    display: flex;
    gap: 2.5rem;
    align-items: flex-start;
    margin-top: 2rem;
}

.profile-photo {
    width: 280px;
    height: 350px;
    object-fit: cover;
    border-radius: 12px;
    border: 4px solid #5CAA92;
    box-shadow: 
        0 8px 20px rgba(92, 170, 146, 0.3),
        0 0 0 8px #f8f9fa;
    transition: all 0.3s ease;
}

.profile-photo:hover {
    transform: translateY(-5px);
    box-shadow: 
        0 12px 30px rgba(92, 170, 146, 0.5),
        0 0 0 8px #f2cc84;
}

. about-text {
    flex:  1;
}

@media (max-width: 768px) {
    .about-container {
        flex-direction:  column;
        align-items: center;
    }
    
    .profile-photo {
        width: 240px;
        height: 300px;
    }
}
</style>

<div class="about-container">
  <img src="/images/foto_mia.jpeg" alt="Valentina González Madariaga" class="profile-photo">
  
  <div class="about-text">
    <h2>About Me</h2>
    <p>I am a PhD candidate in Sociology at Universidad Católica de Chile, specializing in social research methodology and data analysis. My work focuses on understanding complex social phenomena through rigorous use of quantitative, qualitative, and mixed methods.</p>
    <p>My research combines sociological theory with advanced data analysis techniques, aiming to generate knowledge that contributes to understanding social inequalities, urban dynamics, and sociocultural transformations in Latin America.</p>
  </div>
</div>

<h2>Research Interests</h2>
<div class="interest-grid">
  <div class="interest-card">
    <h3>Social Research Methodology</h3>
    <p>Research design, epistemology, and philosophy of social sciences.</p>
  </div>
  <div class="interest-card">
    <h3>Quantitative & Qualitative Analysis</h3>
    <p>Advanced statistical techniques, content analysis, interviews, and focus groups.</p>
  </div>
  <div class="interest-card">
    <h3>Urban Sociology & Inequality</h3>
    <p>Spatial segregation, social mobility, and territorial inequalities.</p>
  </div>
  <div class="interest-card">
    <h3>Social Data Science</h3>
    <p>Application of computational techniques to social phenomena analysis.</p>
  </div>
  <div class="interest-card">
    <h3>Mixed Methods</h3>
    <p>Integration of qualitative and quantitative approaches in social research.</p>
  </div>
  <div class="interest-card">
    <h3>Data Visualization</h3>
    <p>Effective communication of results through interactive graphics and infographics.</p>
  </div>
</div>

<h2>Technical Skills</h2>
<div class="skills-list">
  <span class="skill-tag">Python</span>
  <span class="skill-tag">R</span>
  <span class="skill-tag">SPSS</span>
  <span class="skill-tag">SQL</span>
  <span class="skill-tag">Stata</span>
  <span class="skill-tag">NVivo</span>
  <span class="skill-tag">Atlas.ti</span>
  <span class="skill-tag">GeoPandas</span>
  <span class="skill-tag">Tableau</span>
  <span class="skill-tag">Power BI</span>
  <span class="skill-tag">R Shiny</span>
  <span class="skill-tag">Git</span>
</div>

<h2>Education</h2>
<div class="education-item">
  <h3>PhD in Sociology (c)</h3>
  <p class="institution">Universidad Católica de Chile</p>
  <p class="year">In Progress</p>
  <p>Thesis: [Space to complete thesis title]</p>
</div>

<div class="education-item">
  <h3>Master's in [Field of Study]</h3>
  <p class="institution">[University]</p>
  <p class="year">[Year]</p>
  <p>[Brief description or specialization]</p>
</div>

<div class="education-item">
  <h3>Sociology</h3>
  <p class="institution">[University]</p>
  <p class="year">[Year]</p>
  <p>[Undergraduate degree in Sociology or relevant focus]</p>
</div>
