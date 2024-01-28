---
layout: default
---

<div class="furniture-grid">
    {% for product in site.products %}
    <div class="item">
        <a href="{{ product.url }}">
            <img src="/assets/img/{{ product.name | remove: '.markdown'}}/thumbnail.jpg" alt="{{ product.title }}" />
        </a>
    </div>
    {% endfor %}
</div>