---
layout: page
title: PACLIC 2022
description: Presentation done at the 36th Pacific Asia Conference on Language, Information and Computation (PACLIC 36)
img: assets/img/poincare.png
importance: 3
category: work
related_publications: weeraprameshwara2022sinhala
---

The presentation took place at the 36th Pacific Asia Conference on Language, Information, and Computation on October 20, 2022, held in Manila, Philippines. The research aimed to craft an embedding structure tailored for the Facebook Dataset.

The findings highlighted that a fusion of fastText word embedding with a sentencer embedding structure within the Seq2seq model, incorporating GRU and attention layers, emerged as the most effective model. Notably, hyperbolic embeddings fell short compared to fastText and Word2Vec embeddings, attributed to a lack of a proper parser. Additionally, Glove embeddings exhibited reduced performance due to the absence of a well-suited pre-trained Glove model for the Sinhala language.

<div class="content">
  <!-- Embed the PDF -->
  <iframe src="{{ '/assets/pdf/PACLIC_2022.pdf' | relative_url }}" width="100%" height="600px"></iframe>
</div>
