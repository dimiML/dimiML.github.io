# "Hello Dimi!"
You made it!
You are a genius!
I admit it!

# Projects
This is where I worked on

# Interests
Basketball

# blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href = "{{post.url}}">{{post.title}}</a>
    </li>
  {% endfor %}    
</ul>
