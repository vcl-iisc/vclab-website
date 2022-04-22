---
title: "Publications"
layout: gridlay
excerpt: VCL Publications
sitemap: false
permalink: /publications/
---

<h1>Publications</h1>

#### Jump to [Book Chapters](#book-chapters), [Journals](#journals), [Conferences](#conferences)

<details open>
<summary>
## Book Chapters
</summary>

---

<!-- <ul> -->

{% for article in site.data.publications %}
{% if article.type=="Book Chapters" %}
<!-- <li> -->
<b><font size='4'>{{ article.paper }}</font></b>
<br><font size='4'>{{ article.author }}</font>
<br><i><font size='4'>{{ article.pub }}</font></i>
<!-- </li> -->
<br><br>

{% endif %}
{% endfor %}

<!-- </ul> -->
</details>

<details open>
<summary>
## Journals
</summary>

---

<!-- <ul> -->
{% for article in site.data.publications %}
{% if article.type=="journal" %}
<!-- <li> -->

<b><font size='4'>{{ article.paper }}</font></b>
<br><font size='4'>{{ article.author }}</font>
<br><i><font size='4'>{{ article.pub }}</font></i>
<!-- </li> -->
<br><br>
{% endif %}
{% endfor %}
<!-- </ul> -->
</details>

<details open>
<summary>
## Conferences
</summary>

---

<!-- <ul> -->
{% for article in site.data.publications %}
{% if article.type=="conference" %}
<!-- <li> -->
<b><font size='4'>{{ article.paper }}</font></b>
<br><font size='4'>{{ article.author }}</font>
<br><i><font size='4'>{{ article.pub }}</font></i>
<!-- </li> -->
<br><br>
{% endif %}
{% endfor %}
<!-- </ul> -->
</details>


<!-- [Google Scholar](https://scholar.google.com/citations?user=q-UUrywAAAAJ&hl=en&citsig=AMD79opm_sa8KYqgVRnFOuKMZr6efInG_Q) -->

<!-- <script src="https://bibbase.org/show?bib=https%3A%2F%2Fgithub.com%2Fvcl-iisc%2Fvclab-website%2Fraw%2Fmaster%2F_pages%2Fbibtex_publications.bib&commas=true&jsonp=1"></script> -->

##### Copyright notice: 

<font size="2"> The contributing authors include the documents contained in these directories/web pages as a means to ensure timely dissemination of scholarly and technical work on a non-commercial basis. Copyright and all rights therein are maintained by the authors or by other copyright holders, notwithstanding that they have offered their works here electronically. It is understood that all persons copying this information will adhere to the terms and constraints invoked by each author’s copyright. These works may not be reposted without the explicit permission of the copyright holder. </font>
