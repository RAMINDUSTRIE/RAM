{% assign doclist = site.pdf | sort: 'url'  %}


<ul>
   {% for doc in doclist %}
       
            <li><a href="{{ site.baseurl }}{{ doc.url }}">{{ doc.url }}</a></li>
       
  {% endfor %}
</ul>
