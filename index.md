---
layout: home
permalink: /
---

Welcome to my personal academic website. I'm a researcher interested in complex systems, computational neuroscience, and computational biology.

Feel free to explore the [About]({{ "/about" | relative_url }}) page to learn more about me and my work.

---

<div class="social-links-home">
  {%- if site.minima.social_links -%}
  <ul class="social-media-list-home">
    {%- for social in site.minima.social_links -%}
      {%- assign key = social[0] -%}
      {%- assign url = social[1] -%}
      {%- if key == 'github' -%}
        <li>
          <a href="{{ url }}" title="GitHub" class="icon-github">
            <svg class="svg-icon">
              <use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use>
            </svg>
          </a>
        </li>
      {%- elsif key == 'twitter' -%}
        <li>
          <a href="{{ url }}" title="Twitter" class="icon-twitter">
            <svg class="svg-icon">
              <use xlink:href="{{ '/assets/minima-social-icons.svg#twitter' | relative_url }}"></use>
            </svg>
          </a>
        </li>
      {%- elsif key == 'linkedin' -%}
        <li>
          <a href="{{ url }}" title="LinkedIn" class="icon-linkedin">
            <svg class="svg-icon">
              <use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use>
            </svg>
          </a>
        </li>
      {%- elsif key == 'email' -%}
        <li>
          <a href="{{ url }}" title="Email" class="icon-email">
            <svg class="svg-icon">
              <use xlink:href="{{ '/assets/minima-social-icons.svg#email' | relative_url }}"></use>
            </svg>
          </a>
        </li>
      {%- endif -%}
    {%- endfor -%}
  </ul>
  {%- endif -%}
</div>
