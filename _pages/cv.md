---
# layout: cv
# permalink: /cv/
title: Curriculum Vitae
nav: true
nav_order: 1
---

<div>

  <header class="post-header">
    <h1 class="post-title">{{ page.title }} {% if page.cv_pdf %}<a href="{{ page.cv_pdf | prepend: 'assets/pdf/' | relative_url}}" target="_blank" rel="noopener noreferrer" class="float-right"><i class="fa-solid fa-file-pdf"></i></a>{% endif %}</h1>
      {% if page.description %}<p class="post-description">{{ page.description }}</p>{% endif %}
  </header>

   <!-- Embed PDF here -->
   <iframe src="assets/pdf/Gihan_Weeraprameshwara_Curriculum_Vitae.pdf" width="100%" height="600px"></iframe>

</div>