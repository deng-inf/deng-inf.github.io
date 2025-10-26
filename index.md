---
---

  <p>
    At <strong>IFIS</strong>, we aim to <strong>XXX</strong>...
  </p>

  <h4>Our research spans:</h4>
  <ul>
    <li><strong>XXX</strong>: XXX</li>
  </ul>

{% include section.html %}

## Highlights

{% capture text %}

We actively publish at the top venues of computer science, including TPAMI, TKDE, TSMC, TFS, etc.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/research.png"
  link="research"
  title="Our Publications"
  text=text
%}

{% capture text %}

We publish in a variety of areas that cross-feed each other, including:
evidence theory, information theory, non-linear dynamic, quantum computing, information fusion, time series analysis, and complex system modeling.

{%
  include button.html
  link="projects"
  text="Browse our research"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/projects.png"
  link="projects"
  title="Our Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We are a fortunate to be in a world-class team composed of individuals from diverse backgrounds, ethnicities with distinct skillsets.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Our Team"
  text=text
%}

{% include section.html %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 col5=col5 col6=col6%}
