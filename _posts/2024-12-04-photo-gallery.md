---
layout: post
title: this is the third post
date: 2024-12-04 01:59:00
description: third post
tags: math images
categories: sample-posts
related_posts: false
---

This is post 3 with image and code and equation


this image is logo of our univercity

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/logo.png" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    in this photo we can see iust logo here
</div>



this is a math 


$$
\prod \bigcap \binom{n}{r}\nless \int x^{3}+4x^{4} dx
$$



this is a code  



{% highlight c++ linenos %}

int main()
{
    string myString;

    cout << "This is code for post 3";
    for(int i=0;i<n;i++)
      cout<<"hi "<<endl;
    return 0;

}

{% endhighlight %}
