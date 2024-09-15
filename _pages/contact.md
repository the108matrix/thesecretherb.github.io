---
layout: page
title: About Us
permalink: /contact
comments: false
---

Welcome to **The Secret Herb**, your go-to journal for uncovering the best-kept secrets of Indian Ayurvedic herbs, Siddha medicine, and nature’s powerful remedies. We merge ancient wisdom with modern science to reveal how these natural solutions can enhance your health, beauty, and vitality.

Whether you’re looking to upgrade your hair and skin care routine, recover post-surgery, or cultivate a vibrant urban garden of happy herbs, we’ve got you covered. From earthbound roots and flavorful condiments to refreshing teas and innovative sauce recipes, our blog provides practical tips and life hacks to elevate your quality of living.

At **The Secret Herb**, we delve into the photochemistry of herbs, offering easy-to-follow recipes for condiments, sauces, and medicinal teas. Transform your space into a vibrant healing sanctuary, and explore the magic of nature’s remedies in daily life. Build your personal Herb Café with our curated selection of natural remedies and become the hero of your wellness journey.

Join us as we uncover nature’s treasures and help you rejuvenate your body, mind, and soul!


# Meet our Team

<div class="list-authors mt-5">
{% for author in site.authors %}   
    <div id="{{ author[1].name }}" class="authorbox position-relative pb-5 pt-5 mb-4 mt-4 border">   
        <div class="row">
            <div class="wrapavname col-md-3 text-center">
                {% if author[1].gravatar %}
                <img  class="author-thumb" src="https://www.gravatar.com/avatar/{{ author[1].gravatar }}?s=250&d=mm&r=x" alt="{{ author.display_name }}">
                {% else %}
                <img  class="author-thumb" src="{{site.baseurl}}/{{ author[1].avatar }}" alt="{{ author.display_name }}">
                {% endif %}

                <p class="mt-4 mb-0 small text-center">

                    {% if author[1].web %}
                        <a target="_blank" class="d-inline-block mx-1 text-dark" href="{{ author[1].web }}"><i class="fa fa-link"></i></a> 
                    {% endif %}

                    {% if author[1].twitter %}
                        <a target="_blank" class="d-inline-block mx-1 text-dark" href="{{ author[1].twitter }}"><i class="fab fa-twitter"></i></a>
                    {% endif %}

                    {% if author[1].email %}
                        <a class="d-inline-block mx-1 text-dark" href="mailto:{{ author[1].email }}"><i class="fa fa-envelope"></i></a>
                    {% endif %}

                </p>
                
            </div>
            <div class="col-md-9">
                <h3>{{ author[1].display_name }}</h3>
                <p class="mt-3 mb-0">{{ author[1].description }}</p> 
            </div>
        </div> 
    </div>    
{% endfor %}
</div>

**Please Note:**

The content on thesecretherb.com is meant to complement, not replace, the guidance of your physician. Always consult your doctor before making any changes to your health routine.

Your well-being is our priority, and we’re here to support your wellness journey. For further information or questions, contact us at <a target="_blank" href="mailto:the108matrix@gmail.com">here</a>.


<!-- <form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Send">
</form> -->