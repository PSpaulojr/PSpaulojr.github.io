# 👋 Bem-vindo ao meu blog!

Sou engenheiro de dados e estudo para me tornar um engenheiro de machine learning.  
Aqui registro minhas resenhas sobre livros, artigos, papers, além da minha evolução técnica.

## 📝 Últimos Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
