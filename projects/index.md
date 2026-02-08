---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

こちらでプロジェクトのコードおよびデータベースを公開しています。ご不明な点がございましたら、GitHubでコメントを残すか、メールで著者までご連絡ください。We are making the project code and database publicly available here. If you have any questions, please leave a comment on GitHub or contact the author by email.

{% include tags.html tags="code, dataset" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="group == 'more'" %}
