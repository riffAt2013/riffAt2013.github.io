---
layout: default
title: Tags
---

{% for tag in collections.tagList %}

<span>
<a href="/tags/{{ tag }}"><button class="bg-slate-600 hover:bg-gray-100 text-gray-800 font-semibold py-2 px-4 border border-gray-400 rounded shadow mr-6 mb-4 dark:bg-white">
{{ tag }}
</button>
</a>
</span>

{% endfor %}
