{% for file in site.static_files %} {% if file.extname == ".md" %} {{ file.basename }} {% endif %} {% endfor %}
