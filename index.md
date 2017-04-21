---
# ◢ is &#9698;
title: "◢ Incline: web and app development, process automation and optimization"
# default description from _config.yml
headline: Incline to bring profits.
#subheadline: ''
class: narrow
featured_customers:
- atari.png
- discovery_channel.jpg
- IBM_Watson.png
- loreal_paris.jpg
- kohls.png
- ticketmaster.svg
---
# ◢ Incline

Incline is a business consulting and software engineering firm established in 2005.

We perform research and development to help businesses launch new products and features, grow sales and revenues, and increase profit margins. 

<div class="row services">
  <div class="col-sm">
    <h3> 📈 Business Optimization</h3>
    <p>We dig into your business and identify key areas where you can increase sales, reduce churn, improve performance, and grow your profit margins. Then we make it happen.</p>
  </div>
  <div class="col-sm">
    <h3> 📱 Websites and Apps</h3>
    <p>Our team builds beautiful, compelling experiences across web, mobile, and desktop. We can create new apps from scratch or take over maintenance of existing ones.</p>
  </div>
</div>


Work with Incline, and you'll be in  <a href="customers.html">good company</a>:

<ul class="logos">
{% for logo in page.featured_customers %}
   <li><img src="assets/images/logos/{{ logo }}" alt="{{ logo | replace: "_", " " |  capitalize }}" /></li>
{% endfor %}
</ul>




### 🖥️ Technologies

We can work with whatever you throw at us, but some of our favorites are Node.js, React, Ruby on Rails, Arduino, Python, Rust, and Swift. 

Incline is very supportive of Open Source - for example, if you run anything on Node.js, you're already running some our code. You're welcome  ;)


## ✉️ Interested in learning more?

Get in touch! [hello@incline.systems](mailto:hello@incline.systems)
