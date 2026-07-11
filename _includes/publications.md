<section id="publications">
  <div class="container">
    <div class="pub-head">
      <h2 class="section-title">Selected publications</h2>
      {% if site.google_scholar %}
      <a class="pub-link" href="{{ site.google_scholar }}" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i> View all on Google Scholar</a>
      {% endif %}
    </div>

    <ol class="pub-list">
      {% for link in site.data.publications.main %}
      <li class="pub reveal">
        <div class="pub-thumb" aria-hidden="true">
          {% if link.image %}<img src="{{ link.image }}" alt="" loading="lazy">{% endif %}
        </div>
        <div class="pub-body">
          {% if link.conference_short %}<p class="pub-venue-label">{{ link.conference_short }}</p>{% endif %}
          <h3 class="pub-title"><a href="{{ link.pdf }}" target="_blank" rel="noopener">{{ link.title }}</a></h3>
          <p class="pub-authors">{{ link.authors }}</p>
          <p class="pub-venue">{{ link.conference }}</p>
          <div class="pub-links">
            {% if link.pdf %}<a class="pub-link" href="{{ link.pdf }}" target="_blank" rel="noopener"><i class="fas fa-file-pdf"></i> PDF</a>{% endif %}
            {% if link.code %}<a class="pub-link" href="{{ link.code }}" target="_blank" rel="noopener"><i class="fas fa-code"></i> Code</a>{% endif %}
            {% if link.page %}<a class="pub-link" href="{{ link.page }}" target="_blank" rel="noopener"><i class="fas fa-link"></i> Project Page</a>{% endif %}
            {% if link.bibtex %}<a class="pub-link" href="{{ link.bibtex }}" target="_blank" rel="noopener"><i class="fas fa-quote-right"></i> BibTeX</a>{% endif %}
            {% if link.notes %}<span class="pub-note">{{ link.notes }}</span>{% endif %}
            {% if link.others %}{{ link.others }}{% endif %}
          </div>
        </div>
      </li>
      {% endfor %}
    </ol>
  </div>
</section>
