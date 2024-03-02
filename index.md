---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
permalink: /
---

<article class="page presentation">
    <header>
        <p>Hi all. I am</p>
        <h1>Valery Raikov</h1>
        <h2>BCSE student</h2>
    </header>

    {% if site.github_username %}
    <p>
        <span class="comment">// you can also see it on my Github page</span>
    </p>
    <p>
        <span class="clr-variable-type">const</span>
        <span class="clr-variable-name">githubLink</span> = 
        <a class="clr-variable-value" href="https://github.com/{{ site.github_username }}" target="_blank">“https://github.com/{{ site.github_username }}”</a>
    </p>
    {% endif %}

</article>