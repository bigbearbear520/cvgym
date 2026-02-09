---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

CVGYM は、日本各地の教員・若手研究者・学生が集うコミュニティです。世代を超えたメンタリングと知見共有により、初学者は着実に力を伸ばし、経験者はよりインパクトのある研究・論文へ挑戦できる環境をつくります。 We are a community of professors, early-career researchers, and students working together across Japan. By sharing expertise and mentoring across career stages, we create an environment where newcomers can learn fast and experienced members can push toward high-impact publications.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'professor'" %}
{% include list.html data="members" component="portrait" filter="role == 'senior_student'" %}
{% include list.html data="members" component="portrait" filter="role == 'student'" %}

