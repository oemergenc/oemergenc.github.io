---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: default
---

<main class="page-content" aria-label="Content">
        <div class="wrapper">

            {%- include about.html -%}

            {%- if site.data.experience.size > 0 -%}
                {%- include experience.html -%}
            {%- endif -%}

            {%- if site.data.education.size > 0 -%}
                {%- include education.html -%}
            {%- endif -%}

            {%- include more.html -%}

        </div>
</main>