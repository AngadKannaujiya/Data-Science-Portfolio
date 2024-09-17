<div class="profile-container">
  <img src="images/profile.png" alt="Your Profile Picture">
  <h2>{{ site.author }}</h2>
  <p>{{ site.description }}</p>
  <h3>Skills</h3>
  <ul>
    <li>Python</li>
    <li>R</li>
    <li>SQL</li>
  </ul>
  <h3>Social Links</h3>
  <ul>
    {% for social_link in site.social %}
      <li><a href="{{ social_link[1] }}">{{ social_link[0] }}</a></li>
    {% endfor %}
  </ul>
</div>
