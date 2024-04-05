---
layout: page
title: How to boost gene expression?
description: synthetic biology, transgene, solubility
img: assets/img/journal.pcbi.1009461.g003.png
importance: 4
category: work
related_publications: true
---

Why are some genes highly expressed? Why are some proteins poorly soluble? We sought to understand the key sequence features that control gene expression and protein solubility. We identify that the ‘accessibility’ of the mRNA regions around initiation codons correlates with gene expression {% cite bhandari2021analysis %}. We find that ‘flexible’ proteins tend to be more soluble {% cite bhandari2020solubility %}. We have developed user-friendly web services to harness these features for cost-effective designs of mRNAs and proteins {% cite bhandari2021tisigner %}.

<div class="row">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/journal.pcbi.1009461.g003.png" title="Expression" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/btaa578f3.jpeg" title="Solubility" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Accessibility around start codons are predictive of protein expression in E. coli (left). Highly flexible proteins tend to be more soluble (right). Based on this, we created a new index called Solubility-Weighted Index to predict solubility.
</div>
