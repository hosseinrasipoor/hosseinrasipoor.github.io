---
layout: post
title: a post 2
date: 2024-12-04 01:59:00
description: this is post 2 for training
tags: math images
categories: sample-posts
related_posts: false
---

The images in this post are all zoomable, arranged into different mini-galleries using different libraries.

This is post 2 with image and code and equation


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/iust.jpg" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    in this photo we can see iust map
</div>



this is a math 


$$
\sum \alpha \times \beta ^{\ddot{}} < \begin{bmatrix}
\alpha  & \beta  \\
\varepsilon  & \xi  \\
\end{bmatrix}
$$



this is a code  



{% highlight c++ linenos %}

int main()
{
    string myString;

    cout << "This is code for post 2";

    return 0;

}

{% endhighlight %}
