---
layout: homepage
---

<section id="about">
  <div class="container">
    <h2 class="section-title">About</h2>
    <div class="about-prose reveal">
      <p>
        I am a postdoctoral researcher in the eXplainable AI (XAI) group at the
        <a href="{{ site.affiliation_link }}" target="_blank" rel="noopener">Fraunhofer Heinrich-Hertz Institute</a>
        in Berlin, led by Dr. Sebastian Lapuschkin and Prof. Wojciech Samek. My research focuses on integrating
        explainability methods into the AI development life cycle to detect and mitigate spurious model behavior,
        with the goal of building reliable and trustworthy AI systems for safety-critical applications.
      </p>
      <p>
        I completed my PhD (<em>Dr. rer. nat., summa cum laude</em>) at TU Berlin, with a dissertation on
        interpretability-driven model debugging within the <em>Reveal2Revise</em> life cycle. Prior to joining
        Fraunhofer, I worked as an Applied Machine Learning Scientist at Amazon in Edinburgh (2019–2021) and as a
        Research Associate at SAP AI Research in Berlin (2017–2019).
      </p>
      <p>If you are interested in collaborating or have questions, feel free to reach out!</p>
    </div>
  </div>
</section>

<section id="research" class="section-alt">
  <div class="container">
    <h2 class="section-title">Research interests</h2>
    <div class="research-list reveal">
      <div class="research-item">
        <i class="fas fa-sync-alt"></i>
        <h3>XAI Life Cycle</h3>
        <p>Integrating explainability methods into the AI development cycle for systematic model validation, debugging, and improvement.</p>
      </div>
      <div class="research-item">
        <i class="fas fa-search"></i>
        <h3>Shortcut Detection &amp; Annotation</h3>
        <p>Identifying spurious model behavior and automating bias annotation using interpretability tools.</p>
      </div>
      <div class="research-item">
        <i class="fas fa-wrench"></i>
        <h3>Model Correction</h3>
        <p>Annotation-efficient unlearning of model shortcuts and spurious correlations in deep neural networks.</p>
      </div>
      <div class="research-item">
        <i class="fas fa-project-diagram"></i>
        <h3>Concept-based Explainability</h3>
        <p>Precise modeling of human-interpretable concepts in neural network latent spaces.</p>
      </div>
      <div class="research-item">
        <i class="fas fa-heartbeat"></i>
        <h3>Medical AI Safety</h3>
        <p>Applying XAI to build reliable and trustworthy AI for safety-critical medical applications.</p>
      </div>
    </div>
  </div>
</section>

{% include_relative _includes/publications.md %}

<section id="contact" class="section-alt">
  <div class="container">
    <h2 class="section-title">Contact</h2>
    <div class="contact-prose reveal">
      <p>I'm always open to research collaborations, discussions on explainable and trustworthy AI, or questions about my work.</p>
      <a class="contact-email" href="mailto:frederikpahde@gmail.com"><i class="fas fa-envelope"></i> frederikpahde@gmail.com</a>
      <div class="social-row">
        {% if site.google_scholar %}<a href="{{ site.google_scholar }}" target="_blank" rel="noopener" aria-label="Google Scholar" title="Google Scholar"><i class="ai ai-google-scholar" aria-hidden="true"></i></a>{% endif %}
        {% if site.github_link %}<a href="{{ site.github_link }}" target="_blank" rel="noopener" aria-label="GitHub" title="GitHub"><i class="fab fa-github" aria-hidden="true"></i></a>{% endif %}
        {% if site.linkedin %}<a href="{{ site.linkedin }}" target="_blank" rel="noopener" aria-label="LinkedIn" title="LinkedIn"><i class="fab fa-linkedin-in" aria-hidden="true"></i></a>{% endif %}
        {% if site.cv_link %}<a href="{{ site.cv_link }}" target="_blank" rel="noopener" aria-label="Curriculum Vitae (PDF)" title="CV"><i class="ai ai-cv" aria-hidden="true"></i></a>{% endif %}
      </div>
    </div>
  </div>
</section>
