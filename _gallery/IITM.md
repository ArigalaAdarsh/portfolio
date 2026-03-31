---
 
show: true
width: 12
height: 330px
date: 2026-03-26

images:
  - src:  /assets/images/labs/IITM/IITM1.jpeg
  - src:  /assets/images/labs/IITM/IITM2.jpeg 
---

<div class="container my-4">
  <h2 class="text-center mb-4"> SPRING Lab,IIT Madras</h2>

  <div class="row">
    {% for img in page.images %}
    <div class="col-md-6 mb-3">
      <div class="card shadow-sm rounded">
        <img src="{{ img.src | relative_url }}" class="card-img-top" style="height: {{ page.height }}; object-fit: cover;" alt="{{ img.title }}">
        <div class="card-body p-2 text-center">
          <h6 class="mb-0">{{ img.title }}</h6>
        </div>
      </div>
    </div>
    {% endfor %}
  </div>
</div>