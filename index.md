---
# ◢ is &#9698;
title: "◢ Incline: web and app development, process automation and optimization"
# default description from _config.yml
headline: Incline helps businesses grow
subheadline: Sometimes that involves computers.
featured_customers:
- atari.png
- discovery_channel.jpg
- kohls.png
- IBM_Watson.png
- ticketmaster.svg
- loreal_paris.jpg
---
# ◢ Incline.

Incline is a business consulting and software engineering firm established in 2005.

Our focus is on helping businesses grow profits. Our services center around development, automation, and optimization.

<div class="row">
  <div class="col-sm">
    <h3> 📈 Business Optimization</h3>
    <p>We dig into your business and identify key areas where you can increase sales, reduce churn, improve performance, and grow your profit margins. Then we make it happen.</p>
  </div>
  <div class="col-sm">
    <h3> 📱 Web and App Development</h3>
    <p>Our team builds beautiful, compelling experiences across web, mobile, and desktop. We can create new apps from scratch or take over maintenance of existing ones.</p>
  </div>
</div>


## 🦄 Why Incline?

This isn't our first rodeo. Our team of experts and industry veterans knows the ins and outs of business and technology, and what it takes to make a project successful.  

We have experience working with a wide range of <a href="customers.html">clients</a>, including:

<ul class="logos">
{% for logo in page.featured_customers %}
   <li><img src="assets/images/logos/{{ logo }}" alt="{{ logo | replace: "_", " " |  capitalize }}" /></li>
{% endfor %}
</ul>


Work with Incline, and you'll be in good company. 

### 🖥️ Technologies

We can work with whatever you throw at us, but some of our favorites are Node.js, React, Ruby on Rails, Arduino, Python, Rust, and Swift. 

Incline is very supportive of Open Source - for example, if you run anything on Node.js, you're already running some our code. You're welcome  ;)


## ✉️ Interested in learning more?

Get in touch! [hello@incline.systems](mailto:hello@incline.systems)
